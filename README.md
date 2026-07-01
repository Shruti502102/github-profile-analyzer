# GitHub Profile Analyzer

## Intern Details
- **Full Name:** Shruti Srivastava
- **Intern ID:** CITS4083
- **No. of Weeks:** 4 Weeks
- **Project Name:** GitHub Profile Analyzer
- **Project Scope:** Build a client-side tool that consumes a public third-party REST API (GitHub's) to fetch and display a user's profile information, repository statistics, and language usage, handling loading states, missing users, and API rate-limit errors gracefully.

## Overview
Look up any public GitHub username to view their profile stats, top repositories by star count, and a language breakdown across their repos, powered by the public GitHub REST API.

## How to Run
This is a single self-contained `index.html` file -- no build step, no dependencies, and no installation required.
1. Clone this repository.
2. Open `index.html` directly in your browser (double-click it, or right-click -> Open With -> Browser).
3. For features that call an external API (if applicable), serve the file locally instead of opening it directly:
   ```
   python3 -m http.server 8000
   ```
   then visit `http://localhost:8000` in your browser.

## Folder Structure
```
github-profile-analyzer/
├── index.html      # Complete application (HTML, CSS, and JS in one file)
└── README.md        # Project documentation
```

## Tech Stack
Vanilla HTML, CSS, and JavaScript -- no frameworks, libraries, or external build tools.
