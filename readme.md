# 🎵 ElijahAbdulLucLiamLink Audio Player

This project is a custom HTML5 audio player hosted via NPM and unpkg, linked to a custom FreeDNS subdomain.

## 🚀 Live Link
[Listen here](http://unpkg.com/airafay-audio-web@1.1.0/index.html)

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

##  Here are some of my other projects
1. https://github.com/liamiskulet/soundcloudwabdolrafay/blob/main/package.json
2. Or the straight link: https://unpkg.com/soundcloudwabdolrafay@1.0.1/index.html

IF yo want to make a soundloucd link liek me, follow this tutorial below.

🛠️ Step 1: Create your own NPM Token
You can't use my token (it's a secret!). You need your own.

Go to npmjs.com and log in.

Go to Access Tokens > Generate New Token > Classic.

Set the type to Automation and copy the code it gives you.

🔐 Step 2: Add the Secret to YOUR Fork
On your forked GitHub repo, go to Settings (the gear icon at the top).

On the left sidebar, click Secrets and variables > Actions.

Click New repository secret.

Name: NPM_TOKEN

Secret: Paste the code you just copied from NPM.

✍️ Step 3: What to Replace in the Code
You only need to edit two files to make this repo yours:

1. package.json
Open this file and change these two lines:

"name": Change "airafay-audio-web" to a brand new, lowercase name (e.g., "yourname-music-player").

"version": Set this to "1.0.0".

2. index.html
This is where you put your own music.

Find the <iframe> tag and replace the SoundCloud URL with the link to your own song or playlist.

Update the text links at the bottom so they don't say "AiNA THE END" or "Luminous" anymore.

🚀 Step 4: Launch!
Commit your changes to the main branch.

Go to the Actions tab at the top of your GitHub page.

Note: You might see a button asking you to "Enable Actions"—click it!

Wait for the Publish to NPM workflow to finish. If it turns green, you are live!

Your new link will be:
https://unpkg.com/YOUR-NEW-PACKAGE-NAME@1.0.0/index.html
