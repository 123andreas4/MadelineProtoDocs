---
title: "secureFile"
description: "Secure passport file, for more info see the passport docs »"
nav_exclude: true
image: https://docs.madelineproto.xyz/favicons/android-chrome-256x256.png
---
# Constructor: secureFile  
[Back to constructors index](/API_docs/constructors/index.md)



Secure [passport](https://core.telegram.org/passport) file, for more info [see the passport docs »](https://core.telegram.org/passport/encryption#inputsecurefile)

### Attributes:

| Name     |    Type       | Required | Description |
|----------|---------------|----------|-------------|
|id|[long](/API_docs/types/long.md) | Yes|ID|
|access\_hash|[long](/API_docs/types/long.md) | Yes|Access hash|
|size|[int](/API_docs/types/int.md) | Yes|File size|
|dc\_id|[int](/API_docs/types/int.md) | Yes|DC ID|
|date|[int](/API_docs/types/int.md) | Yes|Date of upload|
|file\_hash|[bytes](/API_docs/types/bytes.md) | Yes|File hash|
|secret|[bytes](/API_docs/types/bytes.md) | Yes|Secret|



### Type: [SecureFile](/API_docs/types/SecureFile.md)


### Example:

```php
$secureFile = ['_' => 'secureFile', 'id' => long, 'access_hash' => long, 'size' => int, 'dc_id' => int, 'date' => int, 'file_hash' => 'bytes', 'secret' => 'bytes'];
```  
