## `IndexedDB`

Relational database implemented with JavaScript objects:

```js
var request = window.indexedDB.open('myNewDatabase', 1);

request.onupgradeneeded = function (ev) {
	ev.target.result.createObjectStore('users', {
		autoIncrement: true
	});
}

request.onsuccess = function (ev) {
	var db          = ev.target.result,
	    transaction = db.transaction(['users'], 'readwrite');
	    store       = transaction.objectStore('users');

	store.add({ email: 'test@example.com' });
}
```