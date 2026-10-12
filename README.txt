jpillingworth.com: how to publish on GitHub Pages
==================================================
This folder is the whole site: six HTML pages, your CV (PDF) and a CNAME file.
No builder, no framework. You can open index.html on your computer to preview it.

ONE-TIME SETUP (about 20 minutes)
1. Create a free account at github.com (use a professional username, e.g. jpillingworth).
2. Click New repository. Name it: jpillingworth.com   Set it to Public. Create.
3. On the new repository page click "uploading an existing file" and drag in every file
   in this folder (index.html, career.html, education.html, projects.html, research.html,
   outside.html, Illingworth_JP_CV.pdf, CNAME). Click Commit changes.
4. Settings > Pages. Under "Build and deployment" choose: Deploy from a branch,
   Branch: main, folder: / (root). Save.
5. Same page, Custom domain: jpillingworth.com. Save. (The CNAME file already says this.)

POINT YOUR DOMAIN (in GoDaddy, where jpillingworth.com is registered)
6. GoDaddy > My Products > jpillingworth.com > DNS.
7. Delete the existing A records for "@" and add these four A records (Name "@"):
     185.199.108.153
     185.199.109.153
     185.199.110.153
     185.199.111.153
8. Change the CNAME record named "www" so it points to:  <your-github-username>.github.io
9. Wait 15 minutes to a few hours. Back in GitHub Settings > Pages, tick "Enforce HTTPS"
   once it becomes available.
10. When the new site shows at jpillingworth.com, cancel the GoDaddy Website Builder plan.
    Keep the domain registration.

UPDATING LATER
Edit a page on github.com (pencil icon) or upload a new version of a file. Changes go live
in about a minute, and every previous version is kept in the repository history.
