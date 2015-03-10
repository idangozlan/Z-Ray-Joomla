# Z-Ray-Joomla

This is an extension to add functionality to the Zend Server Z-Ray. 
It will result in additional tab(s) to be presented in the browser.

### Current state
Version 0.2.1 (beta) = Ready for production, but perhaps not as many features as possible. Leave your comment for feature suggestions.

### Requirements
Zend Server 8 with Z-Ray support enabled.

This extension will only output on Joomla sites with the Z-Ray toolbar enabled.

### Installation
Create a directory `/usr/local/zend/var/zray/extensions/Joomla`, and add the contents of this repo within.

```
    /usr/local/zend/var/zray/extensions/Joomla/zray.php
    /usr/local/zend/var/zray/extensions/Joomla/logo.png
```

### Features
* Listing of all rendered Joomla modules (`mod_menu`, etcetera)
* Listing of triggered Joomla events (`onAfterRender`, etcetera)
* Listing of request data (component-name, view, layout, ID)

### Contact
Open an issue in the GitHub repo if you want. Alternatively, contact me at jisse AT yireo AT com or tweet to @yireo. Eat your vegetables.
