# Sapir Auto Login

A small browser extension that makes logging in to the Sapir College login page very easy. Save your username and password once, and it logs you in automatically.

## Download

1. Download the extension's zip file.
2. **Unzip it.**
3. Keep the unzipped folder somewhere permanent. The browser uses the files in it.

The folder you choose below is the one that contains `manifest.json`.

## Add the extension to your browser

### Google Chrome

1. Go to `chrome://extensions`.
2. Turn on **Developer mode** (top right).
3. Click **Load unpacked**.
4. Select the unzipped folder.

### Opera

1. Go to `opera://extensions`.
2. Turn on **Developer mode**.
3. Click **Load unpacked**.
4. Select the unzipped folder.

### Firefox (version 128 or newer)

1. Go to `about:debugging#/runtime/this-firefox`.
2. Click **Load Temporary Add-on**.
3. Select the `manifest.json` file inside the unzipped folder.

Firefox removes temporary add-ons when it closes, so repeat these steps after restarting it.

### Safari (Mac)

1. Open **Safari > Settings > Advanced** and turn on **Show features for web developers**.
2. Open the **Developer** tab and check **Allow unsigned extensions**.
3. Click **Add Temporary Extension…** and select the unzipped folder.
4. In the **Extensions** tab, make sure the extension is enabled. If Safari asks, allow it on the Sapir login page.

Safari removes temporary extensions after 24 hours or when you quit it, so repeat these steps when that happens.

## How to use it

1. Click the extension's icon in the browser toolbar. If you don't see it, look in the extensions menu.
2. Enter your Sapir username and password.
3. Make sure **Auto login on** is checked.
4. Click **Save**.

That's it. Open the Sapir login page and the extension logs you in.

To stop automatic login, uncheck **Auto login on**.

## Security note

Your username and password are saved in your browser's extension storage on your own computer, **without encryption**. The extension only runs its login script on `https://ids.sapir.ac.il/nidp/*`. Don't use it on a shared or public computer.

---

This is a personal project and is not an official Sapir College product.
