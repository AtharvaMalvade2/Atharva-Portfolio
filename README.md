# Portfolio Website

## 🚀 About the Project
The **Portfolio Website** is a fully responsive and personal portfolio designed for professionals, students, and freelancers. Built with **HTML, CSS and JavaScript**, this project enables users to showcase their work, skills, and experiences dynamically.

## Table of Contents
- [Features](#features)
- [Tech Stack](#tech-stack)
- [Sections](#portfolio-sections)
- [Installtion Guide](#installation-guide)
- [Deployment](#deployment)
- [For the Future](#future-enhancements)
- [Author](#author)

## 🎯 Features
- 🖥️ **Responsive Design** - Works seamlessly on all devices.
- 📧 **Contact Form Integration** - Receive messages directly through the website.
- 📊 **Skills & Experience Showcase** - Display skills and work experience.
- 🌐 **Social Media Integration** - Link to GitHub, LinkedIn, and other platforms.

## 🏗️ Tech Stack
- **Frontend:** HTML, CSS, JavaScript   
- **Libraries Used:** FontAwesome  

## Portfolio Sections
✔️ About me\
✔️ Skills\
✔️ Education\
✔️ Projects\
✔️ Work Experience\
✔️ Contact me\
✔️ Linkedin Profile\
✔️ GitHub Profile

## 🛠️ Installation Guide
1. **Clone the Repository**  
   ```sh
   git clone https://github.com/yourusername/your-repo.git

Open http://localhost/your-project-folder/ in a browser.


## 🛫 Deployment
When you are done with the setup, you should host your website online.
We highly recommend to read through the [Deploying on GitHub Pages](https://create-react-app.dev/docs/deployment/#github-pages) docs for React.

#### Configuring GitHub Actions (Recommended)
First you should enable, GitHub Actions for the repository you use.

The Profile and the Repository information from GitHub is only created at the time of deploy and the site needs to be redeployed if those information needs to be updated. So, a configurable [CRON Job](https://docs.github.com/en/actions/reference/events-that-trigger-workflows#scheduled-events) is setup which deploys your site every week, so that once you update your profile on GitHub it is shown on your portfolio. You can also trigger it manually using `workflow_dispatch` event, see [this guide](https://github.blog/changelog/2020-07-06-github-actions-manual-triggers-with-workflow_dispatch) on how to do that.

- When you are done with the configuration, we highly recommend to read through the [GitHub Actions Configuring a workflow](https://docs.github.com/en/actions/configuring-and-managing-workflows/configuring-a-workflow) docs.

#### Deploying to GitHub Pages

This section guides you to deploy your portfolio on GitHub pages.

- Navigate to `package.json` and enter your domain name instead of `https://developerfolio.js.org/` in `homepage` variable. For example, if you want your site to be `https://<your-username>.github.io/developerFolio`, add the same to the homepage section of `package.json`.

- In short you can also add `/devloperFolio` to `package.json` as both are exactly same. Upon doing so, you tell `create-react-app` to add the path assets accordingly.

- Optionally, configure the domain. You can configure a custom domain with GitHub Pages by adding a `CNAME` file to the `public/` folder.

- Follow through the guide to setup GitHub pages from the official CRA docs [here](https://create-react-app.dev/docs/deployment/#github-pages).

## 🎯 Future Enhancements
🏆 Blog Section for content sharing.

🎨 Theme Customization for better UI/UX.

🌍 Multilingual Support for global users.

## 👨‍💻 Author
Atharva Malvade
🔗 Portfolio
📧 Email
📌 GitHub
