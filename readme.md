# KitabuCode (Acode-based)

KitabuCode is an Android programming editor based on Acode, with the KitabuCode name and owner-provided logo. The original project remains on the repository's main branch. This migration uses application ID `com.kitabucode.editor` so it can be tested alongside the previous application.

## Offline tools

Open Terminal once with an internet connection. Setup installs Python 3, pip, Node.js, npm, Git and C/C++ build tools. After successful setup those tools run locally without internet. Additional project dependencies must also be installed before going offline. HTML/CSS/JavaScript preview is available in the editor. Completion and formatting depend on each language's editor integration; installing a compiler does not automatically install its language server.

## Build

Use the **KitabuCode APK** GitHub Actions workflow on `codex/acode-migration`, then download its `KitabuCode-debug` artifact. This is a development APK, not a signed store release.

For a Linux local build, follow CONTRIBUTING.md and run `npm run setup` then `npm run build paid dev apk`. The `paid` argument selects the upstream ad-free variant; this fork does not require payment to install.

## Attribution

Based on https://github.com/Acode-Foundation/Acode. The original MIT copyright and licence are retained in license.txt. Native runtime components, plugins and downloaded packages have their own licences; these remain applicable. The KitabuCode logo was supplied and authorised by the project owner.
