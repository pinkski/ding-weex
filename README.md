# ding-weex

ding-weex is project about use weex to implements ding
持续更新中...

## How to start

### Install

```bash
npm install
```
### Development

* `npm run build`: build `src/main.we` into `dist/main.js`
* `npm run dev`: watch file changes of `src/main.we` and automatically build into `dist/main.js`
* `npm run serve`: preview in html5 renderer through `http://localhost:8080/`

### Show in Weex Playground

```bash
1. open weex playground app
2. open qrcode scan ,scan http://your weex server ip/dist/main.js
```

*note: the entry file can be configured in `webpack.config.js`, learn more from [weex-loader](https://www.npmjs.com/package/weex-loader)*

Finally the generated code will be found in `dist` folder.



