LILY — ANDROID PWA v4

This build fixes Daily Journal date loading. Changing the date now loads that date’s saved entry, or clears the fields when no entry exists. Saving an entry updates only that date.

Upload these files to the ROOT of the GitHub repository (replace existing files): index.html, manifest.webmanifest, sw.js, lily-hero.png, icon-192.png, icon-512.png. README.txt is optional.

GitHub Pages: Deploy from branch > main > /(root).

Privacy: Period dates and journal entries are stored in localStorage in each browser/device and are not synced. Do not put personal cycle data in repository files or screenshots. The website source is publicly visible.

The service worker cache was bumped to v4 so installed copies can receive the updated code.

Notifications are checked when the app opens; scheduled notifications while closed are not guaranteed without a push-notification backend. Predictions are estimates only and must not be used for contraception or diagnosis.


Lily v7 update: adds the approved personal portrait as a small circular image beside the Lily title. The image is stored locally as lily-owner-photo.jpg and cached by the service worker. The daily journal date-specific loading fix from v4 is retained.

Privacy note: if this repository is public, anyone who can access the repository can also access the portrait file. Keep the repository private or remove the portrait before making the project public if that is not intended.


Lily v7 update: the personal portrait beside the Lily title is larger (68x68 CSS pixels) and uses a rounded-square frame rather than a circle. This keeps the square portrait visible without circular edge cropping. The date-specific journal fix and local-storage keys are unchanged.

Lily v7 portrait update: uses the full, uncropped supplied photo in a larger 4:3 frame. The portrait uses object-fit: contain so the whole photo remains visible.
