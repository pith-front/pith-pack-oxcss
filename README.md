# pith-pack-oxcss
Pack OxCSS for Pith

-------

# About

This project packs OxCSS so that it can be used with the Pith Framework.

For info about OxCSS, see the Git repo at https://github.com/ian-maurmann/oxcss

For info on Pith, see the Pith website at https://pith-framework.org/

# Install

Install to an existing Pith Framework project

Use Composer to install pack to the `vendor` folder.
```bash
php composer.phar require pith-front/pith-pack-oxcss
```

Add new route to your Route List:

```php
public array $routes = [
    // Other routes....
    // ...
    
    // Add route to call src fallback resources from
    ['route', 'GET', '/resources/vendor/library/oxcss/{filepath:.+}', '\\PithFront\\PithPackOxcss\\OxcssResourceRoute'],
];
```

-------------


# Licensing Info

pith-pack-oxcss contains OxCSS.

### OxCSS
- OxCSS
- The MIT License (MIT)
- Copyright (c) Ian Maurmann
- https://github.com/ian-maurmann/oxcss


### pith-pack-oxcss
- pith-pack-oxcss
- The MIT License (MIT)
- Copyright (c) Ian Maurmann
- Link: https://github.com/pith-front/pith-pack-oxcss






-------------

Thanks!