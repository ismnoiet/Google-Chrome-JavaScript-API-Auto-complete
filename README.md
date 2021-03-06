##Google-Chrome-JavaScript-API-Auto-complete

Offer Google Chrome JavaScript API auto-complete for sublime text.


**Preview**

![chrome autocomplet sublime text ](img/autocomplete.gif)


**Requirements :**
* Make sure you have [Sublime Codeintel](https://packagecontrol.io/packages/SublimeCodeIntel) installed and working properly.

**How to make it work?**

1. Copy the content of ``chrome.cix``
2. From sublime text main menu click on <kbd>Preferences > Browse Packages ...</kbd> to open up sublime text packages folder.
3. Now open ``SublimeCodeIntel/libs/codeintel2/stdlibs/javascript.cix`` file
4. Right after the following  snippet of code, paste the content of ``chrome.cix``:

```xml
<codeintel version="2.0">
  <file lang="JavaScript" mtime="1102379523" path="javascript.cix">
    <scope ilk="blob" lang="JavaScript" name="*">
    // here add chrome.cix content(this line should be removed, asit is here for guidance purposes only)
```

**Restart sublime text and now you are ready to go**.




**Available APIs**

Here is the list of already implemented API objects :


* accessibilityFeatures
	* spokenFeedback &#x2714;
	* largeCursor &#x2714;
	* stickyKeys &#x2714;
	* highContrast &#x2714;
	* screenMagnifier &#x2714;
	* autoclick &#x2714;
	* virtualKeyboard &#x2714;
	* animationPolicy &#x2714;
* alarms
	* create &#x2714;
	* get &#x2714;
	* getAll &#x2714;
	* clear &#x2714;
	* clearAll &#x2714;
	* onAlarm &#x2714;
* bookmarks
	* MAX_WRITE_OPERATIONS_PER_HOUR &#x2714;
	* MAX_SUSTAINED_WRITE_OPERATIONS_PER_MINUTE &#x2714;
	* get  &#x2714;
	* getChildren  &#x2714;
	* getRecent  &#x2714;
	* getTree  &#x2714;
	* getSubTree  &#x2714;
	* search  &#x2714;
	* create  &#x2714;
	* move  &#x2714;
	* update  &#x2714;
	* remove  &#x2714;
	* removeTree  &#x2714;
	* onCreated &#x2714;
	* onRemoved &#x2714;
	* onChanged &#x2714;
	* onMoved &#x2714;
	* onChildrenReordered &#x2714;
	* onImportBegan &#x2714;
	* onImportEnded &#x2714;
* browserAction
	* setTitle &#x2714;
	* getTitle &#x2714;
	* setIcon &#x2714;
	* setPopup &#x2714;
	* getPopup &#x2714;
	* setBadgeText &#x2714;
	* getBadgeText &#x2714;
	* setBadgeBackgroundColor &#x2714;
	* getBadgeBackgroundColor &#x2714;
	* enable &#x2714;
	* disable &#x2714;
	* onClicked &#x2714;
* browsingData
	* settings &#x2714;
	* remove &#x2714;
	* removeAppcache &#x2714;
	* removeCache &#x2714;
	* removeCookies &#x2714;
	* removeDownloads &#x2714;
	* removeFileSystems &#x2714;
	* removeFormData &#x2714;
	* removeHistory &#x2714;
	* removeIndexedDB &#x2714;
	* removeLocalStorage &#x2714;
	* removePluginData &#x2714;
	* removePasswords &#x2714;
	* removeWebSQL &#x2714;
* certificateProvider
	* onCertificatesRequested &#x2714;
	* onSignDigestRequested &#x2714;
* commands 
	* getAll &#x2714;
	* onCommand &#x2714;
* contentSettings	
	* cookies &#x2714;
	* images &#x2714;
	* javascript &#x2714;
	* location &#x2714;
	* plugins &#x2714;
	* popups &#x2714;
	* notifications &#x2714;
	* fullscreen &#x2714;
	* mouselock &#x2714;
	* unsandboxedPlugins &#x2714;
	* automaticDownloads &#x2714;
* contextMenus
	* ACTION_MENU_TOP_LEVEL_LIMIT &#x2714;
	* create &#x2714;
	* update &#x2714;
	* remove &#x2714;
	* removeAll &#x2714;
	* onClicked &#x2714;
* cookies 
	* get  &#x2714;
	* getAll  &#x2714;
	* set  &#x2714;
	* remove  &#x2714;
	* getAllCookieStores  &#x2714;
	* onChanged  &#x2714;
* debugger
	* attach &#x2714;
	* detach &#x2714;
	* sendCommand &#x2714;
	* getTargets &#x2714;
	* onEvent &#x2714;
	* onDetach &#x2714;
* declarativeContent
	* onPageChanged &#x2714;
* desktopCapture
	* chooseDesktopMedia &#x2714;
	* cancelChooseDesktopMedia &#x2714;
* devtools
	* inspectedWindow  &#x2714;
	* eval &#x2714;
	* reload &#x2714;
	* getResources &#x2714;
	* onResourceAdded &#x2714;
	* onResourceContentCommitted &#x2714;







The rest of the objects will be added in the near future so stay tuned :).


##TODO
* Make a seperate file that contains ``chrome.cix`` content and integrate it with [SublimeCodeIntel](https://github.com/SublimeCodeIntel/SublimeCodeIntel)
