# Any Video to MP4

A single-page web app that converts almost any video (MKV, AVI, MOV, WebM, FLV, WMV, TS, 3GP...) to MP4 (H.264 + AAC) entirely in the browser using ffmpeg.wasm. No server, no uploads.

## Put it online (free, GitHub Pages)
1. Create a new GitHub repository (e.g. `video-to-mp4`).
2. Upload `index.html` and this `README.md` (Add file > Upload files).
3. Settings > Pages > Deploy from a branch > `main` / root > Save.
4. Open `https://<your-username>.github.io/video-to-mp4/` on any device, including a smart TV browser.

## Notes
- The first conversion downloads the converter (about 30 MB); later ones reuse it.
- Large files need free memory. On phones and TVs, files under about 500 MB work best.
- Runs on any modern browser with WebAssembly (Chrome, Edge, Firefox, Safari, most smart TV browsers).
