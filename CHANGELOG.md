# Changelog

## 1.2.1

- Clean up types and allow erroring the response similar to `xhr-mock`. Brought to you by [@joscha](https://github.com/joscha)

## 1.2.0

- Add support for `MockXMLHttpRequestUpload`. Thanks a lot to [@joscha](https://github.com/joscha) !

## 1.1.0

- Add readyStates as both static and and instance members
- default response `status` to 200
- Pass mocked `ProgressEvent` and `MockEvent` to event listeners
- Improve TypeScript typings

## 1.0.0

Initial release:

- mock requests
- mock responses
- fake `XMLHttpRequest` interface to make requests to our mock.
