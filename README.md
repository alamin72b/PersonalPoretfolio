# AL AMIN's Portfolio


## Overview

This is a personal portfolio website for **AL AMIN BHUIYAN**, a Full Stack Developer.  
The site showcases my skills, experience, and contact information in a clean, responsive, and modern design.  

It's built as a **single-page application (SPA)** using pure **HTML and CSS**, emphasizing semantic structure, accessibility, and best practices for web development.

The project demonstrates fundamental web technologies while incorporating creative elements like **custom fonts, animations, and a professional layout**. It was developed to highlight my expertise in creating user-friendly interfaces without relying on JavaScript frameworks, focusing on performance and maintainability.

---

## Features

- **Responsive Design**: Adapts seamlessly to desktop, tablet, and mobile devices using CSS media queries.  
- **Semantic HTML**: Uses proper tags (`<header>`, `<main>`, `<section>`, `<footer>`) for better SEO and accessibility.  
- **Custom Styling**: Includes a unique font (`seenonim-v1`), CSS variables for theming, and subtle animations (fade-in effects on sections via CSS keyframes).  
- **Navigation**: Smooth anchor links to sections (Home, Skills, Contact) without JavaScript.  
- **Contact Form**: Functional form that opens the user's email client for sending messages (using `mailto:` protocol). Includes required fields, labels, and basic validation via HTML attributes.  
- **Hero Section**: Engaging introduction with buttons for **Hire Me** (links to Contact) and **Get CV** (downloads a PDF placeholder).  
- **Skills Showcase**: Categorized list of skills with hover effects for interactivity.  
- **Footer**: Includes quick links, services, social media icons (with ARIA labels for accessibility), and contact details.  
- **Accessibility Enhancements**: Alt text for images, focus outlines for interactive elements, and high-contrast colors.  

---

## Technologies Used

- **HTML5** – For structure and semantics.  
- **CSS3** – For styling, layouts (Flexbox), animations, and responsiveness.  
- **Custom Font** – Loaded via `@font-face` from the `fonts/` directory.  
- **No JavaScript** – Relies purely on HTML/CSS for all functionality and interactivity.  



## Installation and Setup

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/alamin72b/PersonalPortfolio.git


2. **Navigate to the Project Directory**:

   ```bash
   cd PersonalPortfolio
   ```

3. **File Structure**:

   ```
   PERSONALPORTFOLIO/
   ├── fonts/
   │   └── seenonim-v1.otf
   ├── statics/
   │   ├── css/
   │   │   └── style.css
   │   └── image/
   │       ├── home-right.png.webp
   │       └── Self_Logo.jpg
   ├── templates/
   │   └── base.html
   └── README.md
   ```

4. **Open the Site**:

   * Open `templates/base.html` in any modern browser (Chrome, Firefox, etc.).
   * No server or dependencies required—it's a **static site**.

5. **Optional: Deploy to GitHub Pages**:

   * Push to GitHub.
   * Go to repo **Settings > Pages > Source: `main` branch**.
   * Access at:

     ```
     https://alamin72b.github.io/PersonalPortfolio/templates/base.html
     ```

---

## Usage

* **Customization**:

  * Update personal details (name, email, address) in `base.html`.
  * Change colors/themes via CSS variables in `:root` of `style.css`.
  * Add your actual CV file path in the "Get CV" button (`href="statics/cv.pdf"`).
  * Replace placeholder images in `statics/image/` with your own.

* **Testing**:

  * Validate HTML: [W3C Validator](https://validator.w3.org/)
  * Check Responsiveness: Resize browser or use dev tools (F12 > Toggle device toolbar).
  * Accessibility: Run tools like **WAVE** or **Lighthouse**.

* **Browser Compatibility**:
  Tested on Chrome, Firefox


## Challenges and Improvements

* **Challenges**:
  Ensuring full responsiveness without JS while maintaining creative animations.
  Solved using CSS keyframes and transitions.

* **Future Improvements**:

  * Add a **Projects** section with CSS Grid.
  * Integrate **light/dark mode toggle** via CSS `prefers-color-scheme`.
  * Add basic **JavaScript form validation** if needed.

---

## Contact

* **Email**: [alamin72b@gmail.com](mailto:alamin72b@gmail.com)
* **Phone**: +880 1869674096
* **LinkedIn**: [linkedin.com/in/alamin72b](https://linkedin.com/in/alamin72b)
* **GitHub**: [github.com/alamin72b](https://github.com/alamin72b)

📩 Feel free to reach out for collaborations or feedback!

---

## License

This project is licensed under the **MIT License**.
See the [LICENSE](LICENSE) file for details.

---

© 2025 **AL AMIN BHUIYAN**. All rights reserved.




