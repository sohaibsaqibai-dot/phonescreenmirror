# Website: Phone Screen Mirror to PC

The landing page, support page and privacy policy, ready for GitHub Pages. No build step: upload the files as they are.

| File | What it is |
| --- | --- |
| `index.html` | Landing page with features, how it works, FAQ and the Chrome Web Store button |
| `support.html` | Setup steps for each phone brand, fixes for common problems, contact |
| `privacy.html` | Privacy policy. Use its link in the Chrome Web Store's Privacy practices tab. |
| `404.html` | "Page not found" page |
| `llms.txt` | Plain-text summary for AI assistants (ChatGPT, Claude, Perplexity, Gemini) |
| `robots.txt` | Lets search engines and AI crawlers read the site |
| `sitemap.xml` | List of pages for Google and Bing |
| `.nojekyll` | Tells GitHub to serve the files as they are |
| `assets/` | Styles, font, icons, screenshots, share image |

Every Chrome Web Store button already points to item ID `ocddcpfmfpgallddfdcejebnanejibnb`.

## 1. Fill in your details (find and replace)

Open the folder in any editor that can replace text across files (for example VS Code: Ctrl+Shift+H). Replace:

| Find | Replace with | Example |
| --- | --- | --- |
| `YOUR-USERNAME` | your GitHub username | `sohaib-dev` |
| `YOUR-EMAIL@example.com` | your support email | `support@yourdomain.com` |

## 2. Publish on GitHub Pages

1. Sign in to GitHub and create a new **public** repository named exactly **`YOUR-USERNAME.github.io`** (your username, then `.github.io`). This puts the site at the root of your GitHub site, which robots.txt and llms.txt need to work.
2. Click **uploading an existing file** and drag in everything in this folder, including the `assets` folder and `.nojekyll`. Click **Commit changes**.
3. Open **Settings › Pages**. Under **Build and deployment**, choose **Deploy from a branch**, branch **main**, folder **/ (root)**, then **Save**.
4. After a minute or two the site is live at `https://YOUR-USERNAME.github.io/`.

Tip: `.nojekyll` starts with a dot, so Windows may hide it. If it doesn't upload, create a new empty file in the repository named `.nojekyll`.

## 3. After it's live

- Chrome Web Store dashboard: paste `https://YOUR-USERNAME.github.io/privacy.html` as the privacy policy link, and `https://YOUR-USERNAME.github.io/` as the homepage and support URLs.
- Google Search Console: add the site and submit `sitemap.xml`. Do the same in Bing Webmaster Tools, because several AI search tools draw on Bing's index.
- Check the structured data at https://search.google.com/test/rich-results.
- Use the same name, "Phone Screen Mirror to PC", everywhere (store, site, GitHub, social posts), so search engines and AI see one product.

## Using your own domain later

Add the domain under **Settings › Pages › Custom domain**, then replace `https://YOUR-USERNAME.github.io` with your domain in every file.
