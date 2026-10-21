# VPC Architecture — Interactive Builder

This project is a visual, task-based AWS VPC architecture learning website.

## How it works
Each left-side task has a **Perform task** button. Clicking it changes the live SVG diagram by adding the relevant visual layer. Complete the seven tasks in order to build up the full architecture.

1. Create VPC
2. Create public and private subnets across two Availability Zones
3. Attach an Internet Gateway
4. Configure route paths
5. Add a NAT Gateway
6. Add an Application Load Balancer, EC2 app targets, and Auto Scaling label
7. Add a private RDS database tier

## Open locally
Extract the ZIP and open `index.html` in a browser. No install or build step is needed.

## Publish through GitHub
Create a repository → **Add file → Upload files** → upload `index.html`, `style.css`, `script.js`, and `README.md` → commit → **Settings → Pages** → deploy from branch `main`, folder `/(root)`.

## Note
This is a front-end educational simulation. Buttons update the visual diagram in the browser; they do not provision real AWS resources or make AWS API calls. The CIDR blocks and layout are examples, not a deployment template.
