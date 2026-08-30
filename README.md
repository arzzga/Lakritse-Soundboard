# Hostable Soundboard

This is a plain static website. No backend or database is required.

## Add permanent sounds

1. Copy audio files into the `audio` folder.
2. Open `sounds.js`.
3. Add entries like:

```js
window.SOUNDBOARD_SOUNDS = [
  { name: "Air Horn", file: "audio/air-horn.mp3" },
  { name: "Applause", file: "audio/applause.mp3" },
];
```

4. Upload/deploy the whole folder again.

## Hosting

### GitHub Pages
- Create a GitHub repository.
- Upload `index.html`, `sounds.js`, and the `audio` folder.
- In repository Settings > Pages, deploy from your main branch.

### Netlify
- Drag the whole folder into Netlify's manual deploy page.

### Vercel
- Import a repository containing these files.
- No build command is needed; it is a static site.

### Traditional web hosting
Upload all files to your public web directory (often `public_html` or `www`).

## Notes
- MP3 is usually the safest format for broad browser compatibility.
- The “Add local sounds” button is temporary and does not upload files to the server.
- Permanent sounds must be placed in the `audio` folder and added to `sounds.js`.
