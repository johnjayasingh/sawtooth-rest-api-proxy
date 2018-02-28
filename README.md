# sawtooth-rest-api-proxy

> Reverse proxy for Sawtooth REST API using Express

## Getting started

```bash
git clone git@github.com:thegreatsunra/sawtooth-rest-api-proxy.git

cd sawtooth-rest-api-proxy

npm install
```

Edit the values in `config.js` to reflect the URL of your Sawtooth REST API, and the port that you want the proxy to run on.

## Usage

```bash
cd sawtooth-rest-api-proxy

node index.js
```

### Use pm2 to start proxy as a long-running process

```bash
npm install -g pm2

cd sawtooth-rest-api-proxy

pm2 start index.js
```
