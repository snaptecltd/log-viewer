# Configure

Add the following to the main composer.json

```json
"repositories": [
    {
        "type": "path",
        "version": "master",
        "url": "/home/snaptec/log-viewer"
    }
],
"require": [
    "snaptecltd/log-viewer": "master",
]

```

Then add the service to config/app.php

Then 
```sh
php artisan config:cache
```
