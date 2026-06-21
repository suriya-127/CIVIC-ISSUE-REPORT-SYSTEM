# Civic Issue Project

This project is a static front-end web app for reporting and managing civic issues. It brings together a citizen complaint flow and an authority review flow in one simple browser-based experience.

The goal of the project is to make civic reporting feel direct and organized. Residents can submit complaints, check report status, and generate information that is useful for follow-up. On the other side, authorities can sign in and review complaints through a dashboard-style interface.

## What's Included

- `indexpage.html` - public complaint submission page for residents
- `page.html` - authority login screen
- `dashboard.html` - authority dashboard for reviewing complaints
- `Civic Issue with Report.html` - civic issue reporter interface with a richer citizen portal and report/poster features

## What The Project Covers

- Public issue reporting for problems that need civic attention
- Complaint tracking through a status-checking interface
- Separate authority access for reviewing and managing incoming reports
- A more detailed reporter experience for cases that need extra public visibility, such as missing person posters

## Project Structure

The app is split into a few standalone HTML pages rather than a framework-based build. Each page focuses on one part of the workflow:

- the citizen page collects report details in a form-driven layout
- the authority login page provides access to the internal dashboard
- the dashboard page organizes complaints for review
- the report-focused page adds richer interactions for poster creation and portal navigation

## Design Approach

- The UI is built with plain HTML, CSS, and JavaScript
- Some pages use Tailwind via CDN for faster styling and layout
- The visuals use strong gradients, cards, and modal panels to make the experience feel like a public-service portal rather than a generic form
- Because the project is front-end only, the pages behave as a prototype or demo experience unless backend storage is added later

