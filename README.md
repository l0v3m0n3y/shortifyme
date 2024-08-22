# shortifyme
JavaScript library for shortifyme.co
# main
```js
async function main(){
    const {shortifyme} = require('./shortifyme');
    const short= new shortifyme();
    let req=await short.short_url("url")
    console.log(req)
}
main()
```
