📁 Repository Structure

'''
html-css-comprehensive-assignment/
├── README.md
├── question1-innovatetech/
│   ├── index.html
│   ├── about.html
│   ├── contact.html
│   ├── css/
│   │   └── styles.css
│   └── images/
│       ├── favicon.ico
│       └── [other images]
├── question2-dashboard/
│   ├── dashboard.html
│   ├── css/
│   │   └── dashboard.css
│   └── images/
│       └── user-avatar.png
└── screenshots/
    ├── question1-desktop.png
    ├── question1-mobile.png
    ├── question2-desktop.png
    └── question2-mobile.png
'''
🧩 Question 1: InnovateTech Solutions Website
🎯 Objective

Create a complete, responsive tech company website demonstrating the use of semantic HTML, CSS Grid, Flexbox, and accessibility features.

📄 Pages

    index.html – Homepage (Hero, Services, About Preview, Footer)

    about.html – Company History, Team, and Core Values

    contact.html – Contact Information and Advanced Contact Form

💡 Key Features

    Semantic HTML5 structure (<header>, <nav>, <main>, <footer>, etc.)

    Responsive layout using CSS Grid & Flexbox

    Sticky header with smooth navigation

    Accessible and validated contact form

    Consistent branding with favicon, logo, and hero image

    Mobile-first approach with breakpoints at 768px and 1024px

🖥️ Question 2: Interactive Dashboard Application
🎯 Objective

Develop a responsive admin dashboard using advanced CSS layout techniques, including CSS Grid, Flexbox, and CSS variables.

📄 Main File

    dashboard.html

🧱 Layout Overview

The dashboard is divided into:

    1.Sidebar Navigation – Logo, navigation items, and user profile section

    2.Header Bar – Page title, search bar, notifications, and profile dropdown

    3.Main Content – Stats cards, data tables, and quick action form

💡 Key Features

CSS Grid for full dashboard structure:
'''
.dashboard-layout {
  display: grid;
  grid-template-areas:
    "sidebar header"
    "sidebar main";
  grid-template-columns: 280px 1fr;
}
'''
Flexbox for cards, navigation items, and form layouts

Sticky header and fixed sidebar

Interactive hover and focus effects (pure CSS, no JS)

Zebra-striped tables, badges for status, and responsive scrolling

Mobile-first design with breakpoints:

<768px: Sidebar hidden, stacked cards, scrollable tables

768–1024px: Two-column layout

>1024px: Full dashboard view

🧮 CSS Custom Properties
'''
:root {
  --primary-color: #3b82f6;
  --secondary-color: #64748b;
  --success-color: #10b981;
  --warning-color: #f59e0b;
  --danger-color: #ef4444;
}
'''
⚙️ Technical Highlights

Semantic, accessible HTML5 across all pages

Modern CSS3: Flexbox, Grid, Custom Properties, clamp(), and calc()

Responsive Design: Mobile-first, tablet-friendly, and adaptive scaling

Clean folder structure and modular CSS organization

Browser Compatibility: Tested on Chrome, Firefox, Edge, Safari

🚀 How to View the Projects

Clone this repository
'''
git clone https://github.com/<your-username>/html-css-comprehensive-assignment.git
'''

Open the desired project folder
''''
cd html-css-comprehensive-assignment/question1-innovatetech
'''

Launch the .html files directly in your browser
(double-click or drag into Chrome/Firefox)