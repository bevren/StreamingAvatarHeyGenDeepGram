# Streaming Avatar Demo With Deepgram Speech to Text Integration

Mix of:

[StreamingAvatar](https://github.com/HeyGen-Official/StreamingAvatar)
[Deepgram Stream Starter](https://github.com/deepgram-starters/live-node-starter/tree/main)

#### Clone the repository

```bash
git clone https://github.com/HeyGen-Official/StreamingAvatar.git
```

#### Edit the config file

Create a new file called `.env`. Paste in the code and enter your API key 

```js
DEEPGRAM_API_KEY=%api_key%
OPENAI_API_KEY=%api_key%
```

#### Edit the index.js file

```js
const heygen_API = {
  apiKey: 'YourApiKey',
  serverUrl: 'https://api.heygen.com',
};
```

#### Run the application

The `start` script will run a web and API server concurrently. Once running, you can [access the application in your browser](http://localhost:3000/).

```bash
npm run start
```

## Introduction

This HeyGen Streaming Avatar demo with real time speech to text translation using Deepgram is a starting point from which developers can adapt and build streaming sessions into their own websites and experiences.

## Getting Started FAQ

### How do I get an API Key?

Either an an API Key or Trial Token from HeyGen is required to run this Streaming API demo. API Keys are reserved for Enterprise customers, whereas both Creator and Teams plan users can activate and use a Trial token. You can retrieve either the API Key or Trial Token by logging in to HeyGen and navigating to this page in your settings: https://app.heygen.com/settings?nav=API

## Sign-up to Deepgram

Before you start, it's essential to generate a Deepgram API key to use in this project. [Sign-up now for Deepgram and create an API key](https://console.deepgram.com/signup?jump=keys).


