# Content Blocking Lists

This repo will soon be deprecated and superseded by https://github.com/duckduckgo/privacy-configuration 


These files are served: https://duckduckgo.com/contentblocking/...

**Adding unprotected entries**

To add a manual unprotected entry update the top section of trackers-unprotected-temporary.txt.

**Whitelist is deprecated**

Please note the whitelist file has been deprecated and is only being used by the Safari extension, it will be removed soon after that.

**Adding new broken canvas websites**

If breakage is detected of a website due to Canvas fingerprint protection there are two mechanisms to remove the protection:

- broken-canvas-scripts.txt - Line separated regular expressions to match against scripts loaded into a web page.
- broken-canvas-sites.txt - First party pages that are exempt of protection.

## Contributing
You may open an issue in this GitHub repo or open a pull request.
