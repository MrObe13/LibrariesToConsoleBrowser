# Libraries To Console Browser
Collector of most famous libraries to use in console of browser

To use a library in console of your browser, copy and paste in yuor console the text after name of the library. 

---

# MOMENT.JS
```javascript
fetch('https://cdnjs.cloudflare.com/ajax/libs/moment.js/2.24.0/moment.min.js')
    .then(response => response.text())
    .then(text => eval(text))
    .then(() => { /* now you can use Moment.js in your console */ })
```

🆙 TO UPDATE to last version check it on official site 👉 https://momentjs.com/

••••••••••••••••••••••••••••••••••••••••••••••••••••••••••••••••••••

# LODASH.JS
```javascript
let el = document.createElement('script');
el.src = 'https://cdnjs.cloudflare.com/ajax/libs/lodash.js/4.17.14/lodash.min.js';
document.getElementsByTagName('head')[0].appendChild(el);
```

🆙 TO UPDATE to last version check it on official site 👉 https://lodash.com/

••••••••••••••••••••••••••••••••••••••••••••••••••••••••••••••••••••

# CRYPTO-JS.JS
```javascript
fetch('https://cdnjs.cloudflare.com/ajax/libs/crypto-js/3.1.9-1/crypto-js.min.js')
    .then(response => response.text())
    .then(text => eval(text))
    .then(() => { /* now you can use Crypto.js in your console with Crypto obj */ })
```

🆙 TO UPDATE to last version check it on official site 👉 https://code.google.com/archive/p/crypto-js/downloads
