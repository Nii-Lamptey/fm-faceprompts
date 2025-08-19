# FM Face Prompt Generator (Static Site)

This is a one-file website that generates Football Manager face prompts in the browser using **PyScript** (Python in the browser).

## Deploy on GitHub Pages
1. Create a new repo (e.g., `fm-prompt-site`) and upload these files.
2. Commit `index.html` to the **main** branch.
3. In GitHub: **Settings → Pages → Build and deployment → Source: Deploy from a branch**.  
   Choose **Branch: main** and **/ (root)**. Click **Save**.
4. Your site will appear at: `https://<your-username>.github.io/<repo>/`

## Customize
- Open `index.html` and replace the placeholder dictionaries:
  - `country_codes`, `regions`, and any trait lists to match your Windows script.
- The “Copy” button uses the Clipboard API to copy the textarea contents.

## Notes
- Because this is a static site, your data dictionaries are visible in page source. 
  If you prefer to keep them private, consider a tiny Flask API and host on Railway/Render instead.

## Optional
- Point a custom domain via your repo’s **Settings → Pages → Custom domain**.
