# Smart Trading Checklist

A light-theme, offline-first Android checklist for trading preparation. Includes interactive checks for trend/market structure, swing range, premium/discount, liquidity, supply/demand, order blocks, fair value gaps (FVG), and entry confirmation. It also includes trade notes, local-device saving, reset, progress tracking, and text export.

## Use it immediately without installing an APK
Open `SmartTradingChecklist.html` in a browser on your phone. (The standalone HTML file is included separately in the download.) Browser support for saving data from local files can vary, so use the Save checklist button and export your notes as a backup.

## Build an APK automatically with GitHub Actions
This project includes `.github/workflows/build-apk.yml` to build a debug APK in GitHub Actions.
1. Create a new repository on GitHub and upload the contents of this project.
2. Open the repository's **Actions** tab and allow workflows if asked.
3. Select **Build Android APK** and choose **Run workflow** (or push to `main`/`master`).
4. When it finishes, open the workflow run and download the `SmartTradingChecklist-debug-apk` artifact.
5. Extract the downloaded artifact ZIP on your phone or computer to get `app-debug.apk`, then install it on your Android phone. Android may ask you to allow installation from that source.

The APK is not included in this source package; it must be compiled by the workflow or Android Studio. This is a checklist/decision aid, not a signal service or a guarantee of profit. Trading can result in loss.
