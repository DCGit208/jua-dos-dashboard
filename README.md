JUA HOTEL Q4Life DOS - GitHub Pages Deploy

Files in this folder:
- index.html - main dashboard
- presentation.html - presentation mode
- .nojekyll - prevents GitHub Pages from running Jekyll processing

Quick deploy steps:

1. Create a new GitHub repository.
2. Upload everything in this folder to the root of that repository.
3. In GitHub, open Settings > Pages.
4. Under Build and deployment:
   - Source: Deploy from a branch
   - Branch: main
   - Folder: / (root)
5. Save.
6. Wait for GitHub Pages to publish the site.

Your URLs will be:
- Main dashboard: https://YOUR-USERNAME.github.io/YOUR-REPO/
- Presentation mode: https://YOUR-USERNAME.github.io/YOUR-REPO/presentation.html

Section-specific links:
- Dashboard: https://YOUR-USERNAME.github.io/YOUR-REPO/#dashboard
- Bookings: https://YOUR-USERNAME.github.io/YOUR-REPO/#bookings
- CRM: https://YOUR-USERNAME.github.io/YOUR-REPO/#crm
- POS: https://YOUR-USERNAME.github.io/YOUR-REPO/#pos
- Rooms: https://YOUR-USERNAME.github.io/YOUR-REPO/#rooms
- Internet Sales: https://YOUR-USERNAME.github.io/YOUR-REPO/#internet
- Finance: https://YOUR-USERNAME.github.io/YOUR-REPO/#finance
- Reports: https://YOUR-USERNAME.github.io/YOUR-REPO/#reports

Optional terminal workflow:

git init
git add .
git commit -m "Publish JUA HOTEL dashboard"
git branch -M main
git remote add origin https://github.com/YOUR-USERNAME/YOUR-REPO.git
git push -u origin main