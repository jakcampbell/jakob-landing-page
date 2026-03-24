# Jakob Campbell – Personal Landing Page

## Project Overview

A simple static HTML/CSS personal landing page for Jakob Campbell, a Business Analytics & Information Systems student. The site showcases his background, skills, and experience for recruiters.

## Technology Stack

- HTML5
- CSS3
- No frameworks (plain static site)
- Python's built-in HTTP server for local development

## File Structure

```
project-root/
├── index.html          # Main page (currently a placeholder)
├── css/
│   └── stylesheet.css  # External stylesheet (to be created)
├── images/             # Image assets (to be created)
├── prd.md              # Product Requirements Document
├── standards.md        # Design & coding standards
├── jakobcampbell_resume.docx (1).pdf  # Resume PDF
└── replit.md           # This file
```

## Running Locally

The site is served using Python's built-in HTTP server:
```
python3 -m http.server 5000
```

The "Start application" workflow handles this automatically on port 5000.

## Deployment

Configured as a **static** deployment. The root directory (`.`) is the public directory.

## Design Standards

- Colors: Black (#000000), White (#FFFFFF), Light gray (#f5f5f5)
- Font: Arial, sans-serif
- Max content width: ~1000px
- Sections: Header, About, Experience, Skills, Contact
