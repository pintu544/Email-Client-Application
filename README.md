# Email Client Application

This email client application mimics the functionalities of Outlook. It allows users to view their emails, mark them as favorites, and filter them based on different criteria such as read, unread, and favorites.

## How to Run the App Locally

To run the app locally, follow these steps:

```bash
git clone <[repository-url](https://github.com/pintu544/Email-Client-Application)>
cd Email-Client-Application
yarn dev
```

## Features

### Email List

The app displays a list of emails, showing details such as sender, subject, short description, date, and time. Each email item is represented with an avatar (circular logo) populated with the first character of the sender's first name.

### Email Filtering

Users can filter emails based on the following criteria:

- **All Emails:** Displays all emails.
- **Read Emails:** Displays only read emails.
- **Unread Emails:** Displays only unread emails.
- **Favorite Emails:** Displays only emails marked as favorites.

### Email Details Page

When a user clicks on a particular email, the app splits the screen into a master-slave layout. The master (left) section shows the email list with the selected email item, while the slave (right) section displays the email details, including subject, body, and date/time.

### Mark as Favorite

Users can mark any email as a favorite by clicking on the email item and then clicking the "Mark as Favorite" button in the email body section.

### Read/Unread Styles

Read and unread emails are visually distinguished using different CSS styles to enhance user experience and help users quickly identify their unread messages.

## Tech Stack

- **React:** JavaScript library for building user interfaces.
- **Redux Toolkit:** State management library for managing the application state efficiently.
- **React Router:** Declarative routing for React.js applications, allowing navigation among views of various components.
- **Vanilla CSS:** Simple and lightweight CSS styles for a minimalist visual design.

## Note

- This application was created as a solution to a problem statement.
- The codebase adheres to modern JavaScript standards (ES6/ES7), ensuring a clean and maintainable code structure.
- The application's user interface closely resembles the provided mockups, following a minimalist visual design using semantic HTML tags and CSS.

