# Arlo Email Signature

Generate and copy Arlo email signatures for Gmail (and other clients). Three styles with optional phone, email, and links.

## Publish to GitHub and host images

1. **Create a new repository on GitHub**
   - Go to [github.com/new](https://github.com/new)
   - Name it e.g. `arlo-email-signature`
   - Leave "Add a README" unchecked (this project already has one)
   - Create the repository

2. **Push this project**
   ```bash
   cd /path/to/arlo-email-signature-main
   git init
   git add .
   git commit -m "Initial commit: Arlo email signature generator"
   git branch -M main
   git remote add origin https://github.com/YOUR_USERNAME/arlo-email-signature.git
   git push -u origin main
   ```
   Replace `YOUR_USERNAME` and `arlo-email-signature` with your GitHub username and repo name.

3. **Enable GitHub Pages (so the page and images are public)**
   - In the repo: **Settings → Pages**
   - Under "Build and deployment", **Source** choose **Deploy from a branch**
   - **Branch** choose `main`, folder **/ (root)**, then Save
   - Your site will be at `https://YOUR_USERNAME.github.io/arlo-email-signature/` (replace with your username and repo name)

4. **Use the Image base URL when copying**
   - Open the generator at the URL above
   - In the form, set **Image base URL** to your Pages URL, e.g.  
     `https://YOUR_USERNAME.github.io/arlo-email-signature`
   - Copy a signature; pasted emails will load logos and icons from that URL.

## Local use

Open `index.html` in a browser. Fill in the form and use "Copy signature" for the style you want. Paste into Gmail (Settings → Signatures). For images to show in sent email, either host the page (e.g. GitHub Pages) and set the Image base URL, or use image URLs that are already publicly hosted.
