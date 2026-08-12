# Build the .deb

1. Upload this project to a GitHub repository.
2. Open **Actions → Build .deb**.
3. Choose **Run workflow**.
4. Download the `deb-package` artifact from the completed run.

The workflow installs Theos and the required packaging tools, then runs `make package FINALPACKAGE=1`.
