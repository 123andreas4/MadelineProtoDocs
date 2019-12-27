---
title: help.getAppUpdate
description: Returns information on update availability for the current application.
image: https://docs.madelineproto.xyz/favicons/android-chrome-256x256.png
---
# Method: help.getAppUpdate  
[Back to methods index](index.md)


Returns information on update availability for the current application.

### Parameters:

| Name     |    Type       | Description | Required |
|----------|---------------|-------------|----------|
|source|[string](../types/string.md) | Source | Yes|


### Return type: [help\_AppUpdate](../types/help_AppUpdate.md)

### Can bots use this method: **NO**


### MadelineProto Example ([now async for huge speed and parallelism!](https://docs.madelineproto.xyz/docs/ASYNC.html)):


```php
if (!file_exists('madeline.php')) {
    copy('https://phar.madelineproto.xyz/madeline.php', 'madeline.php');
}
include 'madeline.php';

$MadelineProto = new \danog\MadelineProto\API('session.madeline');
$MadelineProto->start();

$help_AppUpdate = $MadelineProto->help->getAppUpdate(['source' => 'string', ]);
```

Or, if you're into Lua:

```lua
help_AppUpdate = help.getAppUpdate({source='string', })
```
