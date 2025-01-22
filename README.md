
<h1 align=center>Geeky Hugo</h1> 
<p align=center>Get Geeked out by Geeky, a personal Hugo blog theme that is fully responsive and super-fast.</p>
<h2 align="center"><a target="_blank" href="https://demo.statichunt.com/geeky-hugo/" rel="nofollow">Demo</a> | <a  target="_blank" href="https://pagespeed.web.dev/report?url=https%3A%2F%2Fdemo.statichunt.com%2Fgeeky-hugo%2F&form_factor=desktop">Page Speed (85%)</a> </h2>


<p align=center>
  <a href="https://github.com/gohugoio/hugo/releases/tag/v0.87" alt="Contributors">
    <img src="https://img.shields.io/static/v1?label=min-HUGO-version&message=0.87&color=f00&logo=hugo" />
  </a>

  <a href="https://github.com/statichunt/geeky-hugo/blob/master/LICENSE">
    <img src="https://img.shields.io/github/license/statichunt/geeky-hugo" alt="license"></a>

  <img src="https://img.shields.io/github/languages/code-size/statichunt/geeky-hugo" alt="code size">

  <a href="https://github.com/statichunt/geeky-hugo/graphs/contributors">
    <img src="https://img.shields.io/github/contributors/statichunt/geeky-hugo" alt="contributors"></a>

  <a href="https://twitter.com/intent/follow?screen_name=heyStatichunt">
    <img src="https://img.shields.io/twitter/follow/heyStatichunt?style=social&logo=twitter"
      alt="follow on Twitter"></a>
</p>

---

<p align="center">
 
![geeky-hugo-startup-theme](https://user-images.githubusercontent.com/17677384/140605658-0c68cf6c-d15a-4f0d-8e66-1060ce636d20.png)
</p>

---
## Key Features
- Hugo module support
- Google analytics, AdSense support
- Image optimize  with hugo pipe
- CSS and JS bundle with hugo pipe
- Netlify settings predefine
- Forestry cms pre-configured
- Google font loads from webfont loader
- Caching enable
- Color and fonts variable in config file
- Contact form Support
- Search by fuse.js
- Mailchimp integrate
- GDPR consent enable
- Google page speed optimized
- Open graph meta tag
- Twitter card meta tag


## Local development

```bash
# clone the repository
git clone git@github.com:statichunt/geeky-hugo.git

# cd in the project directory
$ cd geeky-hugo/exampleSite/

# Start local dev server
$ hugo server --themesDir ../..
```

## Deployment and hosting

## Netlify 

[![Deploy to Netlify](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy?repository=https://github.com/statichunt/geeky-hugo)

Follow these steps.


## Render

![Deploy to Render](https://www.render.com)

To deploy your Hugo site on Render, follow these steps:

1. **Create a New Static Site** on Render's dashboard.
2. **Link the Git Repository** that contains your Hugo site.
3. Navigate to **Settings > Build & Deploy**.

Configure the build settings as follows:

- **Build Command**:

```bash
mkdir geeky-hugo; mv * geeky-hugo/.; hugo -s geeky-hugo/exampleSite --minify --gc --themesDir ../..
```

- **Publish Directory**:

```bash
geeky-hugo/exampleSite/public
```

<!-- reporting issue -->
## Reporting Issues
We use GitHub Issues as the official bug tracker for the geeky Template. Please Search [existing
issues](https://github.com/statichunt/geeky-hugo/issues). Someone may have already reported the same problem.
If your problem or idea has not been addressed yet, feel free to [open a new
issue](https://github.com/statichunt/geeky-hugo/issues).

<!-- ## geeky hugo theme Powered Websites

View all the websites powered by geeky hugo theme [here](https://github.com/statichunt/geeky-hugo/wiki/All-Geeky-Hugo-Powered-Websites). Want to submit your own website powered by geeky hugo theme? You can submit it [here](https://github.com/statichunt/geeky-hugo/discussions/2). -->

<!-- licence -->
## License
Copyright &copy; Designed and developed by [Statichunt](https://statichunt.com)

**Code License:** Released under the [MIT](https://github.com/statichunt/geeky-hugo/blob/master/LICENSE) license.

**Image license:** The images are only for demonstration purposes. They have their licenses. We don't have permission to
share those images.

<!-- resources -->
## Special Thanks
- [Bootstrap](https://getbootstrap.com)
- [Jquery](https://jquery.com)
- [Font Awesome Icons](https://fontawesome.com)
- [Fuse Js](https://fusejs.io)
- [Google Fonts](https://fonts.google.com/)
- [All Contributors](https://github.com/statichunt/geeky-hugo/graphs/contributors)














---
---
---
---


# Deploying and Developing the Geeky Hugo Theme

## Overview
This guide walks you through the process of deploying the Geeky Hugo theme to Netlify and Render, performing local development, and hosting it on a GitHub Pages domain. 

---

## Step 1: Deploy on Netlify

1. **Visit the GitHub Repository**
   Navigate to the [Geeky Hugo GitHub Repository](https://github.com/statichunt/geeky-hugo).

2. **Deploy to Netlify**
   - In the repository’s `README`, click on the **Deploy to Netlify** button:
     ![Deploy to Netlify](https://www.netlify.com/img/deploy/button.svg)
   - Follow the prompts to authenticate your Netlify account and set up the deployment.
   - Create a new repository named `geeky-hugo` by default (you can rename it later).

3. **Automatic Repo Creation**
   - Netlify will automatically create a repository in your GitHub account for the theme.

---

## Step 2: Deploy on Render

1. **Create a Render Account**
   - Go to [Render](https://www.render.com) and create an account if you don’t already have one.

2. **Set Up a Static Site**
   - On the dashboard, click **Create a New Static Site**.

3. **Link the GitHub Repository**
   - Give Render access to your GitHub repositories.
   - Select the `geeky-hugo` repository.

4. **Configure Build Settings**
   - Navigate to **Settings > Build & Deploy**.
   - Use the following configuration:
     - **Build Command**:
       ```bash
       mkdir geeky-hugo; mv * geeky-hugo/.; hugo -s geeky-hugo/exampleSite --minify --gc --themesDir ../..
       ```
     - **Publish Directory**:
       ```bash
       geeky-hugo/exampleSite/public
       ```

5. **Deploy**
   - Deploy the site and verify that it’s live.
   - You can customize the site URL (e.g., `<somename>.render.com`).

---

## Step 3: Local Development

1. **Clone the Repository**
   - Clone the `geeky-hugo` repository created on Netlify:
     ```bash
     git clone git@github.com:<your-username>/geeky-hugo.git
     ```

2. **Navigate to the Example Site**
   - Change to the example site directory:
     ```bash
     cd geeky-hugo/exampleSite/
     ```

3. **Start the Local Development Server**
   - Run the following command to start the Hugo server:
     ```bash
     hugo server --themesDir ../..
     ```
   - The site will be available at `http://localhost:1313`.

4. **Make Changes and Push Updates**
   - Edit files locally and commit changes:
     ```bash
     git add .
     git commit -m "Update site content"
     git push origin main
     ```
   - Since Render is linked to the repository, changes will automatically deploy.

---

## Step 4: Host on GitHub Pages

1. **Set Up Repository for GitHub Pages**
   - If you want to host the site under your GitHub Pages domain (e.g., `username.github.io/blog`), create a new repository named `blog`.

2. **Change Folder Structure**
   - Ensure your project folder structure is as follows:
     ```
     Downloads
     |-- newblog (folder)
         |-- geeky-hugo
     ```

3. **Generate the Static Files**
   - Run the Hugo build command to generate the static site:
     ```bash
     hugo -s geeky-hugo/exampleSite --minify --gc --themesDir ../..
     ```
   - Change to the `public` directory:
     ```bash
     cd geeky-hugo/exampleSite/public
     ```

4. **Initialize Git and Push to GitHub**
   - Initialize a new Git repository and push to your GitHub Pages repository:
     ```bash
     git init
     git remote add origin https://github.com/<your-username>/blog.git
     git branch -M main

     git add .
     git commit -m "Initial commit - Deploy Hugo blog"
     git push -u origin main
     ```

5. **Update Configuration**
   - Edit the `baseURL` in the `config.toml` file to reflect your GitHub Pages domain (e.g., `https://username.github.io/blog/`).
   - Adjust image paths to start with `/` for compatibility.

---

## Additional Steps for Local Deployment and Git Management

1. **Navigate to Project Directory**
   ```bash
   cd ..\..\..\..\newblog/
   ```

2. **Build the Site Locally**
   ```bash
   hugo -s geeky-hugo/blog --minify --gc --themesDir ../..
   ```

3. **Navigate to Public Directory**
   ```bash
   cd geeky-hugo/blog/public
   ```

4. **Commit and Push Changes**
   ```bash
   git add .
   git status
   git commit -m "message"
   git push -u origin main
   ```

---

## Notes

- Always test changes locally before pushing to ensure everything works as expected.
- Render and Netlify offer robust free tiers suitable for most personal projects.
- GitHub Pages requires careful folder structuring and configuration for smooth hosting.

By following this guide, you can easily deploy, develop, and host your Geeky Hugo theme with minimal setup.
