# Chapterly

This project was developed as part of the undergraduate course *"Metodologie di Programmazione per il Web"* (Web Programming Methodologies) during the academic year 2020/2021.

> **Note**: This was my **first complete web application**, developed with a focus on learning web technologies and design, **not security**.

## Project Overview

The web application is designed for managing and publishing **article series**, with different roles and interactions for writers and readers.

### Key Features

- **User Roles**: Registered users can act as:
  - **Writers**, who can:
    - Create and manage series of articles
    - Add, edit, and delete episodes
  - **Readers**, who can:
    - Follow series
    - Save favorite episodes
    - Comment on episodes
    - Purchase premium episodes

- **Series**:
  - Consist of a title, description, category, cover image, and a list of episodes
  - Each episode includes a title, description, publish date, full content, and optional sponsor
  - Premium episodes require a simulated credit card form for purchase

- **Guest Access**:
  - Unregistered users can browse all content by category or perform text-based searches on titles and descriptions

- **Search Functionality**:
  - Search episodes or series by keyword
  - Filter by category and type (episodes or series)

- **Profile Page**:
  - Each user has a personal profile page displaying their saved and purchased content

## Technologies Used

The application was built using the technologies taught in the course:

- **Front-End**:
  - HTML5 & CSS3 (with Bootstrap for styling)
  - Vanilla JavaScript (ES6 Classes)

- **Back-End**:
  - Node.js + Express.js
  - SQLite3 as the database engine

- **Programming Style**:
  - Object-oriented JavaScript (ES6)
  - Use of `async/await` and Promises
  - Proper separation of concerns between front-end and back-end
  - Semantic HTML and well-structured, commented source code

## Security Disclaimer

This project was **not developed with security in mind**, as the course focused on the methodology and technology stack rather than secure coding practices.

Do not reuse this code in production environments without significant improvements to authentication, validation, and general security.


## Test Users & Sample Content

To test the application, at least one **writer** and one **reader** account are pre-created, along with a few (3–4) sample series and episodes.

Credentials and sample data can be found in the [istruzioni.txt](node-express/istruzioni.txt) file included in the repository.

## License

This project is licensed under the terms of the [LICENSE](./LICENSE) file.

