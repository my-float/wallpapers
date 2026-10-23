# MyFloat reception desktop wallpaper

Public artwork and configuration for MyFloat reception PCs. No installers, passwords or customer information belong here.

To change every configured PC's desktop:

1. Replace `desktop.png` with the approved image (640x360 to 7680x4320; under 12 MB).
2. Calculate its original SHA256 with `Get-FileHash .\desktop.png -Algorithm SHA256`.
3. Update `sha256` in `wallpaper.json`. Update `version` for your own reference. Commit both files to `main` together.

PCs check at Reception sign-in and every six hours; the desktop applies a downloaded change within five minutes while Reception is signed in. No network means the previous image stays in place. Only images are downloaded; this repository cannot supply executable update code. Images and manifest are public.

Lock screen and moving screensaver remain the locally installed MyFloat artwork. This feed changes the desktop wallpaper only.
