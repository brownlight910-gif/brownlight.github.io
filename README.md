# Brown Light — Portfolio Website

Real Estate CRM & Automation Specialist. A fast, static website: no build step, no server needed.

## What is inside

| File / folder | What it is |
|---|---|
| `index.html` | The whole website (Home, About, Portfolio, Services and Contact pages). |
| `assets/` | All images: your photo, logos and portfolio screenshots. |
| `.nojekyll` | Tells GitHub Pages to serve the files exactly as they are. Keep it. |

The five pages live inside `index.html` and open with these links:
`#home`, `#about`, `#portfolio`, `#services`, `#contact`
(for example `https://YOUR-USERNAME.github.io/YOUR-REPO/#portfolio`).

## Host it on GitHub Pages (free)

1. Unzip this folder on your computer.
2. Go to https://github.com and sign in. Click **New repository**.
   - Name it `brown-light-website` (or `YOUR-USERNAME.github.io` if you want the address `https://YOUR-USERNAME.github.io`).
   - Choose **Public**, then click **Create repository**.
3. Click **uploading an existing file**. Drag in `index.html`, the whole `assets` folder and the `.nojekyll` file (open the unzipped folder and select everything inside it, not the folder itself). Click **Commit changes**.
   - If you cannot see `.nojekyll` on your computer, it is only hidden. The site still works without it.
4. Open the repository **Settings**, then **Pages**.
   - Under **Build and deployment**, set **Source** to **Deploy from a branch**.
   - Choose branch **main** and folder **/ (root)**, then click **Save**.
5. Wait 1 to 2 minutes and refresh. GitHub shows your live address at the top of the Pages screen.

## Use your own domain (optional)

In **Settings, Pages, Custom domain**, type your domain (for example `brownlight.com`) and follow the DNS steps GitHub shows.

## Change things later

- **Text:** open `index.html` in any text editor and search for the words you want to change.
- **Contact details:** search for `brownlight910@gmail.com` and `2348051843258` (WhatsApp number).
- **Links:** Upwork, Fiverr and LinkedIn links are plain `href="..."` values you can edit.
- **Images:** replace a file in `assets/` with a new one that has the same name.
- After any change, upload the changed file to the repository again (**Add file, Upload files**) and commit.

## Notes

- The contact form and the footer email box open the visitor's email app with the message filled in. There is no server behind them. If you want messages sent straight to your inbox, add a free form service such as Formspree.
- Fonts load from Google Fonts, so the first visit needs an internet connection.
