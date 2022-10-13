# Ingot 2.0
A bookmarklet to disable extensions based on LTBEEF with an interface based on the chrome extension page

### Installation
For easy setup go the the website at https://ingot-2.thegreatestgiant.repl.co/

1. Show your bookmarks bar with `ctrl + shift + b`

2. Right/Alt/Double click on the bar and choose `Add Page`

3. Set the name to `Ingot 2.0` and the URL to the code below or [here](https://github.com/FogNetwork/Ingot/blob/main/bookmarklet.js)

```js
javascript:(()=>{var a=document.createElement('script');a.src='https://cdn.jsdelivr.net/gh/thegreatestgiant/ingot-2.0@main/ingot2.0.js';document.body.appendChild(a)})()
```
