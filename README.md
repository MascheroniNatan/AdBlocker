# AdBlocker

AdBlocker is a simple Google Chrome extension that blocks http requests from major ad sites.

## Installation

Follow the [cnet guide](https://www.cnet.com/how-to/how-to-install-chrome-extensions-manually/) to understand how to install the extension.

## Update Sites To Be Blocked

Change newsitetobeblocked.com to your own domain.

Line 7 of "background.js".

```javascript
 urls: [
            "*://*.doubleclick.net/*",
            "*://partner.googleadservices.com/*",
            "*://*.googlesyndication.com/*",
            "*://*.google-analytics.com/*",
            "*://creative.ak.fbcdn.net/*",
            "*://*.adbrite.com/*",
            "*://*.exponential.com/*",
            "*://*.quantserve.com/*",
            "*://*.scorecardresearch.com/*",
            "*://*.zedo.com/*",
            "*://*.newsitetobeblocked.com/*"
       ]
```

## Contributing
Pull requests are welcome. Feel free to open an "Issue" tab for any problem. 

## License
[GNU General Public License v2.0](https://choosealicense.com/licenses/mit/)
