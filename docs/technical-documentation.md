# Technical Documentation

## Project Overview

This project is a responsive personal portfolio website that aims to help us toward our professional portifolio. It introduces me, presents my main projects, shows my skills and interests, and provides contact information for future communication.

The website was created only using HTML, CSS, and JavaScript .

## Technologies Used

- HTML for the structure and content.
- CSS for the design and responsive layout.
- JavaScript for interactions.
- GitHub for version control.
- Live Server for local testing.
- ChatGPT for development guidance.
- TeleportHQ and Webstudio for design exploration.

## Project Structure

project-folder/
├── index.html
├── README.md
├── .gitignore
├── css/
│   └── styles.css
├── js/
│   └── script.js
├── assets/
│   └── images/
│       ├── seraj-project.jpg
│       └── networking-assistant.jpg
└── docs/
    ├── ai-usage-report.md
    └── technical-documentation.md



## HTML Structure
Navigation

The navigation provides links to the main sections of the page. Each link uses a section ID to move the visitor to the correct part of the website.

Hero

The hero section displays my name, tagline, and a greeting that changes depending on the time of day.

About Me

This section introduces me as a software engineering student, graphic designer, and someone interested in technology and programming.

Projects

The Projects section presents:

Seraj, a virtual reality game about Saudi culture.
Networking Assistant, a project related to computer networks.

Each project includes a title, description, image, and related topics.

Skills and Interests

This section shows my interests in programming, graphic design, cloud computing, and artificial intelligence.

Contact

The Contact section contains my university email, LinkedIn profile, and a form with Name, Email, and Message fields.

The form is a demonstration because this assignment does not require a backend. JavaScript displays a message when the form is submitted.

## CSS Design
CSS variables are used to manage the main colors. This makes it easier to change the appearance without editing every CSS rule.

Flexbox is used for navigation and alignment. CSS Grid is used for the project cards and interests.

Media queries change the layout for smaller screens. On mobile devices, the project cards, interest cards, and contact links are displayed in one column.

Project images use object-fit: cover so that they remain consistent inside their cards.

## JavaScript Features
Time-Based Greeting

JavaScript gets the current hour using new Date().getHours(). An if/else condition displays a morning, afternoon, or evening greeting.

Contact-Form Feedback

An event listener detects when the contact form is submitted. It prevents the page from refreshing and displays a demonstration confirmation message.

Automatic Copyright Year

JavaScript gets the current year and places it in the footer automatically.

Dark Mode

The theme button adds or removes the dark-theme class from the page. The CSS changes its color variables when this class is active.

The selected theme is stored using localStorage, so the website remembers the visitor's preference after the page is refreshed.

## Testing

I tested the website using Live Server and browser developer tools.

## Limitations

The contact form does not send or save messages because the project does not include a backend.

