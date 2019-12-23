# Microsoft Web Translator bookmarklet

Microsoft Web Translator provides the *Translate this page* service in Bing search results. 

Since Microsoft removed their bookmarklet for the service, I created this simple bookmarklet that uses the service to translate to English.

To add the bookmarklet:
1. Make your bookmarks toolbar visible
2. Select the entire line of code below
3. Drag the selection to a free space in your bookmarks toolbar
4. Rename the bookmarklet to something memorable, like "MWT", to take less space.

Code:

`javascript:void(window.open('https://www.translatetheweb.com/?ref=TVert&from=&to=en&a='+location.href));`

To use the bookmarklet:
1. Browse a web page in a foreign language
2. Click the bookmarklet.

The translation should appear in a new tab (or new page).

If the foreign language is not properly detected, use the *From* menu in the Web Translator toolbar. 

To translate to a different language, use the *To* menu. 

If the bookmarklet stops working, it may be due to Microsoft changing the URL and/or parameters. You can try to fix it yourself, but please let me know.

## Limitations

A site's [Content Security Policy](https://wikipedia.org/wiki/Content_Security_Policy) (CSP) may prevent use of bookmarklets such as this. CSP can be found here in GitHub; at various Mozilla sites; and so on. 

Microsoft's service may be unable to translate some types of page. Examples: 

* https://discourse.mozilla.org/t/topic/15069 translation from Arabic to English results in a blank page
* http://forums.mozillazine.org/viewtopic.php?f=11&t=3055133 translation from English to any language may fail, with an on-screen invitation to try again; retrying may not lead to a translation. 
