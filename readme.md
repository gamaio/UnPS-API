#UnPS-GAMA API
Current Version: v0.0.2 - Not ready for production environment

This is my upcoming API for the services I provide.

Currently, the API supports six functions:
	Shortening of links
	Deletion of shortened links
	Reporting of false negatives
	Uploading images
	Deleting images
	editing images

This implements the upcoming Shortv4 code (which includes deletion of short links with a password) and also implements ImgHostv6 code

API usage can only happen with a valid apikey (a 64 character long string), all transactions are logged for future analysys (either automatic or manual)
The api.backend.php file does not attempt to sanatize imput (other than addslashes on a few uses), that must be done in api.frontend.php

TODO:
	Code the frontend
	Add API user creation
	Add future services
	Implement into services
	TEST the four new functions