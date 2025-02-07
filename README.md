# Sample project for Agora Web SDK 4.x

_English | [简体中文](README.cn.md)_

## Overview

This repository contains sample projects using the Agora RTC Web SDK 4.x.

The Web SDK 4.x refactors the Web SDK 3.x. Based on the features of 3.x, 4.x fully optimizes the internal architecture of the SDK and provides more flexible and easy-to-use APIs.

Compared to the Web SDK 3.x, the Web SDK 4.x has the following advantages:

- Uses promises for asynchronous operations, which improves the robustness and readability of your code.
- Supports TypeScript.
- Replaces the Stream object with Track objects for separate and flexible control over audio and video.
- Improves the channel event notification mechanism, making it easier for you to deal with reconnection.
- Provides more accurate and comprehensive error codes for troubleshooting.

## Projects using jQuery and Bootstrap

| Feature                       | Sample project location          |
| ----------------------------- | -------------------------------- |
| Adjust video profile          | `Demo/adjustVideoProfile`        |
| Audio mixing and audio effect | `Demo/audioMixingAndAudioEffect` |
| Live streaming                | `Demo/basicLive`                 |
| Video call                    | `Demo/basicVideoCall`            |
| Display call status           | `Demo/displayCallStats`          |
| Dual stream                   | `Demo/dualStream`                |
| Push stream to CDN            | `Demo/pushStreamToCDN`           |
| Control recording devices     | `Demo/recordingDeviceControl`    |
| Share the screen              | `Demo/shareTheScreen`            |
| Video beauty effect           | `Demo/videoBeautyEffect`         |

### How to run the sample projects

#### Prerequisites

You need a supported browser to run the sample projects. See [Product Overview](https://docs.agora.io/en/Interactive%20Broadcast/product_live?platform=Web#compatibility) for a list of supported browsers.

#### Steps to run

1. Use a supported browser to open `Demo/index.html` and select a demo.
2. In the demo page, enter your App ID, token, and channel name and join the channel.
    - See [Set up Authentication](https://docs.agora.io/en/Agora%20Platform/token) to learn how to get an App ID and token.
    - You can specify your own channel name. See [join](https://docs.agora.io/en/Interactive%20Broadcast/API%20Reference/web_ng/interfaces/iagorartcclient.html#join) to learn the supported character set.

## Projects using React.js

| Feature    | Sample project location |
| ---------- | ----------------------- |
| Video call | `ReactDemo`             |

### How to run the sample projects

#### Prerequisites

- You need a supported browser to run the sample projects. See [Product Overview](https://docs.agora.io/en/Interactive%20Broadcast/product_live?platform=Web#compatibility) for a list of supported browsers.
- [npm](https://www.npmjs.com/)

#### Steps to run

1. Navigate to `ReactDemo` and run the following command to install dependencies.

    ```shell
    npm install
    ```

2. Use the following command to run the sample project.

    ```shell
    npm run start
    ```

3. In the demo page, enter your App ID, token, and channel name and join the channel.
    - See [Set up Authentication](https://docs.agora.io/en/Agora%20Platform/token) to learn how to get an App ID and token.
    - You can specify your own channel name. See [join](https://docs.agora.io/en/Interactive%20Broadcast/API%20Reference/web_ng/interfaces/iagorartcclient.html#join) to learn the supported character set.

## Reference

- [Web SDK 4.x Product Overview](https://docs.agora.io/en/Interactive%20Broadcast/product_live?platform=Web)
- [Web SDK 4.x API Reference](https://docs.agora.io/en/Interactive%20Broadcast/API%20Reference/web_ng/index.html)

## Feedback

If you have any problems or suggestions regarding the sample projects, feel free to file an issue.
