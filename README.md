# Google Book Search Application

This application provides a book search engine that allows users to search for books, view search results, save books to their account, view saved books, and remove books from their account. Users can also log in or sign up to access additional features.

## Table of Contents

- [Features](#features)
- [Usage](#usage)
- [Screenshots](#screenshots)
- [Dependencies](#dependencies)
- [Contributing](#contributing)
- [License](#license)

## Features

The Google Book Search application includes the following features based on the specified acceptance criteria:

- Menu with options:
  - Search for Books
  - Login/Signup

### Search for Books

- Search Input Field
- Submit Button

### Guest User

- Search for books without logging in
- View search results, each with:
  - Book title
  - Author
  - Description
  - Image
  - Link to the book on the Google Books site

### Authentication

- Modal for Login/Signup
- Toggle between Login and Signup
- Signup:
  - Username input
  - Email address input
  - Password input
  - Signup button
- Login:
  - Email address input
  - Password input
  - Login button

### Logged In User

- Search for books
- View search results with the ability to save books to the account
- Menu options change to:
  - Search for Books
  - See saved books
  - Logout

- See saved books, each with:
  - Book title
  - Author
  - Description
  - Image
  - Link to the book on the Google Books site
  - Button to remove a book from the account

- Logout button to log out of the site

## Usage

1. Clone the repository.
2. Install dependencies using `npm install`.
3. Run the application using `npm start`.
4. Access the application through a web browser at the specified URL.

## Screenshots
![Example Image](/Assets/Screenshot%202023-09-19%20at%209.01.56%20AM.png)



## Dependencies

- React: JavaScript library for building user interfaces.
- Apollo Client: A fully-featured, caching GraphQL client.
- Bootstrap: CSS framework for styling the application.

## Contributing

Feel free to contribute to this project. Fork the repository, make your changes, and submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).