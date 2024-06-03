A script to run on your browser console to hide all mesages from a specific user.

# Script
```Javascript
function hideSetton() {
    var elements = document.getElementsByClassName('person');
    for(var i = 0; i < elements.length; i++){
        elements[i].style.display = 'none';
    }
}
var observer = new MutationObserver(hideSetton);
observer.observe(document, { childList: true, subtree: true });

```

# How to use
1. You will need to get the user's class
2. Change 'person' on the script to the users class
3. Paste it on the browser's console
4. Done!
