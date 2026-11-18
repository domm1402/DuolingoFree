# Duo Academy

A free, mobile-first learning app for languages, programming and other skills.

## Run locally
Open `index.html` in a browser, or serve this folder with a static web server. GitHub Pages deployment is configured in `.github/workflows/pages.yml`.

## Included
- Language catalogue with starter courses across 20+ languages
- Programming catalogue covering mainstream and specialist languages, plus custom course creation
- Interactive multiple-choice lessons and progress paths
- XP, gems, streak tracking, daily quests and achievements
- Code playground for HTML, CSS and JavaScript, isolated in a sandboxed iframe
- Flashcards, quick practice, spoken prompts using browser speech synthesis
- Learner profile, daily XP goal, progress export/import
- Gem shop items, personal league preview and streak calendar
- Installable PWA with an offline cache for core app files
- Responsive mobile layout

## Local data
Progress is stored in the browser's local storage on the device. Use Profile → Export progress to make a backup and Import progress to restore it. Clearing browser data will remove locally stored progress unless it has been exported.

## Execution support
The built-in live playground executes HTML, CSS and JavaScript locally. Lessons for other programming languages are currently instructional; running those languages requires a compiler or execution service that is not bundled into this static app.

## Project identity
Duo Academy is an independent personal learning project. Its interface, mascot and lesson content are original and are not official Duolingo software. The “Super Duolingo” banner is a label for the app's own unlocked personal feature set, not an official Duolingo subscription or account.


## Android APK

The repository includes a native Android WebView wrapper in `android/`. Every push to `main` builds a debug APK with GitHub Actions. Open the repository's **Actions** tab, select **Build Duo Academy APK**, open the latest successful run, and download the `duo-academy-android-apk` artifact. Extract the ZIP to get `app-debug.apk`, then install it on your Android device. The debug APK is suitable for personal testing; a signed release build is not configured yet.
