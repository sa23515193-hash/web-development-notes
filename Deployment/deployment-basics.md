# Deployment Basics

A typical frontend deployment flow:

```text
Local Project
    ↓
Build
    ↓
Upload / Connect Repository
    ↓
Hosting Platform
    ↓
Live Website
```

## Security Checklist

Never commit:

```text
.env
API keys
Database passwords
Private tokens
Secret credentials
```

Use environment variables for secrets.

## Production Checklist

- Test links
- Test images
- Test API requests
- Test mobile layout
- Check console errors
- Verify environment variables
