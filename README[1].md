# LAMBITEK Online Academy - Fullstack with Email

## Setup

### Backend
```bash
cd backend
npm install
npm start
```

### Configure Email
1. Create a `.env` file in `backend/` (already provided as a template).
2. Fill in your Gmail and App Password:

```
MAIL_USER=yourgmail@gmail.com
MAIL_PASS=your_gmail_app_password
RECIPIENT_EMAIL=where_messages_should_go@example.com
```

3. If using Gmail, enable 2FA and generate an **App Password**.
4. Alternatively, replace transporter settings in `server.js` with your SMTP provider.

### Frontend
Static files are served automatically by Express from `frontend/public`.

## Deployment
- Deploy on Render/Heroku/Railway.
- Express serves both frontend and backend together.
