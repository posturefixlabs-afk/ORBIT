# ORBIT

ORBIT is an offline-first, installable web-app starter designed to be developed from a phone.

## Current starter features
- Responsive dark command-centre interface
- Service worker caches the app shell for repeat/offline visits
- Local notes stored in the browser on this device
- Browser speech recognition where supported and text-to-speech
- Browser notification permission request
- Install prompt where supported

## Important limitations
- The current command handler is a local demo, not a connected AI model.
- Voice recognition varies by browser/device and may require a network connection.
- Notification permission is implemented; reliable scheduled background notifications need additional support.
- Local notes are not synced or backed up.
- Never put a private AI API key in this public client-side repository.

## Deploy with GitHub Pages
Open **Settings → Pages**, select **Deploy from a branch**, choose `main` and `/(root)`, then save. After GitHub publishes the site over HTTPS, open the Pages URL in Android Chrome and use **⋮ → Add to Home screen / Install app**.

## Development order
1. Publish and test the offline shell.
2. Test installation and persistence on Android.
3. Add a secure AI backend or user-configured endpoint without exposing secrets.
4. Add opt-in routines and carefully permissioned automations.
