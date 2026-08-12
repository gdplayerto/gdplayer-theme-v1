# GDPlayer Theme v1

Official GDPlayer Theme v1 for the **GDPlayer** application.

---

## 📋 Theme Installation Guide

To install and activate **GDPlayer Theme v1** on your GDPlayer installation, follow these steps:

### 1. Extract / Move Theme Files
- Copy/extract all contents from this repository into the following folder on your GDPlayer server:
  ```text
  themes/gdplayer/
  ```

---

### 2. Configure `includes/config.php`
Open the `includes/config.php` file in your root GDPlayer installation, then set or verify that `ACTIVE_THEME` constant is set to `'gdplayer'`:

```php
/**  @define string ACTIVE_THEME current active theme folder name. Default: default */
define('ACTIVE_THEME', 'gdplayer');
```

---

### 3. Done
Save the `includes/config.php` file. The **GDPlayer Theme v1** theme is now successfully installed and active on your GDPlayer application.
