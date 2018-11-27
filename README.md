### hashmap
---
https://github.com/flesler/hashmap

```
npm install hashmap
bower install hashmap
npm test
```

```js
var map = new HashMap();
var HashMap = require('hashmap');
map.set();
map.get();

var map = new HashMap();
map.set("key1", "val1");
map.set("key2", "val2");
map.size;

map.set("some_key", "some value");
map.delete("some_key");
map.get("some_key");

map.set("1", "string one");
map.set(1, "number one");
map.set("1");

var key = {};
var key2 = {};
map.set(key, 123);
map.set(key2, 321);
map.get(key);

map.set(1, "test 1");
map.set(2, "test 1");
map.set(3, "test 3");
map.forEach(function(value, key){
  console.log(key + " : " + value);
});

map
  .set(1, "test 1")
  .set(2, "test 2")
  .set(3, "test 3")
  .forEach(function(value, key){
    console.log(key + " : " + value);
  });
```

```
```

