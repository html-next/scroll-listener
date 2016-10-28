# Scroll Listener

```js
import { Container, addScrollHandler, removeScrollHandler } from 'scroll-listener';

let handler = () => { alert('hi'); };
addScrollHandler(Container, handler);
```