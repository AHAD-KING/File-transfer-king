# File Transfer 2.0

A free, static browser-based peer-to-peer file transfer starter. It uses WebRTC DataChannels with manual offer/answer copy-paste signaling.

## Publish free with GitHub Pages
1. On GitHub, create a **public** repository named `file-transfer-2-0`.
2. Upload `index.html` to the repository root.
3. Open **Settings → Pages**.
4. Choose the `main` branch and `/ (root)` as the publishing source, if branch publishing is available; otherwise use the Pages workflow option.
5. Wait for deployment, then open **Visit site**. The URL will look like `https://YOUR-USERNAME.github.io/file-transfer-2-0/`.

## Use
Open the HTTPS page on both phones. Sender creates an offer and shares it with receiver. Receiver pastes offer and creates answer. Sender pastes answer and connects. Keep both pages open.

## Limitations
- This is a starter, not a full Xender replacement.
- Manual connection text is inconvenient and can be long.
- WebRTC connectivity may require internet access for STUN; network restrictions can prevent a connection.
- Browser memory and device/network limits may affect large files.
- The site is static; it does not store or upload files to a central server, but the peer connection details are exchanged manually.
- No automated tests have been run on actual Android devices.
