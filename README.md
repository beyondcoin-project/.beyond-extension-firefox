# ![image](https://cdn.beyondcoin.io/images/common/dot-beyond.png)

BEYOND-DNS addon for Firefox lets you surf **.beyond**, and OpenNIC domains, and other OpenNIC peered domains.

-------

BEYOND-DNS is a public web resolver. It operates at http://dns.byndnic.com (API description is coming soon).

For the list of OpenNIC support domain names see the [full list](https://wiki.opennic.org/opennic/dot).

--------

## Installing Production Version

Coming Soon!
<!--Download the extension from the Firefox Addons site: [.beyond DNS](https://addons.mozilla.org/en-US/firefox/addon/beyond-dns/)-->

## Installing Debug Version

1. Open Add-ons Manager tab: click on the button with 3 horizontal lines, then click on _Add-ons_ button.
2. Open debug page: click on the icon with a cog, then click on _Debug Add-ons_ item. (This and the previous step can be replaced by direct navigation to `about:debugging#addons`.)
3. In the tab that has just opened, click on _Load Temporary Add-on_ button.
4. Select the extension's directory, then select the manifest file. The directory should contain all files from the [Firefox GitHub repository](https://github.com/beyondcoin-project/.beyond-extension-firefox).
5. Once the open dialog is submitted, a new extension should appear in the list. Press Ctrl+Shift+J - this will open console window.
6. In a regular Firefox tab, navigate to a resource in question (e.g. `bynd.beyond`) - you will notice the console window is populated with lines. Select them and copy to clipboard. Then submit the log along with your [GitHub issue](https://github.com/beyondcoin-project/.beyond-extension-firefox/issues/new).
