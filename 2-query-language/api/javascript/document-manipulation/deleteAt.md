---
layout: api-command 
permalink: api/javascript/delete_at/
command: delete_at
---

{% apibody %}
array.deleteAt(index [,endIndex]) → array
{% endapibody %}

Remove an element from an array at a given index. Returns the modified array.

__Example:__ Hulk decides to leave the avengers.

```js
r.expr(["Iron Man", "Hulk", "Spider-Man"]).deleteAt(1).run(conn, callback)
```


__Example:__ Hulk and Thor decide to leave the avengers.

```js
r.expr(["Iron Man", "Hulk", "Thor", "Spider-Man"]).deleteAt(1,3).run(conn, callback)
```
