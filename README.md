# Personal Portfolio Website

A modern, responsive personal portfolio website built with HTML5, CSS3, JavaScript, and Bootstrap 5.

## Features
- **Modern Dark Theme**: Professional design with a black background and purple/blue accent colors.
- **Responsive Layout**: Works perfectly on mobile, tablet, and desktop devices using Bootstrap 5.
- **Animations**: Smooth scrolling, scroll-triggered fade/slide animations, and interactive hover effects.
- **Sections**: Navbar, Hero, About, Skills, Projects, Education, and Contact.
- **Contact Form**: Includes basic front-end validation (requires a backend service like Formspree to send emails).

## Technologies Used
- HTML5
- CSS3
- JavaScript (Vanilla)
- [Bootstrap 5](https://getbootstrap.com/) (via CDN)
- [Font Awesome](https://fontawesome.com/) (via CDN)
- [Google Fonts](https://fonts.google.com/) (Inter font)

## Project Structure
- `index.html`: The main HTML document containing the structure of the website.
- `style.css`: Custom CSS for styling, theming, and animations.
- `script.js`: Custom JavaScript for scroll spy, animations, mobile menu behavior, and form validation.
- `README.md`: Project documentation.

## How to Run / Preview

Since this project consists of static files, you do not need any complex build tools to run it. 

**Option 1: Direct File Opening**
Simply double-click the `index.html` file to open it in your default web browser.

**Option 2: Using VS Code Live Server**
1. Open the project folder in Visual Studio Code.
2. Install the "Live Server" extension.
3. Right-click on `index.html` and select "Open with Live Server".

**Option 3: Using Python Local Server**
If you have Python installed, open your terminal in the project directory and run:
```bash
python3 -m http.server 8000
```
Then navigate to `http://localhost:8000` in your web browser.

## Customization
- **Images**: Replace the placeholder image URLs (`https://via.placeholder.com/...`) in `index.html` with paths to your actual images.
- **Colors**: You can easily change the accent color by modifying the `--accent-color` variable in `style.css`.
- **Content**: Update the text in `index.html` to reflect your own skills, projects, and personal information.
