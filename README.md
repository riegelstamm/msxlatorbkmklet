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
