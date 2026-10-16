BEYOND THE SUMMIT — PARTICIPANT APP
Michigan Virtual AI Lab

WHAT IS IN HERE
  index.html                 The whole app in one file. Nothing loads from the internet.
  manifest.webmanifest       Makes it installable as an app.
  sw.js                      Offline cache, so it works with no signal at the venue.
  app-icon-*.png             Home screen icon, cropped from the official
                             "Beyond the Summit: AI Implementers' Symposium" logo.

TO PUBLISH
  Upload this entire folder, as a folder, to any https web host.
  Examples: michiganvirtual.org/beyond-the-summit/, Netlify drop, GitHub Pages,
  SharePoint, or any district web server.
  No build step, no server code, no database.

  All four icon files must sit next to index.html. If they are missing, phones
  fall back to a screenshot of the page instead of the logo.

  Then make a QR code pointing at that URL and put it on the table tents.

WHAT PARTICIPANTS DO
  iPhone   Open the link in Safari, tap Share, tap Add to Home Screen.
  Android  Open the link in Chrome, tap the three-dot menu, tap Install app.
  Laptop   Just use the link, or install from the address bar in Chrome or Edge.

  Once added, it opens full-screen with no browser bars and works offline.

IF THE ICON LOOKS WRONG AFTER AN UPDATE
  Phones cache home screen icons hard. Delete the icon from the home screen,
  close the browser completely, then add it again. On Android also clear the
  site data for the URL. The ?v= number in index.html forces a refetch, so bump
  it if you ever swap the icon art again.

NOTES PRIVACY
  Everything a participant types is stored in their own browser only.
  Nothing is uploaded and Michigan Virtual cannot see it. Participants use
  "Export my notes" in the Notebook tab to keep a copy.

OFFLINE / NO-HOSTING OPTION
  index.html also works on its own. Email it or put it on a flash drive and
  open it in any browser. It will run, but it cannot be installed to the
  home screen that way, and the offline cache is not used.
