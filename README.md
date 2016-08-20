# web-socket [![Build Status](https://travis-ci.org/hph/web-socket.svg?branch=master)](https://travis-ci.org/hph/web-socket)

A [Polymer](https://www.polymer-project.org/1.0/) element to ease the use and
configuration of
[WebSockets](https://developer.mozilla.org/en-US/docs/Web/API/WebSocket).

```html
<web-socket url="ws://echo.websocket.org"
            auto json
            on-open="_onOpen"
            on-close="_onClose"
            on-message="_onMessage"
            on-error="_onError">
</web-socket>
```

The above example shows how to establish a WebSocket connection with
`<web-socket>` in a [Polymer](https://www.polymer-project.org) app. This simple
declarative element definition is:

- Establishing a connection to `ws://echo.websocket.org`.
- Automatically connecting on page load.
- Parsing and stringifying JSON automatically.
- Automatically reconnecting in the event of an unclean close event (a default
  behaviour of this library - no configuration required through properties).
- Setting up event handlers to functions declared externally (`_onOpen`,
  `_onClose`, etc - defined by a parent element, such as a page).

### Install

You can install `<web-socket>` with Bower

    bower install web-socket

You can also view the [documentation](http://hph.github.io/web-socket), try the
[demo](http://hph.github.io/web-socket/demo) and run the
[tests](http://hph.github.io/web-socket/test).
