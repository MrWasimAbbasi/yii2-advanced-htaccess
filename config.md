# frontend

```php
return [
    'homeUrl' => '/',
    // ...
    'components' => [
        'request' => [
            'baseUrl' => ''
        ],
        // ...
        'urlManager' => [
            'enablePrettyUrl' => true,
            'showScriptName' => false,
        ],
        // ...
    ],
    // ...
];
```

# backend

```php
return [
    'homeUrl' => '/adminpanel',
    // ...
    'components' => [
        'request' => [
            'baseUrl' => '/adminpanel'
        ],
        // ...
        'urlManager' => [
            'enablePrettyUrl' => true,
            'showScriptName' => false,
        ],
        // ...
    ],
    // ...
];
```
