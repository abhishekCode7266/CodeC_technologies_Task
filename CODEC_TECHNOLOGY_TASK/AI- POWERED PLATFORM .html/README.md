# AI-Powered ATS & Recruitment Platform

Ye directory `AI- POWERED PLATFORM .html` mein maujood sample static web UI ke liye README hai.

## Overview
Yeh ek simple, client-side AI-powered Applicant Tracking System (ATS) mockup hai. Isme resume parsing simulation, AI match scoring, kanban pipeline, aur interview scheduler jaise features diye gaye hain—sab HTML, CSS aur vanilla JavaScript se implement kiya gaya hai.

## Features
- Resume text se skills extract karne wala simulated parser
- Job role ke target skills ke base par AI match score calculation
- Candidates ki Kanban pipeline (Applied → Screened → Interview → Offered → Hired)
- Candidates ki listing aur top AI-matched candidates view
- Interview scheduler (localStorage mein save hota hai)
- Drag & drop support for moving candidates across stages

## Tech & Files
- HTML / CSS / JavaScript (no backend)
- Key file: `index.html` — UI + logic sab isi file mein hai

Directory contents:

- `index.html` — Main UI and JavaScript logic
- `README.md` — (this file)

## How to run
1. Local machine par simply `index.html` file ko browser mein open karein (double-click ya browser ka "Open File" option).
2. Ya ek lightweight HTTP server chalayein (recommended for some browser features):
   - Python 3: `python -m http.server 8000` then open `http://localhost:8000/CODEC_TECHNOLOGY_TASK/AI- POWERED PLATFORM .html/`

## Notes & Limitations
- Sab kuch client-side storage (localStorage) mein store hota hai; page clear ya browser change karne par data alag ho sakta hai.
- Resume parsing aur AI scoring simulated hain — production use ke liye real NLP parsing aur server-side persistence zaroori hai.
- File path mein spaces aur special characters (`AI- POWERED PLATFORM .html`) hain — deployment mein URL encoding ya folder rename consider karein.

## Suggested Improvements
- Real resume parser (server-side or via APIs) + persistent database
- Authentication aur role-based access
- Export/import candidates (CSV/JSON)
- Unit tests aur accessibility improvements

## License
MIT License — use as you like.

---

If you want this README in full English, or want me to create a shorter README badge, or rename the folder to remove spaces, tell me and I'll update it.