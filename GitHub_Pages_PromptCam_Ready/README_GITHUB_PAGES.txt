PROMPTCAM MOBILE — GITHUB PAGES INSTALL
=======================================

1. Extract GitHub_Pages_PromptCam.zip on your computer or phone.
2. Open your GitHub repository on github.com.
3. Select Add file > Upload files.
4. Upload ALL FIVE extracted app files:
   index.html
   manifest.webmanifest
   sw.js
   icon-192.png
   icon-512.png
   They must be in the TOP LEVEL (root) of your repository.
   IMPORTANT: Do NOT upload the ZIP as a single file. GitHub will not
   automatically extract and publish it as a website.
5. Commit changes.
6. Repository Settings > Pages > Build and deployment:
   Source: Deploy from a branch
   Branch: main; Folder: /(root); Save.
7. Open https://YOUR-USERNAME.github.io/YOUR-REPOSITORY/
   (GitHub Pages may take a few minutes to publish.)
8. On Android: open the URL directly in Chrome, tap Start Camera,
   and allow camera and microphone permissions.
9. Chrome menu > Add to Home screen / Install app (optional).

DAILY USE — NO REUPLOAD NEEDED
------------------------------
Open the SAME website link, tap Script > Clear > Paste new script > Done.
Start Camera, tap Scroll, and optionally Record. Script changes are stored
on your phone locally. Do not clear Chrome site data if you want to keep
saved scripts. The script is NOT added to video recordings.

PERMISSION TROUBLESHOOTING
-------------------------
- Open the HTTPS GitHub Pages website, not a github.com file preview,
  a downloaded .html file, or a ChatGPT preview.
- Android Settings > Apps > Chrome > Permissions > Camera / Microphone
  must allow access.
- In Chrome, open site settings for the GitHub Pages address and reset
  blocked camera/microphone permissions, then reload.
- Close other camera apps and retry.

This is an installable website (PWA), not an Android APK. Recording format
may be WebM or MP4 depending on device/browser. Camera access depends on
browser and Android permissions. Nothing is uploaded to a server by the app.
