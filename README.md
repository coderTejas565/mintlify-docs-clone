# Mintlify Documentation Website Clone

A static, desktop-first implementation of a documentation-style website inspired by the official Mintlify platform.  
This project was built as part of the **Web Dev Cohort 2026** to practice real-world frontend layout engineering using only core web technologies.

The primary objective was to accurately reproduce the **structural layout, visual hierarchy, and reading flow** of a modern SaaS documentation website without relying on JavaScript, CSS frameworks, or UI libraries.


## Live Deployment

Production build deployed on Vercel:  
🔗 https://mintlify-docs-clone.vercel.app/


## Problem Statement

Recreate a documentation website inspired by Mintlify with focus on:

- Desktop-first layout  
- Content structure and readability  
- Sidebar-based navigation system  
- Consistent spacing and typography  
- High-fidelity section organization  

While maintaining the following constraints:

- No JavaScript  
- No Tailwind or CSS frameworks  
- No animations or interactive effects  
- No responsive design (desktop only)  
- Pure HTML & CSS only  


## Solution Approach

The project was implemented by first reverse-engineering the layout of the reference website and identifying reusable layout patterns such as:

- Two-column hero layouts  
- Sidebar + main content grids  
- Card-based information blocks  
- Repeating feature sections  
- Multi-column footer system  

A global design system was defined upfront to maintain visual consistency across all sections.


## Implemented Sections

The following major sections were recreated:

1. Top Navigation Bar  
2. Hero Section  
3. Documentation Preview (Sidebar + Main Content)  
4. Trusted By / Logos  
5. Feature Highlights  
6. Intelligent Assistant UI Preview  
7. Enterprise Features  
8. Case Studies / Customer Stories  
9. Final Call-To-Action  
10. Footer  

Each section follows a consistent layout structure and spacing system.


## Tech Stack

- HTML5 (Semantic Markup)  
- CSS3  
  - Flexbox for one-dimensional layouts  
  - CSS Grid for complex two-column and card systems  
- Deployed using Vercel  

No external libraries or frameworks were used.


## Design System

### Typography
- Font Family: Inter (Google Fonts)

### Color Palette
- Background: `#0b0b0f`  
- Primary Accent: `#6366f1`  
- Primary Text: `#e5e7eb`  
- Muted Text: `#9ca3af`  

### Layout Rules
- Max content width: `1200px`  
- Center-aligned container system  
- Large vertical spacing for readability  
- Consistent section padding  


## Project Structure

mintlify-docs-clone/
│
├─ index.html
├─ style.css
├─ assets/
│ ├─ logos/ # Brand and company logos
│ ├─ ui/ # Product UI screenshots
│ ├─ illustrations/ # Hero and feature visuals
│ └─ icons/ # Small icons used in cards
├─ screenshots/
│ ├─ home.png
│ ├─ feature1.png
│ ├─ feature2.png
│ ├─ feature3.png
│ └─ footer.png
└─ README.md


Assets are grouped by **semantic purpose** rather than file type to ensure scalability and maintainability.


## Screenshots

### Homepage
![Homepage](screenshots/home.png)

### Feature Section 1
![Feature 1](screenshots/feature1.png)

### Feature Section 2
![Feature 2](screenshots/feature2.png)

### Feature Section 3
![Feature 3](screenshots/feature3.png)

### Footer
![Footer](screenshots/footer.png)


## Key Learnings

Through this project, the following practical skills were reinforced:

- Translating real-world UI designs into HTML structure  
- Building scalable layout systems using Flexbox and Grid  
- Managing assets and project structure professionally  
- Creating clean, readable documentation for frontend projects  
- Deploying static applications to production  


## Limitations

This project intentionally does not include:

- Interactivity or dynamic behavior  
- Responsive layouts  
- Accessibility optimizations  
- Animations or micro-interactions  

The focus was strictly on **layout engineering and structural accuracy**.


## Acknowledgements

This project is inspired by the design and layout patterns of the official Mintlify website.  
All content and assets are used for educational purposes only.

Built with focus on layout accuracy, not pixel perfection.