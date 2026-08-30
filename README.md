# Lakritse Soundboard

Tseh.

## Lisää audiota.

1. Lisää äänifilu /audio-kansioon.
2. Avaa `sounds.js`.
3. Lisää uusi rivi tyyliin:

```js
window.SOUNDBOARD_SOUNDS = [
  { name: "CmoonPaska", file: "audio/CmoonPaska.mp3" },
  { name: "EiVoiPerkele", file: "audio/EiVoiPerkele.mp3" },
];
```

4. Commit.


## Yms
- Vain mp3 kiitos
- The “Add local sounds” button is temporary and does not upload files to the server.
- Permanent sounds must be placed in the `audio` folder and added to `sounds.js`.
