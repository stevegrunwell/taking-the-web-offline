##  ydn.db

```js
var db = new ydn.db.Storage('myDatabase');

db.put('users', { email: 'test@example.com' }, 1);
db.get('users', 1).always(function(user) {
  console.log(user);
});
```

```js
> { id: 1, email: 'test@example.com' }
```
<!-- .element: class="fragment" -->