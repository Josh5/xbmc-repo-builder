xbmc-repo-builder
======================

* Author: Josh Sunnex (josh@ember-dev.com)
* Website: http://ember-dev.com

## Introduction
This is a Simple XBMC Repository template with buid scripts that will allow you to quickly and easy setup/maintain your repo.

## HOW-TO
1. Clone, [Download](https://github.com/Josh5/xbmc-repo-builder/archive/master.zip) or [Fork](https://github.com/Josh5/xbmc-repo-builder/fork) of this repository.
2. Execute "./build" from within the xbmc-repo-builder folder. 

The first time this is run it will walk you through building your repository and XBMC Add-on. Thereon after executing "./build" will update your repo from your current source code.


## Folder structure

    > source
    >>  |_   #### Your Add-on source ####    

    > repo   
    >>  |_   addons.xml     
    >>  |_   addons.xml.md5     
    >>  |_   #### Your XBMC Add-on DIR ####    
    >>>  |_   #### Your XBMC Add-on ZIPs, icon, changelog etc. ####   



## TIPS

For using Github.com as your repo, use this as your URL: 

```
https://raw.githubusercontent.com/########/xbmc-repo-builder/master/
```

For using bitbucket.org: 

```
https://bitbucket.org/########/xbmc-repo-builder/raw/master/
```

Dont forget to change the default "icon.png" before distributing your repo.



**Josh.5** - EmbER-Dev
