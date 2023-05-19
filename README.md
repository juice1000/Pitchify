# Project Title

A mobile streaming app that plays music from YouTube and enables users to do pitch and speed manipulation.

## Web Demo for you to try

https://pitchify-client.netlify.app

## Demo Video of the App

<img src="demo.gif" width="200">

## Installation

### Setup Expo Simulator

In order to use a simulator for the mobile app, you'll need to install either [Xcode](https://apps.apple.com/us/app/xcode/id497799835?mt=12) or [Android Studio](https://developer.android.com/studio)

For Android Studio there's a bunch of extra configurations to be made in order to run it with Expo, check out [Expo's official documentation](https://docs.expo.dev/workflow/android-studio-emulator/) for more information.

### Setup Local Environment

Run

```bash
  npm i && npm run postinstall
```

in parent folder

## Run locally

To run the whole mobile app locally, you need to launch from 3 separate Terminals:

```bash
  npm run start:server
  npm run start:client
  nom run start:native-app
```

## API Reference

#### Fetch Youtube Data in Mobile App

```http
  GET https://www.googleapis.com/youtube/v3/search
```

| Parameter | Type     | Description                                          |
| :-------- | :------- | :--------------------------------------------------- |
| `API_KEY` | `string` | **Required**. You need to generate a Youtube API key |

- [How to register your API key](https://developers.google.com/youtube/v3/getting-started?hl=de)

#### Pitch Shifting using Web Audio API

- [How Pitch Shifting works](https://www.researchgate.net/publication/228756320_New_phase-vocoder_techniques_for_real-time_pitch_shifting)

- [AudioWorkletProcessor used for implementation](https://developer.mozilla.org/en-US/docs/Web/API/AudioWorkletProcessor)

## Authors

- [@juice1000](https://www.github.com/juice1000)

## Acknowledgements

- [Author doing original Audio Manipulation ](https://github.com/olvb)
