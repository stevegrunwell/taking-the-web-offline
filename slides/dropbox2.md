## ![Dropbox](resources/dropbox.svg)

**Limitations:**

* <!-- .element: class="fragment" --> Dropbox for Business gets expensive quickly with distinct users (~$15/month/user)
* <!-- .element: class="fragment" --> Shared logins meant read *and* write access
	* <!-- .element: class="fragment" --> Split the difference: a small number of shared logins w/ read-only access
* <!-- .element: class="fragment" --> API doesn't allow uploading from remote URLs
	* <!-- .element: class="fragment" --> Production assets stored in S3 had to be downloaded, then uploaded to Dropbox
