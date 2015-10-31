# F2E-Note

## localStorage

跨页面通讯
```
window.addEventListener("storage", fuction(event){
  // event.key, event.oldValue, event.newValue
  console.log(event)
}, false)
```
