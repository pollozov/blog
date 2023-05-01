# Project Overview

This is a web application for a blog, built with NodeJS and ReactJS. The backend is built with NodeJS, Express, and MongoDB/Mongoose, while the frontend is built with ReactJS and Redux Toolkit. The project also uses various libraries such as Validator, JSON Web Token, Multer, bcrypt, React Hook Form, React Router, React Markdown, and Axios.

# Installation and Setup

1. Clone the project from GitHub using the following command:

```
https://github.com/pollozov/blog.git
```

2. Navigate to the project directory using the terminal:

```
cd blog
```

3. Install the dependencies for both the frontend and backend by running the following commands:

```
cd blog && npm install
```

4. Start the server by running the following command in the backend directory:

```
npm run start:dev
```

5. Start the client by running the following command in the frontend directory:

```
npm start
```

6. Open http://localhost:4444 in your browser to view the web application.

# Features

The blog application has the following features:

1. Authentication and Authorization
- Users can sign up, log in, and log out using JSON Web Tokens (JWT).
- Authenticated users can create, edit, and delete their blog posts.

2. Blog Posts
- Users can view all the blog posts on the homepage.
- Authenticated users can create, edit, and delete their blog posts.
- Users can view individual blog posts.

3. Markdown Support
- Blog posts support markdown formatting using the React Markdown library.

# Future Enhancements
The following features are planned for future releases:

1. User Roles
- Implement different user roles such as admin and author.

2. Search Functionality
- Add a search functionality to the blog application to allow users to search for blog posts based on keywords.

3. Social Sharing
- Add social sharing functionality to allow users to share blog posts on social media.

# Conclusion
This project is a simple but functional blog application built with NodeJS and ReactJS. It can be used as a starting point for more complex blog applications or as a learning resource for those new to NodeJS and ReactJS.