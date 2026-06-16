# LinkIn Pack

Organize, edit, and export browser bookmarks locally with zero installation. Perfect for curating onboarding resources for new team members.

- No install
- No build step
- No upload
- Works by opening `index.html` in a browser

## What It Does

- Open exported bookmark `.html` / `.htm` files
- Add, edit, move, sort, and delete bookmarks
- Add and rename folders
- Search titles and URLs
- Export a browser-compatible bookmark HTML file

## How To Use

1. Open `index.html`.
2. Click **Open bookmark file**.
3. Choose a bookmark HTML file exported from your browser.
4. Edit the folders and URLs.
5. Click **Export HTML**.
6. Import the new file back into your browser.

## Project Management Onboarding Use Case

Project managers and team leads can use this to prepare a clean bookmark file for new joiners.

The goal is to give people one organized import with the tools they need on day one: CRM, project boards, design files, docs, reports, and internal processes.

```mermaid
flowchart LR
    subgraph Lead["Project Manager / Team Lead"]
        A[Curate Team URLs] --> B[Organize by Workflow]
        B --> C[Export HTML]
        C --> D[Share with New Joiners]
    end

    subgraph Joiner["New Joiner"]
        E[Import into Browser]
    end

    D --> E
```

Example:

```text
Project Team Bookmarks
+-- Start Here
|   +-- Team handbook
|   +-- Project overview
|   +-- Onboarding checklist
+-- CRM & Sales
|   +-- Salesforce / HubSpot
|   +-- Customer accounts
|   +-- Pipeline dashboard
+-- Project Delivery
|   +-- Jira / Linear / Asana
|   +-- Sprint board
|   +-- Roadmap
+-- Design & Product
|   +-- Figma
|   +-- Product specs
|   +-- Design system
+-- Docs & Knowledge
|   +-- Notion / Confluence
|   +-- Meeting notes
|   +-- Process docs
+-- Reporting
    +-- BI dashboard
    +-- OKRs
    +-- Status reports
```

## Browser Support

The app reads and writes the standard Netscape bookmark HTML format used by most browsers.

