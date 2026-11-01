# The Fine Print (Vercel version)

One static page (`index.html`). No server, no API key, no cost.
Plain Print runs as a demo: "Try an example" shows a full explanation of the sample lease.
For people who want to paste their own documents, the app links to the live version on Claude.

## Put it online (no terminal)

1. Go to github.com and create a new repository (for example `the-fine-print`).
2. Click "uploading an existing file", drag in `index.html`, and click "Commit changes".
3. Go to vercel.com, click "Add New…" then "Project", and import that repository.
4. Leave the framework preset as "Other" and click "Deploy".

Every time you replace `index.html` on GitHub, Vercel updates the site automatically.

## Or with a terminal

    cd fine-print-site
    npx vercel --prod

## Your existing Vercel project

The project called `the-fine-print` currently just redirects to the Claude version.
Deploying this folder into that project (or connecting it to the GitHub repository under
Settings, then Git) replaces the redirect with the real site.
