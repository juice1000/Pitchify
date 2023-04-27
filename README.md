
# Project Title

A mobile app that streams audio files from Youtube and enables pitch and speed manipulation through user interaction

## Demo

https://youtu.be/tMG2V0y_Isw
## Installation

Run

```bash
  npm i && npm run postinstall
```
in parent folder
## API Reference

#### Fetch Youtube Data in Mobile App

```http
  GET https://www.googleapis.com/youtube/v3/search
```

| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
| `API_KEY` | `string` | **Required**. You need to generate a Youtube API key |

- [How to register your API key](https://developers.google.com/youtube/v3/getting-started?hl=de)

#### Pitch Shifting using Web Audio API

- [How Pitch Shifting works](https://www.researchgate.net/publication/228756320_New_phase-vocoder_techniques_for_real-time_pitch_shifting)

- [AudioWorkletProcessor used for implementation](https://developer.mozilla.org/en-US/docs/Web/API/AudioWorkletProcessor)




## Authors

- [@juice1000](https://www.github.com/juice1000)


## Acknowledgements

 - [Author doing original Audio Manipulation ](https://github.com/olvb)

