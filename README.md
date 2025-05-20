# Personal Portfolio Website by GitHub Pages

This is a simple and engaging quiz application hosted on **GitHub Pages**. The app is designed to demonstrate the use of HTML, CSS and a PDF viewer while showcasing the process of deploying a static website using GitHub Pages.

## 🌐 Live Demo

[Checkout My Portfolio website](https://mani-6666.github.io/portfolio-website/)

---

## 📚 Project Overview

The **Portfolio Website** includes a homepage that introduces me, Veera Venkata Durga Manikanta Nandyala. It provides basic information like my profession, background, and links to my GitHub and Linkedin.

The portfolio includes:
- A greeting and introduction
- Links to my GitHub and LinkedIn profiles
- My full resume embedded directly in the site using MANI DevOps resume.pdf

---

## 📁 Folder Structure

```bash
portfolio-website/
├── index.html
├── style.css
├── MANI DevOps resume.pdf
└── README.md
```

---

## 🚀 How I Hosted This Project on GitHub Pages

The application was deployed as a static website using **GitHub Pages**. Here's how it was done:

### 1. **Prepare the Project**
   - The project folder contains:
     - `index.html`: Main webpage with greeting, links, and resume section.
     - `style.css`: Custom styling for layout and responsiveness.
     - `MANI DevOps resume.pdf`: Embedded directly in the site using <iframe>.

### 2. **Create a GitHub Repository**
   - A new repository was created on GitHub to host the project.
   - Added the project files and pushed using:
     ```bash
     git init
     git add .
     git commit -m "Initial commit - personal portfolio website"
     git branch -M main
     git remote add origin https://github.com/mani-6666/portfolio-website.git
     git push -u origin main
     ```

### 3. **Enable GitHub Pages**
   - We navigated to the repository’s **Settings** → **Pages** section.
   - Under the **Source** section, the branch was set to `main`, and the folder was set to `/root`.
   - GitHub provided a live link for public access.

### 4. **View Live Site**
   - Website is accessible at:
     ```
     https://mani-6666.github.io/portfolio-website/
     ```

### 5. **Update Anytime**
   - Any changes to the project are automatically reflected in the live site after committing and pushing updates to the `main` branch.

---

## 🛠️ Tools Used

- **GitHub Pages** for free tatic hosting.
- **HTML5** for structure.
- **CSS3** for styling and layout.

---

## 📝 How to Customize

1. **Edit Content:**
   - Modify `index.html` to update personal info or structure.
   - Edit `style.css` to adjust the design.

2. **Push to GitHub:**
   - Use:
     ```bash
     git add .
     git commit -m "Updated portfolio info"
     git push
     ```

---

Enjoy exploring and hosting with GitHub Pages! 🚀