---
title: account.installTheme
description: Install theme
image: https://docs.madelineproto.xyz/favicons/android-chrome-256x256.png
---
# Method: account.installTheme  
[Back to methods index](index.md)


Install theme

### Parameters:

| Name     |    Type       | Description | Required |
|----------|---------------|-------------|----------|
|dark|[Bool](../types/Bool.md) | Whether to install the dark version | Optional|
|format|[string](../types/string.md) | Format | Optional|
|theme|[InputTheme](../types/InputTheme.md) | Theme to install | Optional|


### Return type: [Bool](../types/Bool.md)

### Can bots use this method: **YES**


### MadelineProto Example ([now async for huge speed and parallelism!](https://docs.madelineproto.xyz/docs/ASYNC.html)):


```php
if (!file_exists('madeline.php')) {
    copy('https://phar.madelineproto.xyz/madeline.php', 'madeline.php');
}
include 'madeline.php';

$MadelineProto = new \danog\MadelineProto\API('session.madeline');
$MadelineProto->start();

$Bool = $MadelineProto->account->installTheme(['dark' => Bool, 'format' => 'string', 'theme' => InputTheme, ]);
```

Or, if you're into Lua:

```lua
Bool = account.installTheme({dark=Bool, format='string', theme=InputTheme, })
```
