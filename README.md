# UZZAP — Download Site

Official APK builds for UZZAP, the J2ME MIDP chat recreation.
Live site: https://cyanideph.github.io/uzzap-site/

## APK publication

The Android repository builds the authoritative debug APK on every push to `main`.
A separate `workflow_run` publication workflow in the Android repository automatically publishes the successful `Uzzap-debug-apk` artifact to this site.

The cross-repository publication requires a GitHub Actions secret named `UZZAP_SITE_TOKEN` in the Android repository. The token must have permission to write contents to `cyanideph/uzzap-site`.

GitHub Pages then serves the updated `uzzap-debug.apk` and website metadata.

The website version and displayed APK size are synchronized from the successful Android CI publication rather than maintained as an independent build number.
