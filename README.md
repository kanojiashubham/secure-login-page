# secure-login-page
This project involves the creation of a secure login page using a combination of HTML, CSS, and JavaScript. The goal is to establish a reliable and protected entry point for users, safeguarding sensitive data and enhancing the overall security of your online platform,this code includes client-side validation and redirects the user to their organization's website on successful login.

## Features

- Clean and responsive design
- Basic client-side validation for the login form
- Secure password input handling
- Redirects users to another website on successful login

## Usage

- Download & Open the **secure-login-page.html** file in your preferred text editor.
- Enter the predefined username and password (or customize the credentials in the JavaScript code) to experience the login process.

# Customization
To customize the login credentials and redirection URL, modify the following part in : secure-login-page.html

-if (username === "**your_username**" && password === "**your_password**") {
    window.location.href = "**https://example.co**m";
} else {
    alert("Invalid username or password. Please try again.");
}
