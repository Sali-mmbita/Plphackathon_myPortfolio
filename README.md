Portfolio Website - README
 Overview
A responsive personal portfolio website built with pure HTML and CSS (no JavaScript) featuring:

Dark/Light mode toggle

Mobile-responsive design

Interactive elements without JavaScript

Complete portfolio sections (About, Skills, Projects, etc.)

 Features
 Pure CSS Dark Mode Toggle
 Mobile-First Responsive Design
 CSS-Only Interactive Elements
 Complete Portfolio Sections:

Hero section

About me

Skills showcase

Education timeline

Projects gallery

Interests

Contact form

 Technologies Used
HTML5 (Semantic markup)

CSS3 (Variables, Grid, Flexbox)

Font Awesome (Icons)

 Installation
No installation required! Simply:

Download the index.html file

Open it in any modern browser

 Customization
To customize colors, edit the CSS variables in the <style> section:

css
:root {
  --primary-color: #4361ee;
  --secondary-color: #3f37c9;
  --accent-color: #4cc9f0;
  /* Light mode colors */
  --text-color: #333;
  --bg-color: #f8f9fa;
  --card-bg: #ffffff;
}

#dark-mode-toggle:checked ~ * {
  /* Dark mode colors */
  --text-color: #f8f9fa;
  --bg-color: #121212;
  --card-bg: #1e1e1e;
}
 Responsive Breakpoints
Mobile: <768px

Tablet: 768px-992px

Desktop: >992px

 Key CSS Techniques
CSS Variables for theming

Checkbox Hack for interactive elements

CSS Grid for layouts

Flexbox for alignment

CSS Transitions for animations

 Notes
All interactivity achieved without JavaScript

Form submissions require backend integration

Images use placeholder URLs - replace with your own

 License
MIT License - Free for personal and commercial use
