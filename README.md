# Joseph Yi - Personal Website

A modern, responsive personal website showcasing my work, skills, and experience as a Computer Science student at the University of Michigan.

## Features

- **Responsive Design**: Works perfectly on desktop, tablet, and mobile devices
- **Dark/Light Mode**: Toggle between dark and light themes with smooth transitions
- **Modern UI/UX**: Clean, professional design with smooth animations and hover effects
- **Interactive Elements**: Smooth scrolling navigation, form validation, and theme switching
- **SEO Optimized**: Semantic HTML structure and meta tags
- **Fast Loading**: Optimized CSS and JavaScript for quick page loads
- **Accessible**: Built with accessibility best practices

## File Structure

```
personal_website/
├── index.html          # Main HTML file
├── styles.css          # CSS styles with dark mode support
├── script.js           # JavaScript functionality and theme toggle
├── selfie.jpg          # Profile image
├── .gitignore          # Git ignore file
└── README.md           # This file
```

## Sections Included

1. **Hero Section**: Introduction with profile image and call-to-action buttons
2. **About Section**: Personal information, academic stats, and relevant courses
3. **Skills Section**: Technical skills organized by category (Programming, Frontend, Backend, Tools)
4. **Projects Section**: Featured projects with descriptions and technologies used
5. **Contact Section**: Contact form and social media links
6. **Navigation**: Fixed navigation bar with smooth scrolling and theme toggle

## About Me

I'm a Computer Science student at the University of Michigan (Class of 2026) focused on systems, web platforms, and scalable, user-friendly tools. I enjoy taking projects from idea to deployment—whether that's implementing a user-level thread library in C++ or shipping full-stack apps for real users.

**Academic Stats:**
- GPA: 3.7
- Degree: BS in Computer Science (2026)
- Major Projects: 4
- Languages: English / Korean

**Relevant Courses:**
- Data Structures & Algorithms
- Intro to Operating Systems
- Web Systems
- Intro to Computer Security
- Building Data-Driven Web Apps

## Skills & Technologies

### Programming Languages
- C/C++
- Python
- C#
- Java
- R
- SQL

### Frontend Development
- HTML
- CSS
- JavaScript
- React
- Tailwind CSS
- WordPress

### Backend Development
- Flask
- Django
- PHP
- REST APIs
- Firebase

### Tools
- Git
- Docker
- VS Code
- Linux
- Visual Studio
- Eclipse

## Featured Projects

### Multi-Processor Thread Library
A user-level thread library in C++ supporting context switching, mutexes, condition variables, FIFO scheduling for ready/mutex/cond queues, and timer/IPI-driven preemption across cores.

**Technologies:** C++, ucontext, Concurrency

### Secure Partner Portal for U-M Nursing
Private server-side application used by 10+ partners to share files, preview/download securely, and contribute data for COSSUP. Includes a custom Google Maps interface for naloxone distributors.

**Technologies:** Python, Flask/Django, Google Maps
**Live Demo:** [umsn-cossup.com](https://umsn-cossup.com/)

### Simplified Relational DB Emulator
CLI database emulator supporting CREATE/INSERT/DELETE/PRINT/JOIN with custom data structures (hash tables, BSTs) for indexing and multi-table joins across typed columns.

**Technologies:** C++, Data Structures, Parsing

### Local Church Website (Frontend)
Helped ship a React-based site and crafted a responsive 404 page using Tailwind CSS, HTML, React, and Docker—contributing to a ~25% increase in average userbase.

**Technologies:** React, Tailwind CSS, Docker
**Live Demo:** [annarbor.hmcc.net](https://annarbor.hmcc.net/)

## Contact Information

- **Email:** yijo@umich.edu
- **Location:** Ann Arbor, United States
- **GitHub:** [github.com/yijo2004](https://github.com/yijo2004)
- **LinkedIn:** [linkedin.com/in/yijo](https://www.linkedin.com/in/yijo/)
- **Instagram:** [instagram.com/josephyiii](https://www.instagram.com/josephyiii/)

## Technical Details

### Dark Mode Implementation
The website features a fully functional dark mode toggle that:
- Persists user preference in localStorage
- Updates navbar styling immediately on theme change
- Maintains consistent color scheme across all sections
- Uses CSS custom properties for easy theme management

### Responsive Design
The website uses CSS Grid and Flexbox for responsive layouts with breakpoints:
- **Desktop**: 1200px and above
- **Tablet**: 768px - 1199px
- **Mobile**: 767px and below

### Form Handling
The contact form includes:
- Client-side validation
- EmailJS integration for sending emails
- Responsive design for all screen sizes

## Deployment

This website can be deployed to various platforms:

### GitHub Pages
1. Push code to a GitHub repository
2. Go to repository Settings > Pages
3. Select source branch and save
4. Site available at `https://yourusername.github.io/repository-name`

### Netlify
1. Drag and drop project folder to Netlify
2. Site deploys automatically
3. Connect to GitHub for automatic deployments

### Vercel
1. Install Vercel CLI: `npm i -g vercel`
2. Run `vercel` in project directory
3. Follow prompts to deploy

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## License

This project is open source and available under the MIT License.

## Contact

If you have any questions or would like to collaborate, feel free to reach out through the contact form on the website or via email at yijo@umich.edu.