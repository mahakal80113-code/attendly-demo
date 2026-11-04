# Attendly — College Attendance Demo

A premium black-and-white, browser-based interactive demo for a college/university attendance workflow.

## Demo access
No login is required. Open `index.html` in a modern browser.

## Included
- Teacher-style overview dashboard
- Create college attendance sessions and customize slip headings
- Student details form and personal QR slip generation
- Camera QR scanning where HTTPS/camera permissions are available
- Simulated scan flow for reliable presentations
- Confirm or reject attendance after visual identity check
- Grant/revoke scanner access UI
- Attendance records and CSV export
- Browser-local demo data persistence

## Important limitations
This is a presentation prototype only. It has no real authentication, server, shared database, roster verification, secure signed QR tokens, or cross-device synchronization. Demo QR payloads are not secure proof of identity or physical presence. Do not use real student data or rely on it for official attendance.

## Hosting
Upload the extracted contents of this folder to a static hosting provider with `index.html` at the repository root. HTTPS is required for camera access on most devices. The QR generator and optional camera scanner use external CDN libraries.
