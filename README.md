# My Happy Form

A static HTML form page (`index.html`, title “My Happy Form”) with first name, last name, comments, and an optional newsletter subscription. The submit button stays disabled until both name fields have a value. Checking the newsletter box reveals an email field. Submitting the form sends a POST request to `https://jsonplaceholder.typicode.com/users` and shows a success or error message.

## Features

- First and last name required before submit is enabled
- Optional newsletter checkbox that shows an email field
- Client-side POST to JSONPlaceholder
- Success and error messages; the form clears after a successful submit

## Tech stack

- HTML, CSS, and JavaScript (no build step)

## Getting started

Open `index.html` in a browser (or serve the folder, for example `python3 -m http.server`). No install is required.

`App.js` is an unused default Create React App starter component. `ContactList.js` is a React contact-list component that is not used by the form page.
