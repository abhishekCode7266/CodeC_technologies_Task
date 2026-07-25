# Enterprise CRM System

Ye directory `ENTERPRISE CRM SYSTEM.html` mein maujood sample static CRM web UI ke liye README hai.

## Overview
Yeh ek client-side mockup of an Enterprise CRM (Customer Relationship Management) dashboard hai, jo contacts, leads, deals, aur activity tracking jaise common CRM features ko demonstrate karta hai. Sab kuch HTML, CSS aur vanilla JavaScript se implement kiya gaya hai — backend/store simulated hai ya localStorage mein.

## Features
- Contacts & Leads listing
- Deal pipeline (Kanban-style) and status management
- Activity log / notes for contacts
- Simple search/filter and basic metrics dashboard
- All data client-side (localStorage), no real backend

## Tech & Files
- HTML / CSS / JavaScript (no server)
- Key file: `index.html` — UI aur logic dono isi file mein hain

Directory contents:

- `index.html` — Main UI and JavaScript logic
- `README.md` — (this file)

## How to run
1. Local machine par simply `index.html` file ko browser mein open karein (double-click ya browser ka "Open File" option).
2. Ya ek lightweight HTTP server chalayein (recommended for some browser features):
   - Python 3: `python -m http.server 8000` then open `http://localhost:8000/CODEC_TECHNOLOGY_TASK/ENTERPRISE%20CRM%20SYSTEM.html/`

## Notes & Limitations
- Sab data localStorage mein store hota hai; browser ya device change karne par data available nahi rahega.
- Backend, authentication, aur secure data persistence nahi hai — production use ke liye server-side API aur database zaroori hai.
- Folder/file names mein spaces ya special characters hain — deployment aur URLs ke liye rename karna behtar rahega.

## Suggested Improvements
- Server-side API + database (Postgres / MongoDB)
- Authentication & role-based access control
- Import/export CSV/Excel, reporting, and analytics
- Unit tests and accessibility improvements
- Remove spaces from folder name for cleaner URLs

## License
MIT License — use as you like.

---

Agar aap chahte hain to main yeh README English-only mein, ya concise summary ke saath, ya folder rename commit karke safer path bana dun — batayiye, mein karta/ti hoon.