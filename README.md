# Toniok Lekakeny portfolio

A one-page, mobile-first portfolio site. The page is `index.html` and uses inline CSS, so there is no build step or dependency installation.

## Before publishing

1. Replace every `[PLACEHOLDER: ...]` marker in `index.html` with the real information or link. In particular, add the WhatsApp number in international format, professional email, CV PDF, GitHub username/profile, LinkedIn and social profile links, and the missing skills and project details.
2. Upload the CV PDF to `assets/Toniok-Lekakeny-CV.pdf`, or update the CV link in `index.html` to wherever the file will live. Create the `assets` folder in the repository if needed.
3. Update the footer year. Remove any social link you do not want to publish.
4. Preview `index.html` locally in a browser and check the contact links and CV download before publishing. Do not publish while personal placeholders remain.

## Publish with GitHub Pages

1. Sign in to GitHub and create a new **public** repository named exactly `username.github.io`, replacing `username` with your GitHub username. For example, if your username is `toniok`, the repository name is `toniok.github.io`.
2. Upload `index.html` to the repository's top level (the repository root). Upload `README.md` too if you want these instructions included. Upload the `assets` folder and CV PDF if you have added them. The homepage file must be named `index.html` and must not be inside another folder.
3. Open the repository's **Settings** tab, then choose **Pages** in the sidebar.
4. Under **Build and deployment**, set the source to **Deploy from a branch**. Choose the `main` branch and the `/(root)` folder, then save.
5. Wait for the Pages deployment to finish. GitHub will show the published address in the Pages settings. For a user-site repository named `username.github.io`, the address is `https://username.github.io/`.
6. Revisit the Pages settings after deployment and use the published link to check the page on desktop and mobile.

## Optional custom domain

1. Register or use a domain you control, then add it in **Settings → Pages → Custom domain** and save.
2. At your domain provider, configure the DNS records using the exact values GitHub Pages lists for the chosen domain type. DNS settings vary by registrar and whether you use an apex domain or a subdomain, so follow GitHub's current Pages custom-domain instructions rather than guessing records.
3. After DNS has propagated, return to the Pages settings and enable **Enforce HTTPS** if GitHub makes that option available.

Keep the GitHub repository public for a public GitHub Pages site on the standard free plan. Never put passwords, access tokens, private data, or sensitive cybersecurity lab details in this public repository.
