# Technical Guidelines

Follow these best practices to ensure your project is well-structured, secure, and maintainable.

---

## 1. Code Organization

### Naming Conventions
- Use **meaningful** variable and function names
- Be consistent with naming style (camelCase, snake_case, etc.)
- Names should describe what the variable/function does

```python
# ❌ Bad
def f(x):
    return x * 2

# ✅ Good
def calculate_double_value(number):
    return number * 2
```

### Function Design
- Keep functions **small and focused** (single responsibility)
- Comment complex logic
- Follow consistent formatting

```javascript
// ❌ Bad - one function doing too much
function handleUser(user, action, data) {
    // 200 lines of code handling multiple things
}

// ✅ Good - separate concerns
function createUser(userData) { /* ... */ }
function updateUserProfile(userId, profileData) { /* ... */ }
function deleteUser(userId) { /* ... */ }
```

---

## 2. Version Control

### Commit Practices

| Do | Don't |
|----|-------|
| Commit frequently with clear messages | Make one giant commit at the end |
| Use present tense ("Add feature" not "Added feature") | Use vague messages like "fix" or "update" |
| Group related changes in one commit | Commit unrelated changes together |

### Example Commit Messages

```
✅ Good commit messages:
- "Add user authentication with JWT"
- "Fix bug in expense calculation"
- "Refactor database connection handling"

❌ Bad commit messages:
- "fix"
- "update"
- "changes"
- "asdfgh"
```

### Security in Version Control

!!! danger "Never Commit Sensitive Data"
    - API keys
    - Database passwords
    - Private keys
    - Personal credentials

Use `.gitignore` properly:

```gitignore
# Environment variables
.env
.env.local
.env.production

# IDE settings
.vscode/
.idea/

# Dependencies
node_modules/
venv/
__pycache__/

# Build outputs
dist/
build/
```

---

## 3. Documentation

### README Essentials

Your README should answer these questions:

1. **What** does this project do?
2. **Why** did you build it?
3. **How** do I set it up and run it?

### Minimum Documentation

- [x] Project title and description
- [x] Installation instructions
- [x] How to run the project
- [x] List of features
- [x] Tech stack used
- [x] Screenshots or GIFs

### API Documentation (if applicable)

Document your API endpoints:

| Method | Endpoint | Description | Request Body | Response |
|--------|----------|-------------|--------------|----------|
| GET | `/api/users` | Get all users | - | Array of users |
| POST | `/api/users` | Create user | `{name, email}` | Created user |
| PUT | `/api/users/:id` | Update user | `{name, email}` | Updated user |
| DELETE | `/api/users/:id` | Delete user | - | Success message |

---

## 4. Error Handling

### Input Validation

Always validate user inputs:

```javascript
// ❌ Bad - trusting user input
function createUser(data) {
    db.insert(data);
}

// ✅ Good - validating input
function createUser(data) {
    if (!data.email || !isValidEmail(data.email)) {
        throw new Error('Invalid email address');
    }
    if (!data.name || data.name.length < 2) {
        throw new Error('Name must be at least 2 characters');
    }
    db.insert(sanitize(data));
}
```

### Handle Edge Cases

Think about what could go wrong:

- What if the database is unavailable?
- What if the user submits an empty form?
- What if the API returns an error?
- What if the file doesn't exist?

### Meaningful Error Messages

```python
# ❌ Bad
raise Exception("Error")

# ✅ Good
raise ValueError("User email cannot be empty")
```

!!! warning "Don't Expose Sensitive Errors"
    Never show database errors or stack traces to end users. Log them internally but show a generic message to users.

---

## 5. Security Best Practices

### Environment Variables

```bash
# ❌ Bad - hardcoded in code
db_password = "supersecret123"

# ✅ Good - use environment variables
db_password = os.environ.get("DB_PASSWORD")
```

Create a `.env.example` file:

```bash
# Database
DB_HOST=localhost
DB_PORT=5432
DB_NAME=your_database
DB_USER=your_username
DB_PASSWORD=your_password

# API Keys
OPENAI_API_KEY=your_openai_key
GOOGLE_API_KEY=your_google_key

# App Settings
SECRET_KEY=your_secret_key
DEBUG=false
```

### Input Sanitization

Prevent injection attacks:

```python
# ❌ Bad - SQL injection vulnerability
query = f"SELECT * FROM users WHERE email = '{email}'"

# ✅ Good - parameterized query
query = "SELECT * FROM users WHERE email = %s"
cursor.execute(query, (email,))
```

### Authentication

- Use established libraries (don't roll your own auth)
- Hash passwords (bcrypt, argon2)
- Use HTTPS in production
- Implement proper session management

---

## Recommended Tech Stacks

### For Rapid Development

=== "Python"
    - **Web Framework:** Flask, FastAPI, Django
    - **Database:** SQLite, PostgreSQL, MongoDB
    - **Frontend:** Jinja templates, React
    - **Visualization:** Matplotlib, Plotly, Chart.js

=== "JavaScript"
    - **Frontend:** React, Vue, Next.js
    - **Backend:** Express, Fastify, Next.js API
    - **Database:** MongoDB, PostgreSQL, Supabase
    - **Real-time:** Socket.io

=== "Full-Stack"
    - Next.js (React + API routes)
    - Django (Python full-stack)
    - Ruby on Rails
    - Laravel (PHP)

### For Data/ML Projects

- Python with pandas, scikit-learn
- Jupyter notebooks for prototyping
- Streamlit for quick UIs
- HuggingFace for pre-trained models

### For Real-Time Features

- Socket.io / WebSockets
- Firebase Realtime Database
- Supabase Realtime
- Redis Pub/Sub
