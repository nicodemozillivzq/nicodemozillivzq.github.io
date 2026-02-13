# 🌐 Portfolio -- Static Resume Website

Personal portfolio website built with **Jekyll + GitHub Pages**, based
on the Start Bootstrap Resume template.

This project was migrated from Flask to a fully static architecture to
enable automatic deployment with GitHub Pages --- no backend required.

------------------------------------------------------------------------

## 🚀 Live Site

👉 https://TU-USUARIO.github.io/TU-REPO/

------------------------------------------------------------------------

## 🧠 Architecture

This project uses:

-   **Jekyll (via GitHub Pages)**
-   **Liquid templating**
-   **Bootstrap**
-   **YAML configuration**

The site is dynamically generated from `_config.yml`.

There is no backend server, no Python, and no database.

------------------------------------------------------------------------

## 📂 Project Structure

. ├── \_config.yml ├── index.html ├── static/ │ ├── css/ │ ├── js/ │ ├──
img/ │ └── vendor/ └── README.md

------------------------------------------------------------------------

## ⚙️ How It Works

All content is defined inside:

\_config.yml

The HTML uses Liquid variables like:

{{ site.profile.first_name }} {{ site.experience }}

GitHub Pages automatically rebuilds the site whenever you push changes.

------------------------------------------------------------------------

## ✏️ Updating Content

To update the website:

1.  Edit `_config.yml`
2.  Commit changes
3.  Push to `main`
4.  GitHub Pages rebuilds automatically

No build step required.

------------------------------------------------------------------------

## 🛠 Deployment

This project is deployed using **GitHub Pages**:

1.  Go to Repository → Settings → Pages
2.  Select:
    -   Branch: `main`
    -   Folder: `/ (root)`
3.  Save

GitHub will automatically build the site using Jekyll.

------------------------------------------------------------------------

## 🎨 Customization

You can modify:

-   Colors → `static/css/resume.css`
-   Layout → `index.html`
-   Assets → `static/img/`

------------------------------------------------------------------------

## 📜 Credits

-   Based on the Start Bootstrap Resume template
-   Migrated to static Jekyll architecture for GitHub Pages

------------------------------------------------------------------------

## 👤 Author

**Nico Zilli**\
Odoo Solution Architect & Full Stack Developer
