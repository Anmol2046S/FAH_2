# Security Policy

## Reporting Vulnerabilities

Please report security vulnerabilities to: **security@example.com**

Do NOT create public GitHub issues for security vulnerabilities.

## Security Best Practices

### For Users
- Keep browser updated
- Use strong API keys
- Never share credentials
- Use HTTPS only
- Clear browser cache regularly

### For Developers
- Never commit API keys
- Validate all inputs
- Sanitize outputs
- Use HTTPS in production
- Set proper CORS headers
- Keep dependencies updated
- Use Content Security Policy
- Enable HSTS

## Security Headers

Recommended headers:
```
Strict-Transport-Security: max-age=31536000
X-Content-Type-Options: nosniff
X-Frame-Options: DENY
X-XSS-Protection: 1; mode=block
Content-Security-Policy: default-src 'self'
```

## Supported Versions

| Version | Status | Support Until |
|---------|--------|---------------|
| 1.0.x   | Active | 2027-07-21   |
| 0.x     | EOL    | 2026-07-21   |

## Security Update Timeline

- Critical: Fixed within 24 hours
- High: Fixed within 1 week
- Medium: Fixed within 1 month
- Low: Fixed in next release

---

**Last Updated**: 2026-07-21