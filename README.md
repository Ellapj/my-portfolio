# my-portfolio
Personal Portfolio Website
🔍 Overview
A responsive personal portfolio website built with HTML and CSS, designed to showcase projects, a downloadable CV, and a contact form. Optimized for desktop, tablet, and mobile devices.

🚀 Live Demo
Visit the website
(Replace with your actual Netlify URL)

🧰 Tech Stack
| Tool | Description | 
| HTML | Structuring the web content | 
| CSS | Styling and layout design | 
| GitHub | Version control & collaboration | 
| Netlify | Live hosting | 
| Chrome DevTools | Responsive testing | 



📱 Features & Improvements
- Responsive layout via media queries (1024px, 600px)
- Navigation wraps and centers on mobile
- Text and buttons resize for accessibility
- Profile image fixed to avoid cropping:
.profile-pic {
  width: 180px;
  height: 180px;
  border-radius: 50%;
  object-fit: contain;
  overflow: hidden;
}
- Mobile adjustment:
@media (max-width: 600px) {
  .profile-pic {
    width: 120px;
    height: 120px;
  }
}



🌐 Hosting Setup
To deploy the site to Netlify from GitHub:
- Push site folder to a public GitHub repository
- Log into Netlify and click Add New Site → Import from Git
- Choose your repo and deploy — Netlify builds and serves your site automatically!

📂 Folder Structure
my-portfolio/
├── index.html
├── style.css
├── images/
│   └── profile.jpg
└── README.md




