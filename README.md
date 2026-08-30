# Just Unorthodox Philosophy

A plain HTML/CSS/JS philosophy blog — no build step, no Jekyll, no local install.
GitHub Pages serves these files exactly as they are.

## GitHub Pages

1. Open **Settings → Pages**.
2. Under **Build and deployment**, choose **Deploy from a branch**.
3. Select branch **main** and folder **/ (root)**.
4. Click **Save**.
5. After GitHub publishes the site, open:
   `https://abhigaur834.github.io/philosophy-blog/`

## Adding a new post

1. Create a new HTML file inside `posts/`.
2. Add its title, date, URL, and excerpt to `posts.json`.
3. Commit the changes to `main`.

## Structure

- `index.html` — homepage
- `about.html` — about page
- `posts.json` — homepage post list
- `posts/` — individual essays
- `style.css` — shared styling
- `favicon.svg` — site icon
- `robots.txt` — crawler rules
- `sitemap.xml` — search-engine sitemap
