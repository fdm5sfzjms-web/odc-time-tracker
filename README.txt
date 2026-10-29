ODC Time Tracker — iPhone Home Screen Web App

Files:
- index.html: tracker app
- manifest.webmanifest: installable app metadata
- service-worker.js: offline caching
- icon.svg: home-screen icon

Important:
This folder must be hosted on an HTTPS website for iPhone Home Screen installation and service-worker/offline support.
The tracker currently stores records in this browser's local storage. It does not sync or back up records to the cloud.
Do not delete browser website data if you need to retain local records. Export CSV backups regularly.
