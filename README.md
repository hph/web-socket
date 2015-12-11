# web-socket

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
`<web-socket>`.
### Install

You can install `<web-socket>` with Bower

    bower install web-socket

You can also view the [documentation](http://hph.github.io/web-socket), try the
[demo](http://hph.github.io/web-socket/demo) and run the
[tests](http://hph.github.io/web-socket/test).
