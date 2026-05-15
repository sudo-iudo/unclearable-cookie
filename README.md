![demo](./cookie-refuse-to-die.gif)

#### How it works

The script stores a persistent unique ID in memory and continuously rewrites the same cookie every millisecond. Even if the cookie is manually deleted, the page instantly recreates it from the in-memory value while the tab remains open.

#### Steps to reproduce

1. Open the [page](https://sudo-iudo.github.io/unclearable-cookie) in Google Chrome, Safari, or Firefox
2. Clear the cookies using the popup from the address bar
3. Reload the page

#### Disclaimer

This method works in Chrome, Safari, and Firefox. It does not work if the cookies are cleared while the tab is closed. However, it still bypasses the most common cookie-clearing flow in the UI.

#### Legal Disclaimer

This proof of concept is intended for security research and demonstration purposes only. Using similar techniques in production to circumvent user intent or privacy controls may violate applicable laws, platform policies, or regulations.
