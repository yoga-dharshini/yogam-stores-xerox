# Deploy Yogam Stores & Xerox on Vercel

This is a static HTML/CSS site and is ready for Vercel.

## Option A — Vercel CLI
1. Extract this folder.
2. Open a terminal in this folder.
3. Install the Vercel CLI if needed: `npm i -g vercel`
4. Run: `vercel`
5. Sign in when prompted and follow the prompts.
6. For the live production deployment, run: `vercel --prod`

## Option B — GitHub + Vercel
1. Create a GitHub repository.
2. Upload the contents of this folder to the repository root.
3. In Vercel, choose **Add New Project** and import the GitHub repository.
4. Use the repository root as the project root. No build command is required for this static site.
5. Deploy.

## Custom domain
After deployment, add your domain in Vercel Project → Settings → Domains. Update `sitemap.xml` with the final domain before submitting the site to Google Search Console.
