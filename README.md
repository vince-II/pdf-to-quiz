# PDF Note to Quiz Converter

This project is a web application that allows users to upload a PDF note and automatically converts its content into a quiz. The generated quiz is formatted into a document, and a built-in mailer service sends it directly to the user's email.

---

## Features

- **PDF Upload**: Users can upload their notes in PDF format.
- **Quiz Generation**: Converts the uploaded PDF content into a structured quiz.
- **Mailer Service**: Sends the generated quiz document to the user's email address.
- **User-Friendly Interface**: Simplified design for seamless interaction.


## Note:

- currently frontend is being developed
---

## Installation

### Prerequisites

- Node.js and npm installed
- A Mailer service API key (e.g., SendGrid, SMTP)

### Steps

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/pdf-to-quiz.git
   cd pdf-to-quiz
2. Install dependencies:
   ```bash
   git clone https://github.com/yourusername/pdf-to-quiz.git
   cd pdf-to-quiz
3. Set up environment variables: Create a .env file in the root directory and add the following:
    ```bash
    PORT=3000
    MAILER_SERVICE_API_KEY= xxxxxxxxxxx
4. Start the development server:
    ```bash
    npm run dev
5. Open the application in your browser
    ```bash
    http://localhost:3000
