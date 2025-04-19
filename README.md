
---

# 🛡️ Fundamental of Authentication App

This project demonstrates the core concepts of modern authentication in web applications. It includes secure session management, OAuth integration, and access control for private and admin-only routes.

## 🔐 Features

### ✅ Session Management
- Uses **Redis** to manage user sessions.
- Sessions are stored server-side and tracked via **HTTP cookies** for better security and scalability.

### 🔗 OAuth Authentication
- Supports **OAuth** login (e.g., Discord, GitHub) through third-party providers.
- Handles OAuth callbacks, token exchange, and session creation.

### 🔒 Protected Routes
- **Private Routes**: Accessible only to authenticated users.
- **Admin Routes**: Restricted to users with admin privileges.

## 🧰 Tech Stack
- **Framework**: Next.js  
- **Session Store**: Redis  
- **Authentication**: OAuth 2.0, cookie-based sessions

## 🚀 Getting Started

1. **Clone the repo**  
   ```bash
   git clone https://github.com/yourusername/yourrepo.git
   ```

2. **Install dependencies**  
   ```bash
   npm install
   ```

3. **Set up environment variables**  
   Create a `.env.local` file and add the following:

   ```env
   # Redis
   REDIS_URL=
   REDIS_TOKEN=

   # Database
   DB_USER=
   DB_PASSWORD=
   DB_NAME=
   DB_HOST=

   # OAuth Redirect
   OAUTH_REDIRECT_URL_BASE=

   # Discord OAuth
   DISCORD_CLIENT_ID=
   DISCORD_CLIENT_SECRET=

   # GitHub OAuth
   GITHUB_CLIENT_ID=
   GITHUB_CLIENT_SECRET=
   ```

4. **Run the app**  
   ```bash
   npm run dev
   ```

---

