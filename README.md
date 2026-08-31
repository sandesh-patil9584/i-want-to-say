# Beautiful Static Apology Website

A beautiful, simple, and fully mobile-responsive static website designed to express an apology. It has no headers or footers, no clicking buttons, and no audio. It displays the apology message and the emoji directly on the page in a clean card layout.

## Project Structure
- `index.html` - Contains the HTML markup with the top emoji, title, and customizable content area.
- `style.css` - Beautiful layout styling with a calming gradient background, card design, pulsing emoji animation, and full mobile responsiveness.
- `script.js` - Minimal Javascript placeholder.

## How to Customize
1. Open [index.html](file:///d:/sandesh/normalText/index.html).
2. Edit the text inside the `<p>` tags or add your own paragraphs/images inside the `.user-content` div.
3. If you want to change the emoji, edit the character inside `<div class="apology-emoji">`.

## How to Deploy to Netlify

### Option 1: Drag & Drop (Easiest)
1. Go to your folder at `d:/sandesh/normalText/`.
2. Select these three files: `index.html`, `style.css`, and `script.js`.
3. Zip them together into a single file (e.g., `sorry-site.zip`).
4. Log into [Netlify](https://www.netlify.com/).
5. Go to **Sites** -> **Add new site** -> **Deploy manually**.
6. Drag and drop your `.zip` file there. Netlify will deploy it instantly!

### Option 2: Deploy with Git / GitHub
1. Push this folder to a GitHub repository.
2. In Netlify, choose **Add new site** -> **Import an existing project** -> GitHub.
3. Keep the **Build Command** blank, and make sure **Publish directory** is set to `.` (root).
4. Click **Deploy site**.
