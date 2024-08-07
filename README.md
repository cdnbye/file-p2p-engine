**English | [简体中文](Readme_zh.md)**

<h1 align="center"><a href="" target="_blank" rel="noopener noreferrer"><img width="250" src="https://www.swarmcloud.net/img/logo.png" alt="cdnbye logo"></a></h1>
<h4 align="center">Let your viewers become your unlimitedly scalable CDN.</h4>
<p align="center">
  <a href="https://www.npmjs.com/package/@swarmcloud/file"><img src="https://img.shields.io/npm/v/@swarmcloud/file.svg?style=flat" alt="npm"></a>
  <a href="https://www.jsdelivr.com/package/npm/@swarmcloud/file"><img src="https://data.jsdelivr.com/v1/package/npm/@swarmcloud/file/badge" alt="jsdelivr"></a>
</p>

file-p2p-engine is a file downloader using CDNBye p2p technology.

## Features
- WebRTC data channels for lightweight peer-to-peer communication with no plugins
- Support downloading any type of file
- Instruct the browser to save a file using some response header and service worker
- Multiple files can be downloaded at the same time
- Efficient scheduling policies to enhance the performance of P2P streaming
- Use IP database to group up peers by ISP and regions

## Getting Started
Run [quick-start.html](demo/quick-start.html) in your web page. Wait for a few seconds，then open the same page from another browser. Now you have a direct P2P connection between two browsers without plugin!
The first web peer will serve as a seed, if no one else in the same channel.

## Browser Support
WebRTC has already been incorporated into the HTML5 standard and it is broadly deployed in modern browsers. The compatibility of CDNBye depends on the browser support of WebRTC.

Compatibility|Chrome | Firefox | macOS Safari| Android Wechat/QQ | Opera | Edge | iOS Safari | IE |
:-: | :-: | :-: | :-: | :-: | :-: | :-:| :-:| :-:
WebRTC Datachannel | ✔ | ✔ | ✔ | ✔ | ✔ | ✔ | ✔ | ❌ |

## Prepare
Make sure your file servers have proper CORS (Cross-origin resource sharing) headers so that data can be fetched across domain.
<br>
Click [here](https://www.swarmcloud.net/download#prepare) for more details.

## Include
Include the pre-built script of latest version:
```html
<script src="https://cdn.jsdelivr.net/npm/@swarmcloud/file@latest"></script>
```

## API and Configuration
See [API.md](https://www.swarmcloud.net/download/API)

## Console
Bind your domain in `https://dash.swarmcloud.net`, where you can view p2p-related information.

## Related Projects
- [hlsjs-p2p-engine](https://github.com/cdnbye/hlsjs-p2p-engine) - Web Video Delivery Technology with No Plugins for hls.js.
- [dashjs-p2p-engine](https://github.com/cdnbye/dashjs-p2p-engine) - Web Video Delivery Technology with No Plugins for MPEG-dash.
- [mp4-p2p-engine](https://github.com/cdnbye/mp4-p2p-engine) - Web Video Delivery Technology with No Plugins for MP4.

## FAQ
We have collected some [frequently asked questions](https://www.swarmcloud.net/faq). Before reporting an issue, please search if the FAQ has the answer to your problem.

## Contact Us
Email: service@cdnbye.com
<br>
Telegram: @cdnbye
<br>
Skype: live:86755838




