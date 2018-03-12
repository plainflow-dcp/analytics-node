# Plainflow-node

A Node.js client for [Plainflow](https://www.plainflow.com) — The hassle-free way to integrate analytics into any application.


## Installation

```bash
$ npm install plainflow
```


## Usage

```js
const Plainflow = require('plainflow');

const client = new Plainflow('secret key');

client.track({
  event: 'event name',
  userId: 'user id'
});
```


## Documentation

Documentation is available at [https://www.plainflow.com/docs/developers/data-tracking-libraries/node](https://www.plainflow.com/docs/developers/data-tracking-libraries/node).
