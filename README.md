# akumoe-downloader
Download image collection from akuma.moe as zip file 📦

## How To Use

1. Open Akuma.moe
2. Find your interested gallery
3. Click "Download" button
4. Save the Zip file
5. Study the academic material


## How It Works

This script directly download image files from akuma.moe current displaying gallery. It will fetch all the pages of the gallery and get their images' URL. Then script will use `GM_xmlhttpRequest` API (in order to cross origin) to download them. After that, it will package them to a Zip file with [JSZip](https://github.com/Stuk/jszip) and give it to you with [FileSaver.js](https://github.com/eligrey/FileSaver.js).

## Tested on

| Browser       | Tampermonkey  |
| ------------- |:-------------:|
| Firefox 122.0 | 5.0.1         |


## Note

- Inspired on [E-Hentai-Downloader](https://github.com/ccloli/E-Hentai-Downloader)