# anyResourceStart

## A General Overview

<a href="https://docs.altv.mp/js/api/alt-server.IServerEvent.html#_altmp_altv_types_alt_server_IServerEvent_anyResourceStart" target="_blank"> You can find information about the types here. (click to redirect) </a>

## Example

```js
import alt from "alt-server";

alt.on('anyResourceStart', (resourceName) => {
  console.log(`Resource ${resourceName} has started.`);
});
```