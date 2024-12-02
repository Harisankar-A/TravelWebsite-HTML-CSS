# Login Page

This repository demonstrates the implementation of a simple login page with social media login options. The page includes an email and password login form along with social media login buttons (Google, Facebook, Apple) and a responsive layout.

## Features

### Email and Password Login
- Allows users to log in using their email and password.
- Provides a "Forgot your password?" link for easy recovery.
- Stylish input fields with focus effects.

### Social Media Login
- Includes buttons for Google, Facebook, and Apple logins.
- Uses Font Awesome icons for easy identification of social media platforms.

### Responsive Layout
- The page is responsive, with an image hiding on smaller screen sizes (less than 800px).
- The layout adapts well to various screen sizes, ensuring ease of use on both desktop and mobile devices.

## How It Works

### HTML Structure:
- A flexbox container `.con` centers the form and image on the page.
- The form contains two input fields for email and password and a login button.
- Social media login buttons are placed below the form for an alternate login option.

### CSS Styling:
- The form is designed with flexbox to center its content vertically and horizontally.
- Inputs are styled with focus effects, turning the border color to a light blue when selected.
- Social media buttons use Font Awesome icons and are styled to be uniform.

### JavaScript (Optional for Future Features):
- Placeholder for adding functionality like form validation or linking the login buttons to actual OAuth login services.

## Technologies Used

- **HTML**: Structure for the login form, inputs, and social media buttons.
- **CSS**: Custom styles for the form layout, input fields, buttons, and responsive design.
- **Font Awesome**: For the social media icons (Google, Facebook, Apple).
- **Responsive Design**: CSS media queries to ensure the layout adapts to mobile screens.

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/Harisankar-A-18/TravelWebsite-HTML-CSS
    ```

2. Navigate to the project directory


3. Ensure that all necessary assets (such as the `travel.jpg` image) are placed correctly.

4. Open the `index.html` file in any web browser to view the login page.

## Usage

- **Login**: Enter your email and password to log in.
- **Social Media Login**: Use the Google, Facebook, or Apple buttons to log in via your preferred social media account.
- **Responsive Design**: The layout will adjust on smaller screens, hiding the image and focusing on the login form.

## Screenshot

### Login Page (Desktop View)
![image](https://github.com/user-attachments/assets/e18b7c27-9f7e-4fdc-af7a-155cd623e995)


### Mobile View (Responsive Design)
![image](https://github.com/user-attachments/assets/e5a12cc8-cc8d-4fcd-9144-5b26c350980a)


## Limitations

- **Login Functionality**: The login functionality (form submission and social media authentication) is not implemented in this version.
- **Image Path**: Ensure that the `travel.jpg` image is available in the project directory or update the `src` attribute to a correct path.
- **Accessibility**: Further accessibility enhancements can be made for better user experience.

