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

IF you want to make a soundloucd link like me, follow this tutorial below.

## 🚀 Quick Start for Forkers
If you just forked this repository, follow these steps to get your own audio player live in minutes.

## 🛠️ Step 1: Create your own NPM Token
You cannot use my token (it is a protected secret!). You need your own "key" to publish.

Go to npmjs.com and log in.

Navigate to Access Tokens > Generate New Token > Classic.

Select Automation as the type.

Copy the code it gives you immediately.

## 🔐 Step 2: Add the Secret to YOUR Fork
On your forked GitHub repo, click the Settings gear icon at the top.

On the left sidebar, go to Secrets and variables > Actions.

Click the New repository secret button.

Name: NPM_TOKEN

Secret: Paste the code you copied from NPM in Step 1.

## ✍️ Step 3: Customize the Code
You only need to edit two files to make this project yours:

1. package.json
Update these two lines so they are unique to you:

"name": Change "airafay-audio-web" to a new, lowercase name (e.g., "yourname-player").

"version": Set this back to "1.0.0".

2. index.html
Put your own music in:

Replace the SoundCloud URL inside the <iframe> tag with your own track link.

Update the labels at the bottom to reflect your song title and artist.

## 🚢 Step 4: Launch!
Commit and Push your changes to the main branch.

Click the Actions tab at the top of your repo.

Note: Click "Enable Actions" if prompted.

Once the Publish to NPM workflow turns green ✅, your site is live!

Your Permanent Link:
https://unpkg.com/YOUR-PACKAGE-NAME@1.0.0/index.html
