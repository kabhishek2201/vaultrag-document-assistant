# VaultRAG Document Assistant

A file-only document search and chat prototype.

- `index.html` — Admin and architecture demo.
- `user.html` — Separate user-only chat page with a blank conversation and the Loan Policy greeting. It reads the bundled circulars from `documents.json` for every visitor, then adds active uploads from the same browser.

## Run locally

Open either HTML file in a modern browser. PDF and DOCX extraction on the admin page use referenced libraries and need an internet connection while loading.

## Storage and multi-user testing

This is a static prototype. Admin uploads are stored in that browser's local storage. The two bundled Loan Policy circulars are available to every visitor through `documents.json`. Additional admin uploads remain in that browser's local storage and are not shared to other testers. Shared uploads and real access control require a backend service.

The demo admin sign-in is client-side and is not production access control. Do not upload confidential documents or real credentials.
