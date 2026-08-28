LingoForge — PWA package
========================

Files:
  index.html              the app
  manifest.json           makes it installable
  sw.js                   offline support
  icon-192.png            app icon
  icon-512.png            app icon
  icon-maskable-512.png   Android adaptive icon

HOW TO PUBLISH (free, ~10 minutes)
----------------------------------
1. Go to github.com and create a free account.
2. Create a new PUBLIC repository, name it: lingoforge
3. Click "uploading an existing file" and upload ALL files
   in this folder (keep them at the top level, not in a subfolder).
4. Go to Settings -> Pages.
   Under "Branch" choose: main  /  (root)   then Save.
5. Wait 1-2 minutes. Your link appears:
   https://YOURNAME.github.io/lingoforge/

INSTALL ON WINDOWS
------------------
Open that link in Chrome or Edge.
Click the install icon in the address bar (a monitor with an arrow),
or menu -> Install LingoForge.
It becomes a real desktop app with its own window and Start Menu entry.

INSTALL ON ANDROID
------------------
Open that link in Chrome.
Menu -> "Install app" or "Add to Home screen".
It becomes a real app icon, opens fullscreen, no browser bar.

MAKE A REAL .APK FILE
---------------------
1. Go to https://www.pwabuilder.com
2. Paste your GitHub Pages link.
3. Click Package For Stores -> Android.
4. Download. You get a signed .apk (and .aab for Google Play).
5. Send the .apk to your phone and install it.
   You may need to allow "Install unknown apps" for your file manager.

NOTES
-----
- After the first load the app works with no internet.
- Progress is stored per device. Use the Backup buttons
  (menu icon, top right) to move progress between devices.
