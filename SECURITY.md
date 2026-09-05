# CodeMaster Security Baseline

## Production controls
- Use HTTPS only.
- Keep private keys and service-account credentials off the frontend.
- Authenticate users server-side / through Firebase Authentication.
- Authorize every admin action using server-enforced roles.
- Use Firestore Security Rules and test them with the Firebase Emulator.
- Validate and sanitize all user input.
- Use a strict Content Security Policy after listing required trusted origins.
- Set X-Content-Type-Options, Referrer-Policy and Permissions-Policy.
- Keep dependencies updated and remove unused third-party scripts.
- Log security-relevant admin events without storing secrets.

No application can honestly promise 100% security. Review and testing are required before production.
