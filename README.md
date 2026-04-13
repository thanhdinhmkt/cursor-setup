# Cursor IDE Setup - My Experience

## Tools I Installed
- **Cursor IDE** - AI-powered code editor (https://cursor.com)
- **Claude Code extension** - AI coding assistant by Anthropic
- **Codex extension** - AI coding tool by OpenAI

## Steps I Completed
1. ✅ Installed Cursor IDE
2. ✅ Added Claude Code add-on and logged in
3. ✅ Added Codex add-on and logged in
4. ✅ Created this public GitHub repository
5. ✅ Opened repository in Cursor
6. ✅ Created this README.md file
7. ✅ Committed and pushed to GitHub

## Issues I Ran Into & How I Solved Them

- **Issue 1**: Could not find where to search for extensions in Cursor IDE.
  **Solution**: Asked Claude for help and learned that extensions can be accessed via the menu: **View → Extensions**. From there I searched for "Claude Code" and "Codex" and installed them successfully.

- **Issue 2**: When trying to open the repository in Cursor, there was no "Open Folder" option visible in the menu.
  **Solution**: Used **"Add Folder to Workspace"** instead, which achieved the same result — the repository folder was loaded into Cursor and ready to work with.

- **Issue 3**: After running `git clone` in the Cursor terminal, I got an error: `xcode-select: note: no developer tools were found at '/Applications/Xcode.app', requesting install.`
  **Solution**: A dialog box appeared on screen asking to install the Xcode Command Line Tools. I clicked **"Install"** and waited for the download to complete. Once installed, Git worked correctly and the clone command ran successfully.