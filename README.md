# Trimfy - URL Shortener Service

> An app to create short urls using Node, Express, MongoDB, React, Parcel, Babel
> Use app on Heroku: https://boiling-thicket-14459.herokuapp.com/

## Quick Start

```bash
# Install dependencies
npm install && npm install --prefix client

# Add your mongoURI and baseUrl
Create a ./config/keys_dev.js with your mongoURI and baseUrl

# Run in development mode
npm run server
```

## Endpoint to create short url

### POST api/url/shorten

{ "longUrl": "xxxx" }
