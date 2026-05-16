Changes:
* Removing cancel token link from new account template since email scanners will "click" links to test them, thereby invalidating the token.
* Update Bugzilla.pm:87 to explicitly set $path to minimal safe to resolve taint issue
