# Personal Academic Portfolio

A responsive multi-page academic portfolio built with semantic HTML, external CSS, and vanilla JavaScript.

## Pages
- `index.html` — homepage and introduction
- `about.html` — education, aspirations, skills, hobbies, and embedded multimedia
- `projects.html` — three sample projects and an HTML table
- `planner.html` — interactive task planner
- `contact.html` — contact form with JavaScript validation

## Features
- Responsive navigation with a mobile menu
- CSS Grid/Flexbox, transitions, and consistent colour scheme
- Academic planner: add tasks, mark tasks complete, delete tasks, filter tasks, clear completed tasks, and persist tasks in localStorage
- Contact form: required-field checks, email validation, and digits-only phone validation
- Semantic elements, lists, images, links, table, and embedded video

## Run locally
Open `index.html` in a browser. For the best local development experience, use the Live Server extension in Visual Studio Code.

## Personalise before submission
1. Confirm your official education details and dates on `about.html`.
2. Replace the sample portrait with your own approved photograph if required.
3. Replace the sample projects with your own work when available.
4. Update the name and content where needed.

Images and the embedded video load from external services, so an internet connection is needed for those assets.

## Hosting and GitHub
1. Create a GitHub repository (for example, `academic-portfolio`).
2. Upload the contents of this folder to the repository root, keeping the `css` and `js` folders.
3. In GitHub, open **Settings → Pages**.
4. Under **Build and deployment**, select **Deploy from a branch**, choose `main` and `/(root)`, then save.
5. After GitHub Pages finishes publishing, copy the published website URL and submit it alongside the repository URL.

The contact form is a front-end validation demo only; it does not send messages to a server.
