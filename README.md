# Ticket Creation Page

This project is a Ticket Creation Page where employees can raise tickets to the company. It is built using React for the frontend and includes backend functionality with Express for handling file uploads. The form data is stored in a MySQL database using XAMPP.

## Table of Contents


- [Getting Started](#getting-started)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Contributing](#contributing)
- [License](#license)

## Getting Started

These instructions will help you set up the project locally.

### Prerequisites

Make sure you have the following installed on your machine:

- [Node.js](https://nodejs.org/en/)
- [npm](https://www.npmjs.com/)
- [XAMPP](https://www.apachefriends.org/index.html)

### Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/yourusername/ticket-creation-page.git
   cd ticket-creation-page
   
2. **Install frontend dependencies:**

    ```bash
    cd ticketform
    npm install

### Set up XAMPP:

1. Start the Apache and MySQL modules from the XAMPP control panel.
2. Create a new database named `form_data` in phpMyAdmin.
3. create a table names submissions and create fields.

### Start the backend server:

```bash
cd server
node update.js
```

### Start the frontend:

```bash
cd ticketform
npm start
```

### Usage
Open your browser and go to http://localhost:3000 to access the Ticket Creation Page.
Fill out the form and submit it to create a new ticket.
Attach any necessary documents using the file upload feature.

## Project Structure

```plaintext
TicketCreate/
├── ticketform/
│   ├── public/
│   ├── src/
│   ├── package.json
│   └── ...
├── server/
│   ├── uploads/
│   ├── update.js
└── README.md


    
