# composer-private-repository-test

Add following to global composer config

```json
{
    "repositories": [
        {
            "type": "composer",
            "url": "https://lazyrepository.imfast.io/composer/demo"
        },
        {
            "packagist": false
        }
    ]
}
```

Auth not required but could be required via global auth.json