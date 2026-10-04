# Threadlane updates

Public release files and update metadata for Threadlane's Firefox beta.

## Current status

The update feed is initialized with no releases. No signed Firefox package has been published here yet. Do not treat this repository or an unsigned development ZIP as an installable, automatically updating release.

## Distribution

Firefox beta builds will be signed by Mozilla and distributed as XPI release assets here. Installed signed builds will check the HTTPS feed at:

https://raw.githubusercontent.com/ahmed-ela/threadlane-updates/main/firefox/updates.json

The stable Firefox add-on ID is `threadlane@extensions.invalid`. New versions must retain that ID and feed URL. Feed entries will identify the signed release file, version, compatibility minimum, and SHA-256 hash. Only verified signed releases should be promoted to the feed.

Chrome beta builds use a separate unlisted Chrome Web Store listing. Chrome handles their updates after versions are reviewed and published there. Ordinary Chrome on Windows and macOS does not provide the same self-hosted installation route that Firefox supports. A Git push by itself does not publish an extension update for either browser.

This repository contains release artifacts and metadata, not the development source tree. Files and links here are publicly accessible; unlisted distribution is not access control.

## Privacy and support

The browser contacts GitHub to check this feed and download Firefox updates. GitHub receives normal request information, such as the IP address and user agent; notes and queued chat messages are not included in update requests.

[Privacy policy](https://gist.github.com/ahmed-ela/5ce1f17c643c3daaa4bc983e7b0a81bf)

Support: threadlane.support@gmail.com

## Browser documentation

- [Firefox self-distribution](https://extensionworkshop.com/documentation/publish/self-distribution/)
- [Firefox update manifests](https://extensionworkshop.com/documentation/manage/updating-your-extension/)
- [Chrome distribution](https://developer.chrome.com/docs/extensions/how-to/distribute)
