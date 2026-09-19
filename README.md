# Ghostpost

A polished, static temporary-mail client powered by the public [mail.tm](https://docs.mail.tm) API.

- No signup, app backend, analytics, or bundled secrets
- Multiple simultaneous inboxes, custom aliases, copy and QR
- Live polling with interval controls, message preview and attachments
- Credentials remain in session storage by default
- Optional local WebCrypto AES-GCM vault (PBKDF2, 180k iterations)
- Plain-language privacy notes and human-readable errors

## Privacy boundary
Messages are received and retained by mail.tm under its own terms. Do not use disposable mail for banking, account recovery, health records, or sensitive personal data. The app itself sends requests directly from the browser to mail.tm.
