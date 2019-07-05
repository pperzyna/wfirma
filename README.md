# wFirma
wFirma PHP Library

Fork with errors handling and some changes

### How to use it
Add folowing package code to composer.json
```json
    ...
    "require": {
       ...
      "pperzyna/wfirma": "master", 
       ...
    },
    "repositories": [
        {
            "type":"package",
            "package": {
                "name": "pperzyna/wfirma",
                "version": "master",
                "source": {
                    "url": "https://github.com/pperzyna/wfirma.git",
                    "type": "git",
                    "reference":"master"
                },
                "description": "wFirma PHP Library",
                "keywords": ["php", "wfirma"],
                "require": {
                    "guzzlehttp/guzzle": "~6.0"
                },
                "minimum-stability": "dev",
                "autoload": {
                    "psr-4": {
                        "Zalazdi\\wFirma\\": "src/"
                    },
                    "files": [
                        "src/helpers.php"
                    ]
                }
            }
        }
    ],
...
```
