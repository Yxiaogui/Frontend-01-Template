```
function encodeStr(str){
  return str.split('').map((s) => `\\u${s.codepointAt().tostring(16)}`)
}
```

