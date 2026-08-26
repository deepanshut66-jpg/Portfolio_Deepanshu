DEEPANSHU THAKUR — RENDER-READY STATIC PORTFOLIO

Keep all six files at the root of your GitHub repository. Do not place them
inside another folder. This package uses plain HTML and requires no Node.js,
Next.js, Python, or dependency installation.

FILES TO UPLOAD TO GITHUB
- index.html
- hero.png
- Deepanshu_Thakur_Resume.pdf
- favicon.svg
- render.yaml
- README.txt

RENDER BLUEPRINT METHOD
1. Upload all six files to the root of the GitHub repository and commit them.
2. In Render, open the existing Blueprint and click Manual sync.
3. Render will read render.yaml, run the no-op build command, and publish the
   repository root as a Static Site.

DIRECT STATIC SITE METHOD
1. In Render, choose New > Static Site and connect the GitHub repository.
2. Build command: echo "Static portfolio ready"
3. Publish directory: .
4. Deploy the site.

If Render still runs `next build`, the repository still contains an old
package.json or the service is pointing to the wrong branch/root directory.
Remove the old application files from the repository and keep only these six
files before redeploying.
