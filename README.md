# Rafid Mahmud Haque — personal website

A static recreation of https://sites.google.com/view/rafidhaque, prepared on 16 November 2026. Includes Bio, Teaching, Publications, Projects, Awards and Honors, and Activities, plus the original portrait and project images. The red theme and content are retained with a responsive layout. Google Sites-specific search and editing controls are omitted. No installation or build is required; open index.html to preview locally.

## Upload and publish (Windows, using your browser)

1. Download the ZIP and right-click it → Extract All. Open the extracted folder until you can see index.html, style.css, and the assets folder.
2. Sign in to https://github.com as rafid085. This workflow needs no ChatGPT connection. GitHub may still request your normal account verification.
3. Click + → New repository. Set the repository name to rafid085.github.io exactly. Choose Public, enable Add README, and click Create repository. If this repository already exists, inspect its contents and download a backup before replacing any existing website files.
4. On the repository's Code tab, select Add file → Upload files. Drag the CONTENTS of the extracted folder into the upload area, including the assets folder. Do not upload the ZIP or a parent folder containing the website. You must see index.html at the top level, alongside style.css and the assets directory.
5. Use the commit message 'Add personal academic website' and commit the upload to main. If GitHub requires a proposed change, open and merge the resulting pull request.
6. Open Settings → Pages. Under Build and deployment, choose Source: Deploy from a branch. Choose Branch: main and folder: / (root). Click Save.
7. Wait for deployment (GitHub says this can take up to 10 minutes). The expected address is https://rafid085.github.io/. Use the published link shown in Settings → Pages to confirm it is ready.
8. Open each navigation link and check the portrait, project images, email, Google Scholar, LinkedIn, project repository and DOI links.

## Files

- index.html: Bio and home page
- bio.html: duplicate Bio entry for convenience
- teaching.html: undergraduate courses
- publications.html: conference publications and book chapters
- projects.html: AgroVisionBD and rice blast detection project
- awards-and-honors.html: academic awards and scholarships
- activities.html: workshops, certifications and activities
- style.css: colors, layout and mobile rules
- assets/: downloaded original images

## Editing later

Open the corresponding HTML file on GitHub and click the pencil icon. Edit the text, then commit the change. For the biography, update index.html and bio.html together. Change colors and spacing in style.css. Replace image files in assets/ without changing their filenames, or update the matching HTML image src. Future edits to your Google Site do not automatically update this copy.

## If something goes wrong

- 404: confirm the repository name, Public visibility, main branch and / (root) Pages setting. Ensure index.html is at the repository root. Check the Actions tab for deployment failures.
- Missing images: confirm you uploaded the assets folder with its files, preserving filenames and lowercase spelling.
- A README appears as the home page: index.html is probably missing or nested in another folder.
- Old content: wait for the deployment, then press Ctrl+F5 in your browser.
- Already have a different GitHub Pages website: do not replace it without a backup. These files can also go in a separate project repository; the address will then include that repository's name.

Official instructions:
https://docs.github.com/en/pages/quickstart
https://docs.github.com/en/repositories/working-with-files/managing-files/adding-a-file-to-a-repository
