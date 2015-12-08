# websocket-binding

A Polymer element to ease the setup and use of a WebSocket.

Example:

```html
<websocket-binding url="ws://echo.websocket.org"
                   on-open="_onOpen"
                   on-close="_onClose"
                   on-message="_onMessage"
                   on-error="_onError">
</websocket-binding>
```

Released under the [MIT License](https://opensource.org/licenses/MIT).
