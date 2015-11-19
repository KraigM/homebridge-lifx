# homebridge-lifx

Supports lifx devices on HomeBridge Platform

Please Note: I didn't write this, I just pulled it out of the homebridge-legacy-plugins repo

# Installation

1. Install homebridge using: npm install -g homebridge
2. Install this plugin using: npm install -g homebridge-lifx
3. Update your configuration file. See sample-config.json in this repository for a sample. 

# Configuration

Configuration sample:

```
"platforms": [
  {
    "platform": "LIFx",             // required
    "name": "LIFx",                 // required
    "access_token": "access token", // required
    "use_lan": "true"               // optional set to "true" (gets and sets over the lan) or "get" (gets only over the lan)
  }
],
```  
