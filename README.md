# UFID Prestige – Luxury Fragrance Landing Page

## Project Overview
A professional, responsive landing page built for a luxury perfume e-commerce brand as part of Week 1 of the BuildLabs Internship Programme. The design emphasizes elegance, high-end aesthetics, and clean typography tailored for executive consumers. It features a custom design system utilizing semantic HTML5 and modern CSS architecture.

## Features
* **Mobile-First Responsive Design:** Fluid layout that scales perfectly across mobile, tablet, and desktop viewports using `@media` queries.
* **Semantic HTML Architecture:** Clean DOM structure ensuring accessibility and proper layout grouping.
* **Modern CSS Layouts:** Strategic use of 1D Flexbox for navigation and a 2D CSS Grid (`repeat(3, 1fr)`) to showcase the fragrance notes.
* **Typography-Driven Aesthetic:** Custom Google Fonts integration featuring *Playfair Display* for executive headings and *Inter* for highly readable body copy.
* **Interactive Elements:** Smooth hover state transitions on navigation links and primary call-to-action buttons.

## Technologies Used
* HTML5
* CSS3 (Variables, Flexbox, Grid)
* Google Fonts
* Git & GitHub (Version Control)
* Vercel (Live Deployment)

## Developer Notes & Challenges
The primary technical challenge during this build was managing a layout collision within the CSS Grid, where the section heading was behaving as a grid item and breaking the layout. This was resolved by restructuring the HTML to separate the `<h2>` heading from a dedicated `.features-grid` wrapper `<div>`, successfully preserving semantic integrity while ensuring the grid only governed the product note cards. 

## Setup Instructions
1. Clone the repository:
   ```bash
   git clone [https://github.com/Ufidtech/your-repo-name.git](https://github.com/Ufidtech/ufid-luxury-perfumes)
Open the project folder in your code editor (e.g., VS Code).

Open index.html in your browser or run it using a live server extension.

Live Deployment
**[Live Link]** (https://ufid-luxury-perfumes.vercel.app/)
