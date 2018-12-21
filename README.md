# multi-rpc-browser

[![NPM](https://nodei.co/npm/multi-rpc-browser.png)](https://nodei.co/npm/multi-rpc-browser/)

[![Build Status](https://travis-ci.org/znetstar/multi-rpc-browser.svg?branch=master)](https://travis-ci.org/znetstar/multi-rpc-browser)

Multi-RPC browser is a [Multi RPC](https://github.com/znetstar/multi-rpc) package which excludes classes that won't run the browser.

## Projects layout

The multi-rpc-browser package is comprised of several modules which can be installed individually.

| Name                                                                                                               | Description                                            | Browser compatible |
|--------------------------------------------------------------------------------------------------------------------|--------------------------------------------------------|--------------------|
| [multi-rpc-common](https://github.com/znetstar/multi-rpc-common)                                                   | Common classes used throughout the project.            | ✓                  |
| [multi-rpc-core](https://github.com/znetstar/multi-rpc-core)                                                       | Server/Client implementation                           | ✓                  |
| [multi-rpc-http-client-side-transport](https://github.com/znetstar/multi-rpc-http-client-side-transport)                     | A HTTP client-side transport                           | ✓                  |
| [multi-rpc-json-serializer](https://github.com/znetstar/multi-rpc-json-serializer)                                 | A JSON serializer                                      | ✓                  |
| [multi-rpc-msgpack-serializer](https://github.com/znetstar/multi-rpc-msgpack-serializer)                           | A MSGPack Serializer                                   | ✓                  |
| [multi-rpc-websocket-client-side-transport](https://github.com/znetstar/multi-rpc-websocket-client-side-transport) | A WebSocket client-side transport                      | ✓                  |

## Tests & Documentation

For mocha tests and documention refer to the individual package (e.g. multi-rpc-common).

## Building

multi-rpc-browser is written in TypeScript. To compile JavaScript run `npm run build`.