# UZZAP — Download Site

Official UZZAP app landing/download site.

Live site: https://cyanideph.github.io/uzzap-site/

## APK source

The site no longer stores or builds APK binaries itself. The **UzzapAndroid** repository is the single source of truth for Android CI builds.

Latest debug APK:
https://github.com/cyanideph/UzzapAndroid/releases/download/debug-latest/app-debug.apk

The landing page links directly to that GitHub Release asset, so every successful `UzzapAndroid` debug publish automatically becomes the download available from this site.

## Assets

The `emo/` directory contains the web landing-page emoticon/dolphin assets used by the animated hero.
