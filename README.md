# Bajaj-Finserv-Health-Dev-Challenge
Bajaj Finserv Health Dev Challenge (Qualifier 1)
# BFHL Frontend

## Overview

BFHL Frontend is a React application designed to submit and process JSON data. Users can input JSON, submit it to a backend server, and view specific parts of the response based on their selection from a multiselect dropdown. The application includes error handling to provide feedback if the user submits invalid JSON.

## Features

- **JSON Submission**: Enter JSON data and submit it to a backend server.
- **Multiselect Dropdown**: Select multiple options to display specific parts of the response.
- **Error Handling**: Warnings for invalid JSON or submission errors.

## Installation

1. **Clone the Repository**

   ```bash
   git clone https://github.com/Samikshashreya/Bajaj-Finserv-Health-Dev-Challenge.git
   ```
2. **Install Dependencies**
   
```bash
npm install
```
3. **Start the Development Server**

```bash
npm start
```
The application will be available at http://localhost:3000.

## Usage
Enter JSON Data: Input valid JSON data into the textarea.

Submit Data: Click the "Submit" button to send the data to the backend.

Select Options: Use the multiselect dropdown to choose what data to display.

View Results: The response will be displayed based on selected options.

## Error Handling
**Invalid JSON:** Displays a warning message if the JSON data is malformed.

**Submission Errors:** Shows a warning for any issues that occur during data submission.

## Dependencies
React

axios

react-select

