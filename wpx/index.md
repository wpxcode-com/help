# WordPress Library

This library is automatically generated when plugin or theme zip is created. You will not see the file in the editor, is only added when code is synced with your testing domain using the [wpxcode plugin](@wpxcode-plugin) or new archive is created by downloading the plugin and of course on client updates.

## Features

**Define feature**

> wpx()->defineFeature(int $package, array $features);

**Verify feature**

> wpx()->hasFeature(string $feature): boolean;

```php
wpx()->defineFeature(1, ['view']);
wpx()->defineFeature(2, ['edit']);
wpx()->defineFeature(3, ['delete']);

if (wpx()->hasFeature('delete')) {
  // Perform delete
}
```
