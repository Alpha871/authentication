

---

# 🛡️ Fundamental of Authentication App

This project demonstrates core concepts of modern authentication in web applications. It includes secure session management, OAuth integration, and route access control for users and admins.

## 🔐 Features

### ✅ Session Management
- Uses **Redis** to manage user sessions.
- Sessions are stored server-side and tracked via **HTTP cookies** for security and scalability.

### 🔗 OAuth Authentication
- Supports **OAuth** login (e.g., Google, GitHub) to allow users to authenticate through third-party providers.
- Handles OAuth callback, token exchange, and session creation.

### 🔒 Protected Routes
- **Private Routes**: Only accessible to authenticated users.
- **Admin Routes**: Restricted to users with admin privileges.

## 🧰 Tech Stack
- Backend: Nextjs
- Session Store: Redis
- Auth: OAuth 2.0, Cookie-based sessions

## 🚀 Getting Started

1. Clone the repo  
   ```bash
   git clone https://github.com/yourusername/yourrepo.git
   ```

2. Install dependencies  
   ```bash
   npm install  # or your package manager
   ```

3. Set up environment variables  
   ```
   # Redis
REDIS_URL=
REDIS_TOKEN=

# Database
DB_PASSWORD=
DB_USER=
DB_NAME=
DB_HOST=

# OAuth
OAUTH_REDIRECT_URL_BASE=

# Discord
DISCORD_CLIENT_ID=
DISCORD_CLIENT_SECRET=

# GitHub
GITHUB_CLIENT_ID=
GITHUB_CLIENT_SECRET=

   ```

4. Run the app  
   ```bash
   npm start  # or your dev command
   ```





