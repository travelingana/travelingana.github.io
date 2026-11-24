# Starter site: setup guide

A small, fast, plain HTML site for your SEO/AEO practice project. No tools to install.

## 1. Fill in the placeholders

Open each file in any text editor and search for these three things:

- `YOUR-USERNAME`: your GitHub username (you create it in step 2)
- `YOUR NAME`: the name you want as author
- `REPLACE`: every spot where your own content goes

Files: `index.html`, `about.html`, `guides/sample-guide.html`, `sitemap.xml`, `robots.txt`.

## 2. Put it on GitHub Pages (free)

1. Create a free account at github.com.
2. Click **New repository**. Name it exactly `YOUR-USERNAME.github.io` (with your real username), set it to **Public**, and create it.
3. Click **Add file > Upload files**, drag in everything from this folder (including the `guides` folder), and click **Commit changes**.
4. Go to **Settings > Pages**. Under **Build and deployment**, choose **Deploy from a branch**, branch **main**, folder **/ (root)**, and save.
5. Wait a few minutes. Your site will be live at `https://YOUR-USERNAME.github.io`.

## 3. Connect Google Search Console and Analytics (do this on day one)

1. Go to search.google.com/search-console and add a **URL prefix** property with your site address.
2. Choose the **HTML tag** verification method, copy the meta tag, and paste it into the `<head>` of `index.html` where the comment says so. Upload the file again, then click Verify.
3. In Search Console, open **Sitemaps** and submit `sitemap.xml`.
4. Optional: create a Google Analytics (GA4) property and paste its snippet into the `<head>` of each page, so you can track visits and AI referral traffic.

## 4. Publish your guides

For each new guide:

1. Copy `guides/sample-guide.html`, rename it (for example `bangkok-to-chiang-mai.html`), and replace the content.
2. Add a link to it in `index.html`.
3. Add its address to `sitemap.xml`.
4. When you edit an existing guide later, update the "Last updated" date and the `dateModified` value.

## Writing checklist (for search and AI answers)

- Put the direct answer in the first two or three sentences.
- Use specific headings that say what the section answers.
- Include details only you know: prices, dates, mistakes, what you would do differently.
- Link to official sources for facts that change, and keep the dates visible.
- Keep the FAQ block only if the same questions and answers are visible on the page.
- You may use AI to fix grammar and clarity, but check that it never changes a fact or number.

## Experiments to run once you have a few pages

- Ask your guide's questions in ChatGPT, Perplexity, Gemini and Google, and note which sources get cited.
- Check Search Console weekly for impressions and queries.
- Write down what you changed and what happened. Those notes are your portfolio piece.
