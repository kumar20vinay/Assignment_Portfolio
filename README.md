# Assignment_Portfolio

## Overview
This is a personal portfolio website for Vinay Kumar, a software engineer who specializes in MERN stack development and data structures. The website showcases his skills, services, projects, and provides a way for visitors to contact him.

## Features
* **Responsive Design**: Fully responsive layout that works on mobile, tablet, and desktop devices
* **Animated Sections**: Smooth scrolling and animations throughout the website
* **Dynamic Typing Effect**: Uses Typed.js to create a dynamic typing animation on the homepage
* **Project Carousel**: Uses Owl Carousel to showcase projects in a responsive slider
* **Contact Form**: Integrated with EmailJS for sending messages directly from the website
* **Navigation**: Smooth scrolling navigation with an accessible menu for mobile devices

## Technologies Used
* **HTML5**: Structure of the website
* **CSS3**: Styling and animations
* **JavaScript**: Interactive elements and form handling
* **jQuery**: DOM manipulation and event handling
* **Typed.js**: For the typing animation effect
* **Owl Carousel**: For the projects slider
* **Font Awesome**: For icons
* **EmailJS**: For the contact form functionality

## Sections
1. **Home**: Introduction with dynamic typing animation
2. **About**: Personal information and downloadable CV
3. **Services**: Overview of services offered (Web Design, Data Structures, Software Support)
4. **Skills**: Technical skills with progress bars
5. **Projects**: Carousel showcasing projects with links to GitHub repositories
6. **Contact**: Contact form and personal contact information

## Setup and Installation
1. Clone the repository
   ```bash
   git clone https://github.com/yourusername/Assignment_Portfolio.git
   ```

2. Navigate to the project directory
   ```bash
   cd Assignment_Portfolio
   ```

3. Open the `index.html` file in your browser or use a local development server

## EmailJS Configuration
The contact form uses EmailJS to send emails. To configure it for your use:
1. Sign up at EmailJS
2. Create a service and email template
3. Replace the service ID and template ID in the script with your own:
   ```javascript
   emailjs.send('YOUR_SERVICE_ID', 'YOUR_TEMPLATE_ID', contactParams)
   ```

## External Libraries
* jQuery 3.5.1
* Typed.js 2.0.11
* Waypoints 4.0.1
* Owl Carousel 2.3.4
* Font Awesome 5.15.3

## Customization
* Update the personal information in the HTML file
* Replace the project links and descriptions
* Change the images in the images folder
* Modify the color scheme in the CSS file
* Update the EmailJS configuration

## Browser Support
* Chrome (latest)
* Firefox (latest)
* Safari (latest)
* Edge (latest)
* Opera (latest)
