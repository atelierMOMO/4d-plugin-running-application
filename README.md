4d-plugin-running-application
=============================

Collection of OS X native application manager commands.

### Platform

| carbon | cocoa | win32 | win64 |
|:------:|:-----:|:---------:|:---------:|
||<img src="https://cloud.githubusercontent.com/assets/1725068/22371562/1b091f0a-e4db-11e6-8458-8653954a7cce.png" width="24" height="24" />|||

* Windows向けは[こちら](https://github.com/miyako/4d-plugin-input-method-manager/)

### Version

<img src="https://cloud.githubusercontent.com/assets/1725068/18940648/2192ddba-8645-11e6-864d-6d5692d55717.png" width="32" height="32" /> <img src="https://user-images.githubusercontent.com/1725068/41266195-ddf767b2-6e30-11e8-9d6b-2adf6a9f57a5.png" width="32" height="32" />

Commands
---

```
// --- App
App_LIST
App_TERMINATE
App_FORCE_TERMINATE
App_Is_active
App_ACTIVATE
App_Get_icon
App_HIDE
App_SHOW
App_Is_hidden
App_Get_path
App_Get_localized_name
App_Find_path
```

Examples
---

```
$path:=App Find path ("com.4d.4d")
```
