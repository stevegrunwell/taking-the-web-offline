##  Search: Solved.

* <!-- .element: class="fragment" --> YDN.DB has an add-on for Fulltext search <!-- .element: class="fragment" -->
	* Stemming + phonetic normalization
	* Flexible indexing, defined in JavaScript

```php
db.search('products', userQuery).done(function (x) {
	// ...
});
```
<!-- .element: class="fragment" -->