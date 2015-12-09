# web-socket

A Polymer element to ease the use and configuration of WebSockets.

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
`<web-socket>`. The full documentation and examples are available
[here](http://hph.github.io/web-socket/index.html).
