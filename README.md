# Mongo File Upload

An example of how to upload files to MongoDB.

This is based on a tutorial by [Traversy Media](https://www.youtube.com/watch?v=3f5Q9wDePzY).

## Special Dependencies

``` bash
npm i multer multer-gridfs-storage gridfs-stream method-override
```

### Crypto

Used to generate file names (to avoid duplicate file names). It's a core Node.js module. SImply include it.

``` js
const crypto = require('crypto');
```