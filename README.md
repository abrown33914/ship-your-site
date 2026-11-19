# Ship Your Site

A simple portfolio template you can publish for free with GitHub Pages. No coding experience needed.

**You'll need:** a laptop and a GitHub account with a verified email.

---

## 1. Copy the template

1. Click **Use this template** → **Create a new repository**.
2. Name it **`your-username.github.io`** (use your actual GitHub username).
3. Keep it **Public** → **Create repository**.

## 2. Publish it
 
Because your repo is named `your-username.github.io`, GitHub usually publishes it for you automatically.
 
1. Wait about a minute, then visit **`https://your-username.github.io`**.
2. **Not showing up?** Go to **Settings** → **Pages**. Under **Branch**, select **main** and **/ (root)**, then click **Save**. Wait a minute and try again.
You're live! Every time you commit a change from now on, your site updates automatically (it can take a minute or two).
 
## 3. Make it yours

Every spot you need to change in `index.html` is marked with an **`EDIT`** comment. To change colors, edit the values at the top of `style.css`.
 
### Option A: Edit on GitHub (easiest)
 
1. Open **`index.html`** and click the **pencil icon**.
2. Replace the placeholder text.
3. Click **Commit changes**.
### Option B: Edit in VS Code
 
1. Install [VS Code](https://code.visualstudio.com).
2. Open VS Code → **Clone Repository** → sign in with GitHub → pick your `your-username.github.io` repo.
3. Make your edits.
4. Save your changes to GitHub. Open the terminal (**Terminal** → **New Terminal**) and run:
```bash
git add .
git commit -m "Add my info"
git push
```
   Your site updates in a minute or two. Every time you make more changes, run those three commands again.
 
### Adding your photo
 
1. Click **Add file** → **Upload files** in your repo and upload your photo.
2. In `index.html`, follow the `EDIT` comment next to the "Your photo" box.
Use a **.jpg** or **.png**. iPhone `.HEIC` photos won't show up in browsers.
 
---
## Level up

### Customize with AI

Use ChatGPT, Claude, or GitHub Copilot Chat in VS Code to restyle or extend your site. Some ideas:

- **Pick a theme:** "Restyle my site like a retro arcade game" or "Make it feel like a minimal magazine layout."
- **Copy a vibe:** find a portfolio or website design you love, screenshot it, and ask: "Recreate this design using my content."
- **Add a feature:** a dark mode toggle, scroll animations, a photo gallery, a projects filter.

Always read through the changes before you commit, so you know what's on your site.

> Copilot Free works for everyone with a GitHub account.

### See who visits (analytics)

[Umami](https://umami.is) is free, privacy-friendly analytics.

1. Sign up at [cloud.umami.is](https://cloud.umami.is) and add your site.
2. Copy the tracking script. It looks like this:
   ```html
   <script defer src="https://cloud.umami.is/script.js" data-website-id="your-website-id"></script>
   ```
3. Paste it into `index.html` where it says **`OPTIONAL: Analytics`**, then commit.

---

## Keep going

**Templates + inspiration**
- [HTML5 UP](https://html5up.net): free site templates
- [One Page Love](https://onepagelove.com): one-page site inspiration
- [Dribbble](https://dribbble.com/search/portfolio): design ideas

**Design basics**
- [Laws of UX](https://lawsofux.com): design principles, explained simply
- [Coolors](https://coolors.co): color palette generator
- [Google Fonts](https://fonts.google.com): free fonts

**Learn to code it**
- [MDN Web Docs](https://developer.mozilla.org/en-US/docs/Learn_web_development): HTML and CSS from the ground up
- [web.dev Learn](https://web.dev/learn): CSS, design, and accessibility courses
- [freeCodeCamp](https://www.freecodecamp.org/learn): free interactive lessons
- [GitHub Pages docs](https://docs.github.com/en/pages): custom domains and more

---

## Tips

- **Changes not showing?** Wait a minute, then hard refresh (Ctrl+Shift+R, or Cmd+Shift+R on Mac).
- **Made a mistake?** Every commit is saved. Open the file and click **History** to see earlier versions.
- **Want a custom domain** like `yourname.com`? See the GitHub Pages docs above.

---

Made by [INIT FGCU](https://getinvolved.fgcu.edu/organization/init) · Become a member at [weareinit.org](https://www.weareinit.org)



Workshop Slides: [click here](https://docs.google.com/presentation/d/1DYaOgWDT0qrsFNSXDweN3R8rctjyNMpj50bNduZlONQ/edit?usp=sharing)
