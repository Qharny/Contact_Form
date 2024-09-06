# Contact Form with EmailJS

This project implements a simple contact form that sends email notifications using EmailJS. It includes HTML for the form structure, CSS for styling, and JavaScript for form submission and email sending functionality.

## Features

- Responsive contact form
- Email notification upon form submission
- Uses EmailJS for sending emails directly from client-side JavaScript

## Prerequisites

Before you begin, ensure you have met the following requirements:
- You have a basic understanding of HTML, CSS, and JavaScript
- You have signed up for a free account at [EmailJS](https://www.emailjs.com/)

## Installation

1. Clone this repository or download the files:
   - `index.html`
   - `script.js`

2. Sign up for EmailJS and obtain your User ID, Service ID, and Template ID.

3. Open `script.js` (or the `<script>` section in your HTML file) and replace the placeholders:
   ```javascript
   emailjs.init("YOUR_USER_ID");
   emailjs.send('YOUR_SERVICE_ID', 'YOUR_TEMPLATE_ID', templateParams)
   ```

## Usage

1. Open `index.html` in a web browser to view the contact form.

2. Fill out the form with your name, email, subject, and message.

3. Click the "Send Message" button to submit the form.

4. If successful, you'll see an alert confirming that your message was sent.

## Customization

- To modify the form fields, edit the HTML in the `<form>` section of `index.html`.
<!-- - To change the styling, edit the CSS in the `<style>` section or in `styles.css` if it's a separate file. -->
- To modify the email template, log in to your EmailJS account and edit the email template you created.

## Troubleshooting

- If emails are not being sent, check the console for error messages.
- Ensure that your EmailJS User ID, Service ID, and Template ID are correctly inserted in the JavaScript code.
- Verify that your EmailJS account is active and that you haven't exceeded the free tier limits.

## License

This project is open source and available under the [MIT License](https://github.com/Qharny/Contact_Form/blob/main/LICENSE).

## Contact

If you have any questions or feedback, please open an issue in this repository.