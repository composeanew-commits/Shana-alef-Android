1. Put these files in the ROOT of your GitHub repo (next to index.html):
   package.json, capacitor.config.json, .github/workflows/build-apk.yml
   (index.html is included only so this zip is complete - keep your repo's own copy.)
2. Commit/push. On GitHub: Actions tab > "Build Android APK" > Run workflow.
3. When it finishes (~5 min), open the run and download "TalmidTracker-APK" (a zip containing app-debug.apk).
4. Send app-debug.apk to people. On Android they tap it and allow "install unknown apps".
