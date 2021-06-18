# SCSS setup
Go to vs code setting search sass and select live sass compiler
Open setting.json in Live sass compiler exclude List
Add or edit this section
```bash
"liveSassCompile.settings.formats": [
    {
        "format": "expanded",
        "extensionName": ".css",
        "savePath": "/assets/style/css"
    }
],
```
This will make sure that compiled sass to dir "/assets/style/css"

