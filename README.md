# Campus OD — Event & On-Duty prototype

Open `index.html` in a modern browser. No build step, package install, or server is required.

Choose a role on the sign-in screen to preview the Student, Event Coordinator, Class In-charge, Department Coordinator, Director, or DEO workspace. The sample requests and events persist in that browser using local storage.

This is a front-end prototype. Uploaded files are represented by their selected file names; files are not sent to a server. To restore the original sample data, clear this site’s local storage for the page.

## Demo sign-in

The landing screen provides sign-in entry points for Student, Event Coordinator, Class In-charge, Department Coordinator, Director, and DEO. Use any ID/email and the password `demo123`. Sign out from the top bar to return to the role selection screen. This is a UI prototype; sign-in is not backed by real identity verification.

## Code map

- `index.html` is the entry page and loads the stylesheet and JavaScript files.
- `styles.css` contains layout, component, responsive, and sign-in styles.
- `js/data.js` holds sample records, roles, navigation labels, and shared helpers.
- `js/pages.js` builds the dashboards, forms, queues, and detail pages.
- `js/actions.js` handles sign-in, navigation, event registration, reviews, and attendance.

