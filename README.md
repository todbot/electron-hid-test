# electron-hid-test

Extremely simple [Electron](https://www.electronjs.org/) app example using [`node-hid`](https://github.com/node-hid/node-hid).

To use:
```
npm install
npm run rebuild
npm run start
```

The `npm run rebuild` is to rebuild any native code (i.e. `node-hid`) for the Electron runtime instead of the Node runtime used during `npm install`.

For a slightly more complex example, see https://github.com/todbot/electron-hid-toy.

For more details on using `node-hid` with Electron, see: https://github.com/node-hid/node-hid#electron-projects-using-node-hid
