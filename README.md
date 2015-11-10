# F2E-Note

### localStorage
```
// 可跨页面通讯
window.addEventListener("storage", fuction(event){
  // event.key, event.oldValue, event.newValue
  console.log(event)
}, false)
```
### try, finally
```
function test(){
  try {
    var obj = {"a" : 1}
    return obj
  } finally {
    // return 后，继续执行
    console.log("in")
    obj = null
  }
}

var ret = test()
console.log(ret)
```
