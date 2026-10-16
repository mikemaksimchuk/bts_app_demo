BEYOND THE SUMMIT — PARTICIPANT APP
Michigan Virtual AI Lab

WHAT IS IN HERE
  index.html             The whole app in one file. Nothing loads from the internet.
  manifest.webmanifest   Makes it installable as an app.
  sw.js                  Offline cache, so it works with no signal at the venue.
  app-icon-*.png         Home screen icon.

TO PUBLISH
  Upload this entire folder to any web host, as a folder, over https.
  Examples: michiganvirtual.org/beyond-the-summit/, Netlify drop, GitHub Pages,
  SharePoint, or any district web server.
  No build step, no server code, no database.

  Then make a QR code pointing at that URL and put it on the table tents.

WHAT PARTICIPANTS DO
  iPhone   Open the link in Safari, tap Share, tap Add to Home Screen.
  Android  Open the link in Chrome, tap the three-dot menu, tap Install app.
  Laptop   Just use the link, or install from the address bar in Chrome or Edge.

  Once added, it opens full-screen with no browser bars and works offline.

NOTES PRIVACY
  Everything a participant types is stored in their own browser only.
  Nothing is uploaded and Michigan Virtual cannot see it. Participants use
  "Export my notes" in the Notebook tab to keep a copy.

OFFLINE / NO-HOSTING OPTION
  index.html also works on its own. Email it or put it on a flash drive and
  open it in any browser. It will run, but it cannot be installed to the
  home screen that way, and the offline cache is not used.
