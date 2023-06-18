**Clousre Examples:**

```js
function init() {
    var name = "Mozilla"; // name is a local variable created by init
    function displayName() {
      // displayName() is the inner function, that forms the closure
      console.log(name); // use variable declared in the parent function
    }
    displayName();
  }
  init();
```

```js
(function(){
    var shohel= true;
        (()=>{
            var onim=true;
            
                (function(){
                    var jahid=true;
                    
                        (function(){
                            if(shohel&&onim&&jahid)
                                console.log("Everyone is available");
                        })();
                })();
        })();
})();
```

**let vs var Example:**
```js
var funcs = [];
for (var i = 0; i < 3; i++) {
  funcs[i] = function() {
    console.log("My value:", i);
  };
}
for (let j = 0; j < 3; j++) {
  funcs[j]();
}
```
