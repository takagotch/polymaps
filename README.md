### polymaps
---

http://polymaps.org/

https://github.com/simplegeo/polymaps

https://github.com/jkotchoff/polymaps

```js
var po = org.polymaps;
var map = po.map()
  .container(document.getElementById("map").appendChild(po.svg("svg")))
  .add(po.interact())
  .add(po.hash());
map.add(po.image()
  .url(po.url("http://{S}tile.cloudmade.com"
  + "/xxxxxxxxxxxxxxxxxx"
  + "/998/256/{X}/{Y}/{Z}.png")
  .hosts(["a.", "b.", "c.", ""])));
```

```
```

```
```

