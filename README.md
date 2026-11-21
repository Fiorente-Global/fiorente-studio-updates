# Fiorente Studio version file

"latest.json" holds the newest published version of Fiorente Studio and its date, nothing else. Fiorente Studio 11.0 and later read it to tell the team when a new version is ready; the download itself stays in Fiorente's private repository and needs a GitHub sign-in.

Copies from before 11.0 (Fiorente Bid Studio) read the same file in Fiorente-Global/bid-studio-updates, so set both until nobody runs one of those copies, then archive that repository.

Update this file only after a release's downloads are published and checked (scripts/check-release.ts in the app's repository). To pull back a release, set it back to the previous version.
