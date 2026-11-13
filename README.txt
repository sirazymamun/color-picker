color-picker v1.0.7 - FRESH REPOSITORY + AUTOMATIC GITHUB RELEASE

App name and version remain unchanged: color-picker 1.0.7.

Upload these files to the ROOT of a brand-new GitHub repository:
- source.zip (keep zipped)
- apk-version.txt
- README.txt
- .github/workflows/app-debug.yml

The tutorial/ folder in the delivered ZIP is for you. Do not upload it to GitHub.

When files are pushed to main (or master), GitHub Actions will compile the Android debug APK.
On build success, it uploads color-picker.apk and color-picker-v1.0.7-FULL-with-APK.zip
to both Actions artifacts and GitHub Releases under the v1.0.7 tag.
If v1.0.7 already exists, the assets are replaced; the version is not changed.
The workflow requests contents: write for creating GitHub Releases.

Important: color-picker.apk is a DEBUG-signed testing APK, not a production/release-signed APK.
This source ZIP does NOT itself contain a compiled APK; GitHub Actions adds it to the built package.
Only GitHub and device testing can confirm success.
Screen sampling of protected/DRM screens can return black pixels.

Release policy: GitHub Releases publishes ONLY color-picker.apk. The FULL ZIP (with source and APK) is uploaded privately to the workflow run as an Actions artifact, not to Releases.

GitHub Release assets: only color-picker.apk. Old extra uploaded assets are deleted on a successful build. GitHub-generated Source code links remain (not release assets).
