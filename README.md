Hosting only:
https://console.firebase.google.com/
1. Create Firebase project and a new web app as part of this project
2. Enable hosting in your project
3. Install npm packages like firebase, firebase-cli (global npm installs)
4. in .firebasesrc set your projectID
(From project settings UI)
Project overview gear icon -> Project settings -> Your project section
https://console.firebase.google.com/project/NAME OF THE PROJECT/settings/general/
5. On the same page, scroll down to 'your apps', then copy the firebaseConfig JSON object.
6. Replace the firebaseConfig in index.html
7. go to root and 'npm run dh' or 'firebase deploy'
