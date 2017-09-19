# Microsoft / Bing Translator Bookmarklet
Since Microsoft has removed their bookmarklet for their Microsoft Translator, which is also used by Bing, I created this simple bookmarklet that does the same thing.

To add it to your web browser:
1. Make sure your bookmarks toolbar is visible
2. Highlight the entire line of code
3. Drag the code somewhere on your bookmarks toolbar
4. Afterwards you can rename it to something you'll remember, like "MT", so it doesn't take up so much space

javascript:void(window.open('http://www.microsofttranslator.com/bv.aspx?from=&to=en&a='+location.href));

To use the bookmarklet:
1. Navigate to a web page in a different language
2. Click the "MT" button, or whatever you named it
3. A new window or tab should open that will translate the page into English. 
4. If you want to translate into a different language, just pick a different language in the target language dropdown
5. Microsoft Translator should automatically detect the from language, but if it doesn't, just change it in the from language dropdown

If the bookmarklet stops working, it's probably because Microsoft has changed the Translator URL and/or paramaters. You can try to fix it yourself, but please let me know.
