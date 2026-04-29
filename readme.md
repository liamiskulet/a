# 🎵 ElijahAbdulLucLiamLink Audio Player

This project is a custom HTML5 audio player hosted via NPM and unpkg, linked to a custom FreeDNS subdomain.

## 🚀 Live Link
[Listen here](unknown, still in wip)

## 📁 Project Structure
- `index.html`: The main player interface.
- `package.json`: Manages the versioning and NPM publishing.
- `assets/`: Contains the audio files (like `luminous.mp3`).
- `.github/workflows/`: Contains the `publish.yml` for automatic deployment.

## 🛠️ How to Update
1. Upload a new song to the `assets/` folder.
2. Update the `<source>` tag in `index.html`.
3. Bump the version number in `package.json`.
4. Commit changes to trigger the GitHub Action.
