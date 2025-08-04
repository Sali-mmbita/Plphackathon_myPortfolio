🌐 Personal Portfolio Website
A sleek, responsive personal portfolio built entirely with HTML and CSS — no JavaScript required!

Showcase your skills, projects, and personality with this modern portfolio that works beautifully across devices and supports dark/light themes.

✨ Features
🌙 Pure CSS Dark/Light Mode Toggle

📱 Mobile-First Responsive Design

🎯 Interactive Elements Without JavaScript

📂 Comprehensive Sections:

Hero Section

About Me

Skills Showcase

Education Timeline

Projects Gallery

Interests

Contact Form

🛠️ Technologies Used
HTML5 – Semantic markup for structure

CSS3 – Variables, Flexbox, Grid, Transitions

Font Awesome – Icon library for UI enhancements

🚀 Getting Started
No setup required! Just:

Download the index.html file

Open it in any modern web browser

Or you can access it live on https://sali-mmbita.github.io/Plphackathon_myPortfolio/

That’s it — you're live!

🎨 Customization
Easily update your site’s color theme by modifying the CSS variables in the <style> section:

css
Copy
Edit
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
  /* Dark mode overrides */
  --text-color: #f8f9fa;
  --bg-color: #121212;
  --card-bg: #1e1e1e;
}
Change colors, fonts, or layout styles to match your branding!

📱 Responsive Design
This portfolio is fully responsive using CSS media queries:

Mobile: <768px

Tablet: 768px–992px

Desktop: >992px

🧠 Key CSS Techniques
✅ CSS Variables for easy theming

✅ Checkbox Hack for toggles (like dark mode)

✅ Flexbox & Grid for layout control

✅ CSS Transitions for smooth effects

✅ Media Queries for responsiveness

⚠️ Notes
🔧 Form submissions require backend integration (e.g., Formspree, Netlify Forms)

🖼️ Replace placeholder images with your own for a personal touch

🧪 All features are built without any JavaScript

💡 Final Thoughts
This portfolio is a great starting point to showcase your work while keeping things simple and fast. Feel free to fork, customize, and make it your own!
