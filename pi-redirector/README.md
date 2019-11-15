You will find all redirects we support under `redirects` inside `firebase.json`.

The project is hosted using the default firebase domain `https://pi-redirector.firebaseapp.com`

Example link: `https://pi-redirector.firebaseapp.com/privacy-policy`

# Dependencies
- [git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git)
- [firebase-cli](https://firebase.google.com/docs/cli)

# Deploy
0. Install dependencies
1. Clone the repository: `git clone https://github.com/ostelco/ostelco-firebase-hosting.git`
2. Go to the correct folder: `cd pi-redirector`
3. Login to your redotter firebase account: `firebase login`
4. Deploy the changes to firebase: `firebase deploy --only=hosting` 

# esim-instructions-video

The video is hosted using firebase storage, to update the file you have to manually update a video through the dashboard for pi-redirector.

Currently know working formats:
- .mov
- .mp4

Currently know not working formats:
- .mpeg

