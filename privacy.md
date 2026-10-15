---
title: ShotBasket privacy policy
---

# ShotBasket privacy policy

Updated October 15, 2026. ShotBasket is published by Kaan Pasa Turhal. For privacy or support questions, contact [vetokori@gmail.com](mailto:vetokori@gmail.com).

## Screenshots on your Mac

ShotBasket stores captures locally so you can edit, collect, and paste them as separate files. It uses screen access for captures you request and macOS input permissions for shortcuts and pasting. It does not record what you type, press Return for you, or send messages. It has no advertising, analytics, tracking SDKs, or developer-operated screenshot server.

Captures in the basket survive app restarts. After a capture leaves the basket, ShotBasket keeps its local source file for at least ten minutes so other apps can finish reading it. You can save copies in a folder you choose. Those saved copies remain there unless you opt into a deletion period for them. If you edit a screenshot, the result is a new PNG. Original images and previously saved or uploaded copies are not redacted by later edits.

## Optional cloud connections

Connecting to Google Drive or Dropbox opens that provider's sign-in page in your browser. ShotBasket stores refresh credentials in macOS Keychain and keeps short-lived access tokens in memory. It does not send credentials or screenshot contents to the developer. Disconnecting removes the local connection; you can revoke the app's access from your provider account. Disconnecting does not delete files already uploaded to the provider.

For Google Drive, ShotBasket asks for the `drive.file` scope. It uses your account identifier and email address to confirm the connection, checks accessible folders and their permissions, and uploads the PNGs you select or new captures when you enable automatic uploads. ShotBasket creates a public reader permission only if you explicitly request a link that anyone can open. Otherwise, the destination folder's existing permissions govern access. Google processes account and connection information under its own policies.

For Dropbox, ShotBasket uses its app folder, checks your account identifier and display name, and uploads the PNGs you select or new captures when you enable automatic uploads. It creates a public shared link only if you explicitly request one. Dropbox processes account and connection information under its own policies.

You can also configure your own HTTPS WebDAV destination. Manual uploads send selected PNGs to that server. If you turn on automatic WebDAV uploads, new captures are sent to that server. The server receives the files, the credentials needed for the request, and ordinary connection information such as your IP address. Its operator controls access, logging, and retention. WebDAV passwords or app tokens are stored in macOS Keychain.

Automatic uploads are off until you enable them for a destination. Uploaded files remain with the destination provider or server according to its settings. ShotBasket cannot retract an upload or delete remote copies when you clear the basket, disconnect an account, or edit a screenshot. Delete remote files and revoke sharing from the provider or server.

## Your choices

You can pause or turn off automatic uploads, disconnect provider accounts, change the saved-copy retention setting, clear the basket, and revoke macOS permissions. Copied links stay on your clipboard until another app changes it. If you share a public link, anyone who has the link may be able to open the image.
