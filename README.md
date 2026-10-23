# Kasboek — installable app

This folder is the complete Kasboek program, ready to put on a free web address
(GitHub Pages). From there you install it on each computer with Chrome or Edge.

Only the *program* is published. Your financial data is never uploaded: it stays
on your computers and in your shared data file.

## 1. Publish once (about 5 minutes)

1. Go to <https://github.com/new>. Repository name: `kasboek`. Choose **Public**
   (GitHub Pages is free for public repositories; only the program is public).
   Click **Create repository**.
2. On the next page click **uploading an existing file**. Drag in everything from
   this folder: `index.html`, `manifest.webmanifest`, `sw.js` and the `icons`
   folder. Click **Commit changes**.
3. Open the repository's **Settings → Pages**. Under *Branch* choose `main` and
   `/ (root)`, then **Save**.
4. After a minute or two, Kasboek is at `https://<your-github-name>.github.io/kasboek/`.

## 2. Install on each computer

- **Mac:** open that address in Google Chrome and click **Install Kasboek**
  (on the welcome screen, under *Settings & backup*, or the install icon at the
  right of the address bar).
- **Windows PC:** open the same address in Microsoft Edge or Chrome and install
  it the same way.

Kasboek then has its own icon in the Dock / Start menu and opens in its own
window, also without internet.

## 3. Bring your data into the app

The installed app does not automatically see data entered in the old
`Kasboek.html` file (the browser keeps them apart).

- **Already using a shared data file?** In the app choose
  **Open our shared data file** and select it. Do this on both computers.
- **Not yet?** In the old version: *Settings & backup → Save backup file*.
  In the app: *Open a Kasboek backup file*. Then set up the shared file under
  *Settings & backup → Use Kasboek on two computers*.

When the browser asks for permission to open the shared file, choose
**Allow on every visit** if it is offered.

## Updates

Replace `index.html` in the repository with the new version (*Add file →
Upload files*). Both computers pick it up automatically the next time Kasboek
starts while online.
