# Student Management System (SIWES Frontend Demo)

A beginner-friendly project using HTML, CSS, Bootstrap 5.3.3 and JavaScript.

## Run the project

1. Extract this ZIP folder.
2. Open `index.html` in a modern browser. If your browser restricts local storage for local files, open the folder with a simple local development server instead.
3. Choose **Enter as Student** to register a demo student or open an existing student record.
4. Choose **Lecturer Login** and use the demo credentials shown on the homepage.
5. On the lecturer page, use **Load sample data** to populate invented example records for testing.

## Files

- `index.html` — homepage and demo lecturer login form.
- `student.html` — student registration, courses, dashboard and attendance history.
- `lecturer.html` — lecturer dashboard, student list, attendance entry and session history.
- `css/style.css` — custom responsive styles layered on Bootstrap.
- `js/main.js` — shared helpers, browser storage, role navigation and attendance calculations.
- `js/student.js` — student portal behavior.
- `js/lecturer.js` — lecturer portal behavior and CSV export.

## Improvements in this version

- Refreshed colour palette, typography, cards, form fields, buttons and tables.
- Better small-screen spacing and accessible navigation labels.
- Added labels and live announcements for important form messages.
- Prevented future dates from being used for attendance.
- New attendance sheets do not preselect everyone as Present. The lecturer must choose Present or Absent for every student before saving.
- Added CSV export for recorded attendance sessions. The CSV contains date, course, student, matriculation number, department, level and status.
- Added clearer handling when browser storage cannot save data.
- Improved email validation using the browser's built-in input validation.

## Demo limitations

This is still a **frontend-only learning project**. Student records and attendance are stored in the current browser using `localStorage`; they are not shared across devices. The lecturer credentials and role checks are visible and changeable in browser-side code. A real school system needs server-side authentication, authorization and a shared database. Do not use real sensitive student information in this demo.

## Technologies

HTML, CSS, Bootstrap 5.3.3, and beginner-level JavaScript. Bootstrap is loaded from a CDN, so an internet connection is needed for Bootstrap styling and components unless Bootstrap files are downloaded and linked locally.
