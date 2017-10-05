# learn nodejs

## get absolute path from dynamic path

```
const path = require('path');
path.join(__dirname, 'json/skema_upload.json'),
// returns
'/home/username/dynamic_path/json/skema_upload.json'

```

## get basename from absolute path

```
const path = require('path');
path.basename('/foo/bar/baz/asdf/quux.html');
// returns
'quux.html'
```

## If you also want to remove the extension

```
path.basename('/foo/bar/baz/asdf/quux.html', path.extname(fpath))
// returns
'quux'
```
 
