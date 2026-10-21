# VPC Architecture Visual Lab

A responsive, interactive learning website about AWS VPC networking. It is built with plain HTML, CSS, and JavaScript—no build tools or VS Code required.

## Features
- Video-inspired dark learning dashboard with topic sidebar
- Clickable SVG architecture map: users, Internet, ALB, NAT Gateway, EC2, and RDS
- Eight guided lessons covering VPCs, subnets, gateways, routes, security, app tier, and database tier
- Zoom controls, theme toggle, checklist, and copyable AWS CLI read command
- Responsive layout for desktop, tablet, and mobile

## Run it locally
1. Extract the ZIP.
2. Open `index.html` in a modern browser.
3. Click topics in the sidebar and click components in the diagram.

## Publish using GitHub website
1. Sign in to GitHub and create a new **public** repository, for example `vpc-architecture-visual-lab`.
2. On the repository page, choose **Add file → Upload files**.
3. Upload `index.html`, `style.css`, `script.js`, and this `README.md` from the extracted folder (upload the files, not the ZIP itself).
4. Commit the files to the `main` branch.
5. Open **Settings → Pages**.
6. Under **Build and deployment**, select **Deploy from a branch**.
7. Select branch `main` and folder `/(root)`, then save.
8. Wait a few minutes. GitHub will show your published Pages URL in Settings → Pages.

## Publish using GitHub Desktop
1. Extract the ZIP.
2. In GitHub Desktop, choose **File → Add local repository** only if this folder is already a Git repository. Otherwise choose **File → New repository**, and set the local path to the extracted project folder (or create a new folder and copy the files into it).
3. Commit the files with a message such as `Add VPC visual lab`.
4. Click **Publish repository** and follow the prompts.
5. Enable GitHub Pages using **Settings → Pages** as described above.

## Important AWS note
This project is an educational diagram and does not create AWS resources. The CIDR ranges and architecture are examples. Check your organization's IP plan, AWS pricing, region, security requirements, and service-specific behavior before deploying production infrastructure.

## Project files
- `index.html` — page structure and architecture SVG
- `style.css` — layout, colors, responsive design, animation
- `script.js` — interactive lessons, component details, zoom, theme, and checklist
