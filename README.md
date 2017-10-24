# Plainflow-node [![CircleCI](https://circleci.com/gh/plainflow-dcp/plainflow-node.svg?style=svg&circle-token=68654e8cd0fcd16b1f3ae9943a1d8e20e36ae6c5)](https://circleci.com/gh/plainflow-dcp/plainflow-node)

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

Documentation is available at [https://www.plainflow.com/docs/developers/sdk/node](https://www.plainflow.com/docs/developers/sdk/node).
