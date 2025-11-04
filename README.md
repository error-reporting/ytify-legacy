> [!Warning]
> This is based on ytify's v7.8 official March 2025 source code, as such it may face issues as it is not officially maintained anymore.
> Some changes have been made to make it work with github pages. `v7.8.7 => v7.8.8`.
> It is not the same as v7x8 which had its last release in September 2025


<div align="center">
 <a href="https://ytify.netlify.app"><img src="public/ytify_thumbnail_max.webp" width="70%"></a>

[![Netlify Status](https://api.netlify.com/api/v1/badges/fbbcc532-3ef6-41fc-b61e-26cb17cfb6ba/deploy-status)](https://app.netlify.com/sites/ytify/deploys)
[![Telegram Members](https://img.shields.io/endpoint?style=flat&url=https://mogyo.ro/quart-apis/tgmembercount?chat_id=ytifytg)](https://t.me/ytifytg)
[![Telegram Online](https://img.shields.io/endpoint?style=flat&url=https%3A%2F%2Ftg.sumanjay.workers.dev%2Fytifytg)](https://t.me/ytifytg)
[![Matrix](https://img.shields.io/matrix/ytify:matrix.org?label=Matrix)](https://matrix.to/#/#ytify:matrix.org)

</div>


> [**ytify-legacy**](https://error-reporting.github.io/ytify-legacy/) is the fastest (56KB to load) and the lightest (7.5K LOC only) centralised audio streaming web application built with an unprecedented hybrid [HTML + SolidJS] approach for maximum efficiency.
>  Listen to **Podcasts**, **Audiobooks**, **Music**, **Livestreams** and other Audio focused YouTube Videos, even under the lowest network conditions.

> As covered in https://blog.csdn.net/gitblog_00024/article/details/139895018 and https://medevel.com/ytify-youtube/

## What else are you getting ?
- **Queuing Features** 🚦
- **ytify collections** 🎷: create your own playlists disconnected from YouTube, share it with the world with share link.
- **YouTube Playlists** 🎶: View them, queue them to the player. You can also both subscribe and import it into your own collections.
- **Theming** 🎨: Modern Autonomous themed UI based on stream thumbnail with High Contrast Mode for increased legibility.
- **PWA** 📱: Install as an app on your device which also allows you to play YouTube links with it from your OS share menu.
- **Radio** 📻: Fetches similar streams and creates a playlist for your stream, great for music listeners.
- **Library** 📚: Discover feed, history, favorites, Channels, YouTube playlists, custom playlists (collections) & Subscription Feed!
- **Download** ⬇️ : Download any audio stream using the button on the action menu.
- **Lyrics** 🎼 : Immersive Synced Lyrics using the button on the action menu.
- **For You** 🎻 : Get audio tailored specifically for you based on your Favorites, generated on device without any violation of privacy.
- **Parental Controls** 👨‍👦 : Disable Parts of the application according to your needs.

![1000012574](https://github.com/user-attachments/assets/450a1eed-0fb6-4fba-8d4a-c18431b935ad)
![1000012580](https://github.com/user-attachments/assets/4abcd09d-d2ef-4e26-8632-1a50cedfbab8)
![1000012579](https://github.com/user-attachments/assets/adf1254a-e565-4fb7-ab51-613bbe69e677)





## WHY / The story of ytify with [n-ce](https://github.com/n-ce)
- I was an avid [NewPipe](https://github.com/TeamNewPipe/NewPipe) user back in 2021, which I used for background playback.
- I noticed it wasn't able to stream under low network conditions.
- So i decided to create an [issue](https://github.com/TeamNewPipe/NewPipe/issues/5838).
- Upon finding no active resolution on the issue, I took it to myself and created this project on Jan 2022.


## Usage 👆
- Instance
  - [My official](https://error-reporting.github.io/ytify-legacy)
  - [Original](https://ytify.pp.ua)
  - [Secondary](https://ytify.netlify.app)
  - [Testing](https://dev--ytify.netlify.app)
- Full Usage Guide is available at [wiki>usage](https://github.com/error-reporting/ytify-legacy/wiki/usage)
- Join our Telegram Community [@ytifytg](https://t.me/ytifytg)
- Join our Matrix Community
[@ytify](https://matrix.to/#/#ytify:matrix.org)


## License 📝
> [Read More](https://github.com/error-reporting/ytify-legacy/blob/main/LICENSE).

## Contributing 📋
> This project is actively seeking contributors, [Read More Here](https://github.com/error-reporting/ytify-legacy/blob/main/CONTRIBUTING.md).

## Development 🔧
1. Prerequisites : Node.js , Beginner TypeScript Knowledge. 
2. Clone repository with
```
git clone https://github.com/error-reporting/ytify-legacy --depth 1
```
or
```
 gh repo clone error-reporting/ytify-legacy -- --depth 1
```
3. Move to Directory, Update & Install Dependencies
```
cd ytify-legacy ; npm run update; npm i
```
4. If you prefer using DevTools, you may disable eruda in [`vite.config.ts`](https://github.com/n-ce/ytify/blob/main/vite.config.ts)
`injectEruda(false),`

5. Start the development server and open localhost 
```
npm run dev -- --open
```
6. Learn More at our [wiki](https://github.com/error-reporting/ytify-legacy/wiki).


#### Vite building the project on my entry-level phone.

```bash
vite v7.1.12 building for production...
✓ 73 modules transformed.
dist/manifest.webmanifest                          1.01 kB
dist/index.html                                   15.88 kB │ gzip:   4.10 kB
dist/assets/UpdatePrompt-BVWVWGFX.css              0.72 kB │ gzip:   0.40 kB
dist/assets/ActionsMenu-DzB5kpEW.css               0.91 kB │ gzip:   0.44 kB
dist/assets/Settings-BsMqzeb-.css                  2.23 kB │ gzip:   0.72 kB
dist/assets/index-C1Z9-jfH.css                    20.65 kB │ gzip:   4.99 kB
dist/assets/enqueueRelatedStreams-B2FO8_k3.js      0.43 kB │ gzip:   0.30 kB
dist/assets/subfeedGenerator-zrZ56PyE.js           0.51 kB │ gzip:   0.36 kB
dist/assets/extractColorFromImage-DK2Ht5t8.js      0.62 kB │ gzip:   0.42 kB
dist/assets/setAudioStreams-CyKTI0py.js            0.67 kB │ gzip:   0.47 kB
dist/assets/setDiscoveries-DX1nhzlG.js             0.87 kB │ gzip:   0.52 kB
dist/assets/virtual_pwa-register-CbGQhOND.js       0.90 kB │ gzip:   0.53 kB
dist/assets/UpdatePrompt-KOl6kybm.js               1.09 kB │ gzip:   0.62 kB
dist/assets/supermix-BVM8E2di.js                   1.13 kB │ gzip:   0.70 kB
dist/assets/Lyrics-DZxLGGB4.js                     1.24 kB │ gzip:   0.80 kB
dist/assets/importPipedPlaylists-AwmTokZ0.js       1.27 kB │ gzip:   0.63 kB
dist/assets/partsManager-CmgDs6sr.js               1.80 kB │ gzip:   0.63 kB
dist/assets/start-DYKcDXuD.js                      1.97 kB │ gzip:   1.06 kB
dist/assets/SuperCollectionList-CBOlBT4r.js        2.42 kB │ gzip:   1.22 kB
dist/assets/WatchVideo-B92uvOCR.js                 3.49 kB │ gzip:   1.59 kB
dist/assets/ActionsMenu-mMLUGy4H.js                4.05 kB │ gzip:   1.71 kB
dist/assets/workbox-window.prod.es5-CwtvwXb3.js    5.76 kB │ gzip:   2.37 kB
dist/assets/ro-nUjBmFtW.js                        10.39 kB │ gzip:   3.36 kB
dist/assets/en-BIveIy_n.js                        12.04 kB │ gzip:   3.91 kB
dist/assets/id-DM_U2fba.js                        12.41 kB │ gzip:   4.11 kB
dist/assets/zh-D3QOo2GG.js                        12.48 kB │ gzip:   4.48 kB
dist/assets/pt-V1C6oc5F.js                        12.76 kB │ gzip:   4.32 kB
dist/assets/pl-DP0Vz_Gq.js                        12.78 kB │ gzip:   4.41 kB
dist/assets/de-B9cmdEYi.js                        12.90 kB │ gzip:   4.36 kB
dist/assets/es-CunG9DIh.js                        13.17 kB │ gzip:   4.37 kB
dist/assets/fr-BJnGeARW.js                        13.19 kB │ gzip:   4.42 kB
dist/assets/Settings-Dxs2zU7O.js                  14.22 kB │ gzip:   4.81 kB
dist/assets/ar-BcR9583f.js                        14.54 kB │ gzip:   4.55 kB
dist/assets/ur-BzdzHqxU.js                        14.68 kB │ gzip:   4.56 kB
dist/assets/ru-CKckOVLt.js                        15.66 kB │ gzip:   4.92 kB
dist/assets/hi-DrTvZ7fL.js                        17.16 kB │ gzip:   4.73 kB
dist/assets/bn-BRHRJXny.js                        17.32 kB │ gzip:   4.84 kB
dist/assets/sa-CPcZJgUt.js                        17.49 kB │ gzip:   4.69 kB
dist/assets/index-D_Td6t-j.js                     90.07 kB │ gzip:  32.54 kB
dist/assets/hls-BvDNz44n.js                      521.10 kB │ gzip: 161.18 kB

(!) Some chunks are larger than 500 kB after minification. Consider:
- Using dynamic import() to code-split the application
- Use build.rollupOptions.output.manualChunks to improve chunking: https://rollupjs.org/configuration-options/#output-manualchunks
- Adjust chunk size limit for this warning via build.chunkSizeWarningLimit.
✓ built in 5.39s
error during build:
Error: Unable to write the service worker file. 'Unexpected early exit. This happens when Promises returned by plugins cannot resolve. Unfinished hook action(s) on exit:
(terser) renderChunk
(terser) renderChunk'
    at writeSWUsingDefaultTemplate (/data/data/com.termux/files/home/ytify-legacy/node_modules/workbox-build/build/lib/write-sw-using-default-template.js:68:15)
    at async generateSW (/data/data/com.termux/files/home/ytify-legacy/node_modules/workbox-build/build/generate-sw.js:95:23)
    at async generateServiceWorker (file:///data/data/com.termux/files/home/ytify-legacy/node_modules/vite-plugin-pwa/dist/index.js:208:23)
    at async _generateSW (file:///data/data/com.termux/files/home/ytify-legacy/node_modules/vite-plugin-pwa/dist/index.js:234:5)
    at async Object.handler (file:///data/data/com.termux/files/home/ytify-legacy/node_modules/vite-plugin-pwa/dist/index.js:427:13)
    at async PluginDriver.hookParallel (file:///data/data/com.termux/files/home/ytify-legacy/node_modules/rollup/dist/es/shared/node-entry.js:22330:17)
    at async Object.close (file:///data/data/com.termux/files/home/ytify-legacy/node_modules/rollup/dist/es/shared/node-entry.js:23347:13)
    at async buildEnvironment (file:///data/data/com.termux/files/home/ytify-legacy/node_modules/vite/dist/node/chunks/config.js:33785:15)
    at async Object.build (file:///data/data/com.termux/files/home/ytify-legacy/node_modules/vite/dist/node/chunks/config.js:34129:19)
    at async Object.buildApp (file:///data/data/com.termux/files/home/ytify-legacy/node_modules/vite/dist/node/chunks/config.js:34126:153)
    at async CAC.<anonymous> (file:///data/data/com.termux/files/home/ytify-legacy/node_modules/vite/dist/node/cli.js:629:3)
```

## Translations 🗺️
[![Translation status](https://hosted.weblate.org/widget/ytify/multi-auto.svg)](https://hosted.weblate.org/engage/ytify/)
ytify is being translated into multiple languages using [Weblate](https://hosted.weblate.org/projects/ytify/web).
 
## Acknowledgements 🙏
- [n-ce's original ytify](https://github.com/n-ce/ytify)
- [Uma](https://github.com/n-ce/Uma) - Instances Manager
- [Piped](https://github.com/teampiped/piped) - YouTube Data API & Adaptive Streaming Proxy
- [Invidious](https://invidious.io) - YouTube Data API & Progressive Streaming Proxy
- [Hyperpipe](https://codeberg.org/Hyperpipe/hyperpipe-backend) - YT Music Artist Data API
- [Cobalt](https://github.com/wukko/cobalt) - YouTube Download API
- [LRCLIB](https://lrclib.net) - Synced Lyrics Provider
- [wsrv](https://wsrv.nl) - Image Proxy Provider
- [Solid](https://github.com/solidjs/solid) - Delightful JSX Library
- [HLS.js](https://github.com/video-dev/hls.js) - HLS Support Library
- [Netlify](https://www.netlify.com) - Hosting, PR Previews, User Feedback Forms, Edge Functions
- [Vite](https://vitejs.dev) - Development Server, Code Bundling, Project Scaffolding.
- [Autoprefixer](https://github.com/postcss/autoprefixer) - CSS Prefixes Solution.
- [Remix Icons](https://github.com/Remix-Design/RemixIcon) - Efficient Icon Solution.
- [Google Fonts](https://fonts.google.com) - NotoSans Font.

