# Build iOS26Anim

This project targets iPhone X / iOS 16 rootless (Dopamine).

## GitHub Actions

1. Push the contents of this folder to your GitHub repository.
2. Open **Actions**.
3. Select **Build .deb**.
4. Tap **Run workflow**.
5. When it finishes, download the **iOS26Anim-deb** artifact.

The workflow builds with Theos and the patched iPhoneOS 16.5 SDK, then creates a rootless `.deb`.
