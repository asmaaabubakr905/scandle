بما أنكِ تريدين رفع هذا الملف كجزء من الـ Pull Request الخاص بكِ، فمن الأفضل أن يكون باللغة الإنجليزية لأنه المتعارف عليه في مشاريع GitHub، خاصة أنكِ أضفتِ تعديلات تقنية.

إليكِ الترجمة الاحترافية لملف الـ README.md:

Scandleted - Luxury Candle E-commerce Website
Project Overview
Scandleted is a static website dedicated to selling premium scented candles. The site showcases a diverse collection of natural candles made from eco-friendly materials.

Features
🕯️ Luxury Product Display: Elegant showcase of candle collections.

🎨 Modern Design: Attractive and sophisticated UI.

📱 Fully Responsive: Optimized for all screen sizes (Mobile, Tablet, Desktop).

🌿 Eco-Friendly Focus: Emphasis on natural and sustainable products.

🛒 Shopping Experience: Dedicated pages for browsing and shopping.

📝 Blog & Testimonials: Engaging content and customer social proof.

Technologies Used
HTML5 - Page structure.

CSS3 - Custom styling and layouts.

Bootstrap 5.3 - CSS Framework (RTL version).

Font Awesome 6.4.2 - High-quality iconography.

Google Fonts - Typography (Zilla Slab & La Belle Aurore).
 
 //edit buy rania


Project Structure
scandle/
├── index.html          # Home Page
├── about.html          # About Us Page
├── shop.html           # Store/Shop Page
├── blog.html           # Blog Page
├── testimonials.html   # Customer Reviews Page
├── images/             # Image Assets
├── bootstrap.rtl.min.css
└── README.md
How to Run the Project
Option 1: Open Locally
Navigate to the project folder.

Double-click index.html.

The site will open in your default web browser.

Option 2: Using a Local Server (Recommended)
Using Python
If Python is installed, run:

Bash

# Python 3
python -m http.server 8000
Then visit: http://localhost:8000

Using Node.js
If Node.js is installed:

Bash

# Install http-server (once)
npm install -g http-server

# Run the server
http-server -p 8000
Using VS Code Live Server (Easiest for Devs)
Open the project in VS Code.

Install the "Live Server" extension.

Right-click index.html and select "Open with Live Server".

Available Pages
Home (index.html) - Featured products and brand highlights.

About Us (about.html) - Information about the company and craftsmanship.

Shop (shop.html) - Full product catalog.

Blog (blog.html) - Articles and candle care tips.

Testimonials (testimonials.html) - Real customer feedback.

Troubleshooting & Contribution Tips (Breadcrumbs) 💡
If you are contributing to this project and encounter a 403 Forbidden error when trying to push your changes:

Fork the repository to your own GitHub account.

Clone your fork locally.

Push your changes to your fork.

Open a Pull Request from your fork to the main repository.

Requirements
A modern web browser (Chrome, Firefox, Safari, or Edge). An internet connection is required to load Bootstrap and Font Awesome via CDN.

Designed by: Asmaa