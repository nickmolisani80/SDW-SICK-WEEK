# DSM Supra Life - Standalone Video Media Page

## What this is
A standalone public video media page with:
- Video grid
- QR code that links to the live page
- Social links
- Merch and race fund buttons
- Mobile-friendly layout
- Light grey textured / dark racing style

## Video files to add
Create a folder named `videos` beside `index.html`, then place these files inside it:

- IMG_5303.MOV
- IMG_5298.MOV
- IMG_5299.MOV
- IMG_5300.MOV
- IMG_5304.MOV
- IMG_5305.MOV
- IMG_5901.MOV
- IMG_5306.MOV
- IMG_5827.MOV
- IMG_5900.MOV
- IMG_5903.MOV

The paths must look like this:

```
index.html
videos/IMG_5303.MOV
videos/IMG_5298.MOV
videos/IMG_5299.MOV
videos/IMG_5300.MOV
videos/IMG_5304.MOV
videos/IMG_5305.MOV
videos/IMG_5901.MOV
videos/IMG_5306.MOV
videos/IMG_5827.MOV
videos/IMG_5900.MOV
videos/IMG_5903.MOV
```

## Important
Some browsers do not play MOV files well. If videos do not play after deployment, convert each MOV to MP4 and change the filenames in `index.html`.

## Where to edit links
Open `index.html` and update these near the top:

```js
const SITE_URL = "";
const INSTAGRAM_URL = "https://instagram.com/yourhandle";
const YOUTUBE_URL = "https://youtube.com/@yourchannel";
const FACEBOOK_URL = "https://facebook.com/yourpage";
const TIKTOK_URL = "https://tiktok.com/@yourhandle";
const MERCH_URL = "https://your-merch-link.com";
const DONATION_URL = "https://your-venmo-or-racefund-link.com";
```

Leave `SITE_URL` blank until deployed. After Vercel gives you the final link, paste it there so the QR code always points to the official live page.
