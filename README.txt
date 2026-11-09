IQBAL DAILY ACTIVITY CRM - BUILD THE APK (free, no Android Studio needed)

Do this on a computer (GitHub's upload page needs it):
1. Make a free account at github.com and create a NEW repository (public or private), e.g. iqbal-crm.
2. Unzip this package. Open the repository > "Add file" > "Upload files".
   Drag EVERYTHING from inside the unzipped folder, including the hidden ".github" folder
   (if it does not appear, see step 2b).
   2b. If ".github" is missing: click "Add file" > "Create new file", type the name
       .github/workflows/build-apk.yml   and paste the contents of that file. Commit.
3. Commit the files. Click the "Actions" tab > "Build APK" > "Run workflow" (wait 5-8 minutes).
4. Open the finished run > "Artifacts" > download "Iqbal-CRM-apk" (a zip). Unzip it to get app-debug.apk.
5. Send app-debug.apk to your phone (WhatsApp, Drive, USB). Tap it and allow "Install unknown apps".
6. Open the app. Allow Notifications. If asked, allow "Alarms & reminders".

NOTES
- Data is stored inside the app on your phone. Use Backup / Download Excel regularly
  (the file opens a Share sheet: choose Drive, WhatsApp, Files, etc).
- Reminders are real phone notifications even when the app is closed.
