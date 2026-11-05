# PDF Review - downloads

Downloads of **PDF Review**, the PDF markup app used at Chavez Engineering PLLC.
This repository holds only the finished app and its release notes. No source code is kept here.

**Download:** open [the latest release](https://github.com/ChavezEngineering/pdf-review-releases/releases/latest) and,
under *Assets*, pick `PDFReview-windows.zip` (Windows) or `PDFReview-mac.zip` (Mac).

**Windows install:** download `PDFReview-windows.zip` and `install_windows.ps1` into the same folder, then in
PowerShell in that folder run
`powershell -ExecutionPolicy Bypass -File install_windows.ps1 -Source PDFReview-windows.zip`.
It installs for your user only (no admin), adds shortcuts, the right-click "Combine Files in PDF Review" entry, and
opens Settings so you can make PDF Review your default PDF app.

Once installed, the app updates itself: **Check for Updates** (top right) asks "Install it now?" when there is a new
version.
