You will find all redirects we support under `redirects` inside `firebase.json`.

The project is hosted using the default firebase domain `https://pi-redirector.firebaseapp.com`

Example link: `https://pi-redirector.firebaseapp.com/privacy-policy`

# Deploy
firebase deploy --only=hosting

# esim-instructions-video

The video is hosted using firebase storage, to update the file you have to manually update a video through the dashboard for pi-redirector.

Currently know working formats:
- .mov
- .mp4

Currently know not working formats:
- .mpeg

