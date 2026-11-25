LILY — Android installable website (PWA)

This test build starts with sample cycle data: period began 16 November 2026 and ended 20 November 2026; average cycle length 30 days and period duration 5 days. Confirm these dates with your friend and get her permission before entering or keeping her personal cycle information.

TO TEST ON ANDROID
1. Upload the contents of this folder to an HTTPS static host (for example, Netlify, Cloudflare Pages, or GitHub Pages). Keep index.html, manifest.webmanifest, sw.js, and icons/ together.
2. Open the HTTPS URL in Google Chrome on Android.
3. Use Chrome menu ⋮ → Install app / Add to Home screen, or tap Install Lily if shown.
4. Open Lily from the home screen.

FEATURES IN THIS TEST BUILD
- Cycle calendar, period logging, cycle history, symptom/mood notes, editable cycle settings.
- Local-only storage in the browser on that device; no account or cloud sync.
- Export and clear-data controls.
- Lily’s little care notes and opt-in browser notifications.

NOTIFICATION LIMITATION
This prototype checks for an upcoming-period reminder when Lily is opened. It does not provide reliable scheduled notifications while the app is closed. True background reminders require a push-notification service and server setup.

PRIVACY & HEALTH
- Cycle entries and logs remain in local browser storage and are not uploaded by this prototype. Anyone with access to the unlocked phone/browser profile may see them. Clearing Chrome site data may erase them; export a backup if needed.
- Only enter your friend’s data with her knowledge and permission.
- Period and ovulation dates are estimates, not contraception or medical advice.
