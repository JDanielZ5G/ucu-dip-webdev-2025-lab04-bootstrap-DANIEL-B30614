&nbsp;UCU DIP WebDev 2025 - Lab 04: Bootstrap 5 Basics

&nbsp;Overview

This repository contains the Week 4 Lab assignment for building a responsive "Campus Events" page using Bootstrap 5. The page features a navbar that collapses on mobile, a grid layout with a hero section, a cards grid for events, a form with validation styles, and a modal dialog. No custom CSS was used—only Bootstrap CDN and utilities.



Goal: Practice Bootstrap components like Navbar, Grid, Cards, Forms, and Modal.



Built on: October 02, 2025  

Due Date: \[Set your due date, e.g., October 09, 2025] 23:59 EAT



&nbsp;Files

\- `index.html`: The main HTML file using Bootstrap CDN only.

\- `full-page.png`: Screenshot of the full page (desktop view).

\- `modal-open.png`: Screenshot with the modal open.



&nbsp;How to View

1\. Clone the repo: `git clone https://github.com/<your-username>/ucu-dip-webdev-2025-lab04-bootstrap-<firstname>-<studentID>.git`

2\. Open `index.html` in any modern browser.

3\. Use browser DevTools (F12) to test mobile view: Toggle device toolbar and select a mobile device.



&nbsp;Features Practiced

\- Navbar: Collapses on mobile with toggler.

\- Grid Layout + Hero: Responsive row with text and icon, button triggers modal.

\- Cards Grid: 3–6 event cards that stack on mobile, 2-col on sm, 3-col on lg.

\- Forms: Row-based layout with required fields, validation styles/feedback, and JS for submit handling.

\- Modal: JS component for quick event add, triggered from hero.

\- Utilities: Spacing (py-5, g-4), colors, flex (d-flex, justify-content-between).



Bonus: Incorporated mini-challenges like adding spacing utilities and a calendar icon in the hero.

&nbsp;Screenshots

&nbsp;Full Page (Desktop View)

!\[Full Page Screenshot](./full-page.png)



&nbsp;Modal Open

!\[Modal Open Screenshot](./modal-open.png)



&nbsp;Common Fixes Applied

\- Ensured Bootstrap bundle JS is after HTML content for toggler/modal to work.

\- Added Bootstrap Icons CDN for the calendar icon (`<i class="bi bi-calendar-event fs-1"></i>`).

\- Form validation: Used `needs-validation` class and JS to add `was-validated` on submit.

\- Tested responsiveness: Cards and grid adjust properly on mobile/desktop.





