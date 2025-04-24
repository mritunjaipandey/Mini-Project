# Student Enrollment Form

# Overview

The Student Enrollment Form is a web application that allows users to input student details for enrollment in a school. The form collects essential information such as roll number, full name, class, birth date, address, and enrollment date. Upon submission, the data is sent to a backend API for processing.

# Features

- User-friendly interface built with Bootstrap for responsive design.
- Form validation to ensure all fields are filled before submission.
- Ability to reset the form to clear all input fields.
- Integration with a backend API to store student data.

# Technologies Used

- HTML
- CSS (Bootstrap)
- JavaScript (jQuery)
- API for data submission


# Prerequisites

- A web browser to run the application.
- Internet connection to access external libraries (Bootstrap and jQuery).

### Installation

1. Clone the repository or download the HTML file.
2. Open the `index.html` file in your preferred web browser.

# Usage

1. Fill in the required fields in the enrollment form.
2. Click the "Submit" button to send the data to the backend API.
3. If you need to clear the form, click the "Reset" button.

# API Integration

The form submits data to a backend API using a PUT request. Ensure that the API endpoint is correctly configured in the JavaScript code. The connection token, database name, and relation name should be updated as per your backend setup.

# Example API Request

The data is sent in JSON format, structured as follows:

json
{
    "Roll-No": "13",
    "Full-Name": "Mritunjai Pandey",
    "Class": "12",
    "Birth-Date": "2005-13-12",
    "Address": "Lucknow",
    "Enrollment-Date": "2025-04-02"
}
