# VaultRAG Document Assistant

A file-only document search and chat prototype. It searches administrator-uploaded files, supports cross-file references, and returns point-wise answers with source metadata when available.

## Run locally

Open `index.html` in a modern browser. PDF and DOCX extraction use the libraries referenced by the page, so those formats require an internet connection while loading the page.

## Multi-user testing limits

This is a static prototype. Uploaded documents and settings are stored in each visitor's browser, so different testers do not share uploads or chat state. The demo admin login is client-side and is not production access control. Do not upload confidential documents or real credentials. Shared documents and real access control require a backend service.
