# invoice-generator-uninstall

Opens when someone removes the Invoice Generator extension. One question —
"Why have you deleted the app?" — in an embedded Google Form. Answered by a small
share of leavers, and that share is the cheapest source of "what to fix next"
this project has.

Wired through `chrome.runtime.setUninstallURL` in the extension's service worker.
