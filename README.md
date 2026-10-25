# YVL license control

Public signed license catalog for the Windows YVL tool.

- `licenses.dat`: RSA SHA-256 signed machine IDs, expiration times and block status.
- `index.html`: browser admin interface. Import your private key locally to sign changes.
- Client software checks the catalog through HTTPS and verifies the signature with its embedded public key.

Do not commit private keys, GitHub tokens, account lists or the owner-only ZIP bundle.
The web interface supports manual signed-file upload without an API token. Direct saves require a repository-scoped token with Contents write permission; the page does not persist it.

This repository does not provide remote desktop control or host the game application.
