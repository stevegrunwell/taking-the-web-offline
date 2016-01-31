### A solution

* Form saves email address, asset IDs, and messages to localStorage <!-- .element: class="fragment" -->
* Register an API endpoint within WordPress where messages can be sent via Ajax <!-- .element: class="fragment" -->
	* Sign messages using a private key built into the app to prevent spam <!-- .element: class="fragment" -->
* <!-- .element: class="fragment" --> Send emails via Ajax on `window.online`