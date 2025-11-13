# Kritan Nepal - Professional Portfolio Website

This is the repository for my personal portfolio website, designed to showcase my skills and projects as a Full Stack Developer with 2+ years of experience.

**Live Link:** [https://kritan19.github.io/Portfolio_website/](https://kritan19.github.io/Portfolio_website/) (Update this if your deployment URL changes)

---

## ✨ Overview

This portfolio is built with HTML, CSS, and vanilla JavaScript. It features:

-   A modern, responsive design.
-   Sections for Home (introduction), About Me, Skills, Projects, and Contact.
-   Dynamic project loading via a JavaScript array, making it easy to add and update project showcases.
-   Smooth scrolling and a mobile-friendly navigation menu.

---

## 🛠️ Tech Stack

-   **Frontend:** HTML5, CSS3 (Flexbox, Grid), Vanilla JavaScript (ES6+)
-   **Styling:** Custom CSS with a focus on modern design principles.
-   **Version Control:** Git & GitHub
-   **Deployment:** GitHub Pages

---

## 🚀 How to Add/Update Projects

Managing your projects is straightforward:

1.  **Open `index.html`:** Navigate to the `<script>` tag at the bottom of the file.
2.  **Find `projectsData` Array:** You'll see a JavaScript array named `projectsData`. Each object in this array represents a project card.
    ```javascript
    const projectsData = [
        {
            imgSrc: "path/to/your/project-image.jpg", // Replace with actual image path or placeholder
            title: "Your Project Title",
            description: "A compelling description of your project, highlighting technologies used and problems solved.",
            tags: ["React", "Node.js", "API", "MongoDB"], // Relevant technologies/keywords
            liveLink: "https://your-live-demo-link.com", // Optional: Link to live demo
            codeLink: "https://github.com/your-repo-link" // Optional: Link to code repository
        },
        // Add more project objects here
    ];
    ```
3.  **To Add a New Project:** Copy an existing project object, paste it as a new element in the array, and update its properties (`imgSrc`, `title`, `description`, `tags`, `liveLink`, `codeLink`).
    *   **`imgSrc`**: Path to your project's screenshot/image. You can use a service like `https://via.placeholder.com/400x225.png?text=Project+Name` for temporary placeholders.
    *   **`title`**: The title of your project.
    *   **`description`**: A brief summary of the project.
    *   **`tags`**: An array of strings representing technologies or keywords.
    *   **`liveLink`**: (Optional) URL to the live version of your project. If not applicable, you can omit this property or set it to `"#"` .
    *   **`codeLink`**: (Optional) URL to the project's source code. If not applicable, you can omit this property or set it to `"#"` .
4.  **Save `index.html`:** Your changes will be reflected on the website.

---

## 🎨 Customization

-   **Colors & Fonts:** Modify CSS variables in `styles.css` (at the top, within `:root`) to change the color scheme, fonts, etc.
-   **Content:** Update text directly in `index.html` for sections like "About Me", "Skills", and "Contact".
-   **Social Links:** Update your social media URLs in the "Hero Section" and optionally in the "Footer" of `index.html`. Ensure your social media icons (`640px-LinkedIn_logo_initials.png`, `download.png` for GitHub, `twitter.png`, etc.) are in the root directory or update their paths.

---

## 🔮 Future Enhancements (Ideas)

-   Integrate a Static Site Generator (e.g., Eleventy, Jekyll) for content management via Markdown files.
-   Implement a more advanced filtering system for projects.
-   Add a blog section.
-   Incorporate light/dark mode toggle.

---

Thank you for visiting!