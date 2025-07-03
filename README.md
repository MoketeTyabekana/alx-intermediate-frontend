# alx-intermediate-frontend

## Project Description

This project is a hands-on exploration of **Tailwind CSS**, focusing on building responsive and aesthetically pleasing web layouts. Each task is designed to introduce advanced Tailwind concepts, enabling you to effectively utilize utility-first CSS for modern web development. You will create layouts ranging from basic CSS grids and flexbox navigation bars to complex multi-section layouts that combine both CSS Grid and Flexbox. This progressive approach ensures a deep understanding of responsive design principles while mastering Tailwind CSS.

## About the Semantic HTML Project

This project is also designed to help you build a solid foundation in **Semantic HTML** while emphasizing **accessibility**, **SEO optimization**, and the implementation of **ARIA roles** for enhanced usability. Through a series of incremental tasks, you will structure and enhance a web page to make it visually organized, optimized for search engines, and accessible to all users, including those using screen readers. By the end of this project, you will understand the importance of semantic elements and accessibility features in modern web development.

## Learning Objectives

### Tailwind CSS

- **Master Tailwind CSS Configuration:** Learn how to install and configure Tailwind CSS, enabling seamless integration into projects.
- **Build Responsive Layouts:** Implement complex, responsive layouts using Tailwind’s utility classes and responsive modifiers.
- **Combine CSS Grid and Flexbox:** Develop advanced page structures by leveraging both grid and flexbox techniques.
- **Design Aesthetically Pleasing Components:** Use Tailwind’s extensive styling utilities to create visually appealing designs with gradients, spacing, and colors.
- **Optimize for Professional Development:** Enhance professional web development skills by adhering to best practices in structuring, coding, and managing CSS frameworks.

### Semantic HTML & Accessibility

- **Master Semantic HTML:** Structure web pages using semantic elements such as `<header>`, `<main>`, `<article>`, `<section>`, and `<footer>` for better content organization and accessibility.
- **Optimize for SEO:** Improve the visibility of your webpage through appropriate usage of meta tags and proper document structure.
- **Enhance Accessibility:** Implement ARIA roles and attributes to make web forms and content more accessible to users with disabilities.
- **Understand Form Design Best Practices:** Create accessible and user-friendly forms using modern HTML techniques.
- **Adopt Incremental Development:** Practice progressive enhancement by building upon the foundation of each previous task.

## Requirements

- Node.js installed on the local machine. [Download Node.js](https://nodejs.org/)
- Basic knowledge of HTML, CSS, and JavaScript.
- Familiarity with a code editor (e.g., VSCode) and browser developer tools.
- GitHub account for repository management.
- Tailwind CSS installed via npm or CDN.
- Modern browser to render and test the designs.
- Internet connection for accessing Tailwind’s documentation and CDN links.
- A working understanding of HTML5.
- Familiarity with semantic HTML elements and their purpose.
- Basic knowledge of SEO and its importance in web development.
- Awareness of web accessibility standards, including ARIA roles and attributes.

---

## Projects

### 1. Flexbox Basics - Build a Simple Navigation Bar

**Objective:** Use Tailwind and Flexbox to create a horizontal navigation bar that adjusts to different screen sizes.

- **File:** `0x02-tailwind-css/3-nav_index.html`
- **Instructions:**
  - Build a simple horizontal navigation bar using Tailwind and Flexbox.
  - Create a file named `3-nav_index.html` and add the provided HTML structure.
  - After the header, add a `<nav>` tag with four `<a>` tags: Home, About, Services, Contact.
  - Use:  
    - `class="flex space-x-5 justify-center bg-gray-300 text-white p-4"` on `<nav>`
    - `class="px-2 text-xl hover:bg-gray-500 p-2 rounded-lg"` on each `<a>`
  - The navigation bar should be responsive and stack vertically on small screens.

---

### 2. Create a Responsive Flexbox Layout with Tailwind

**Objective:** Build a responsive page layout with Tailwind’s utility classes, using the Tailwind CDN.

- **File:** `0x02-tailwind-css/4-flexbox_index.html`
- **Instructions:**
  - Create a new file `4-flexbox_index.html` and add the provided HTML structure.
  - Add `flex` class to the `<main>` tag.
  - The `<aside>` should have: `class="w-1/3 bg-gray-300 p-4"`
  - The `<section>` should have: `class="w-2/3 bg-gray-500 p-4"`
  - The layout should be responsive and stack vertically on small screens.

---

### 3. Combine CSS Grid and Flexbox for a Multi-Section Layout

**Objective:** Combine both grid and flexbox to create a responsive layout.

- **File:** `0x02-tailwind-css/5-gridflex_index.html`
- **Instructions:**
  - Create a file `5-gridflex_index.html` and add the provided HTML structure.
  - In `<main>`, use: `class="grid grid-cols-1 lg:grid-cols-3 gap-4 mt-4 min-h-screen"`
  - In `<section>`, use: `class="lg:col-span-2 flex"`
  - Each `<div>` in the section should have padding, a red background gradient, and occupy half the width.

---

### 4. Build a Responsive Image Gallery Using CSS Grid

**Objective:** Expand on the previous layout by adding a responsive image gallery using CSS grid.

- **File:** `0x02-tailwind-css/6-imageGallery.html`
- **Instructions:**
  - Use the layout from the previous task.
  - Add a section for an image gallery below the existing content.
  - Use CSS Grid to arrange images in a 3-column layout, adjusting to 1 column on small screens.
  - Ensure images are responsive.

---

### 5. Manual Review

- **Repo:** `alx-intermediate-frontend`
- **Directory:** `0x02-tailwind-css`

