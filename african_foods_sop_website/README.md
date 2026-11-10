# African Foods Company (AFC) — SOP Portal

A responsive static website prototype for the WIL Task 2 project. It provides a main page linking to IT Security, Acceptable Use, IT Acquisition, Help Desk, Disaster Recovery, and Document Control / IT Structure.

## Files

```text
african_foods_sop_website/
├── index.html
├── security.html
├── acceptable-use.html
├── acquisition.html
├── help-desk.html
├── disaster-recovery.html
├── document-control.html
├── css/
│   └── styles.css
├── assets/
└── README.md
```

## How to run it on Windows

1. Download and extract `african_foods_sop_website.zip`.
2. Open the extracted folder.
3. Double-click `index.html`. It should open in your browser.
4. Use the navigation menu or the SOP directory cards to visit the other pages.
5. To edit the code, open the folder in Visual Studio Code (File → Open Folder), then edit the HTML files or `css/styles.css`.
6. Save your changes and refresh the browser.

No server, JavaScript framework, database, API key, or paid service is required for this local demonstration.

## How the code works

- Each `.html` file is one website page.
- `<a href="...">` links connect the pages.
- `css/styles.css` controls shared colours, layout, cards, tables, responsive breakpoints, focus indicators and print styling.
- The small JavaScript block in `index.html` filters SOP cards as the user types in the search field.
- The site is static. The search filters the directory only; it does not search inside the text of all pages.

## Important implementation notes

- This is a prototype prepared from the WIL Task 2 brief and the previously discussed AFC network design context.
- Policy content, help-desk response targets, disaster recovery targets and reporting lines are proposals, not verified existing AFC policy. Have management approve and adapt them before real operational use.
- Do not put passwords, VPN keys, administrator credentials, private employee information or sensitive network configurations in public HTML or a public GitHub repository.
- For real internal use, host the site on an approved intranet platform and configure access controls at the hosting/platform level. Hiding a link in HTML is not access control.
- Replace any placeholder contact information with AFC's approved contacts before deployment. This prototype intentionally does not invent phone numbers or email addresses.
- The public company website and internal SOP portal should not automatically be hosted together. Follow the organisation's network and security design.
