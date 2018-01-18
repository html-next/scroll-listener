# Scroll Listener

[![Greenkeeper badge](https://badges.greenkeeper.io/html-next/scroll-listener.svg)](https://greenkeeper.io/)

```js
import { Container, addScrollHandler, removeScrollHandler } from 'scroll-listener';

let handler = () => { alert('hi'); };
addScrollHandler(Container, handler);
```