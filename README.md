# northwestern-proxy-for-arc
This repository contains a custom extension to load the Northwestern University VPN bookmarklet button. It is intended for the Arc browser since it handles bookmarks differently, preventing the usual method of adding a bookmarklet. It should work on other browsers, but I have not tested it outside of Arc.

# Installation

# Build it Yourself!
Do you want to build this extension yourself? It's easy! It will only take a couple minutes to follow these steps below:

1) Navigate to the "Installing the Proxy Button" page on the Galter Library website [here](https://galter.northwestern.edu/galterguides?url=https://libguides.galter.northwestern.edu/c.php?g%3D943466%26p%3D6800422).
2) Copy the proxy link mentioned multiple times on the page. Here it is for quick reference:
```JavaScript
javascript:(function(){location.href=%22https://galter.northwestern.edu/exit%3Furl=%22+encodeURI(location.href)})();
```
3) Navigate to the "bookmarklet-to-extension" tool [here](https://sandbox.self.li/bookmarklet-to-extension/).
4) Paste the JavaScript into the `\* drag bookmarklet here *\` text box. Put whatever you want in the `Name` and `Description` text boxes. 
5) Click generate extension to download a zip file of the extension.
6) Unzip the downloaded file.
7) If you do not care about the extension icon, skip to step _insert here later_.
8) 



# Usage
This repository only contains an alternate method of running the Javascript bookmarklet provided by the official [Northwestern page](https://galter.northwestern.edu/galterguides?url=https://libguides.galter.northwestern.edu/c.php?g%3D943466%26p%3D6800422). This method is convenient and necessary for users of the [Arc browser](https://arc.net/) since the prescribed way of creating a bookmarklet does not work in Arc. All information used to create this extension was pulled from publicly available webpages. Access to the VPN is restricted to those with a Northwestern University account and you will be presented with a NetID sign-in page when trying to access the VPN. This sign-in page is controlled by the University and your NetID and password are only sent through University systems. In other words, you are not sharing anything with me when you use this extension. 

While using the Northwestern University VPN, you are tunneling your traffic through proxy servers owned by the University. Just like any other time you connect through the University, it is entirely your responsibility to make sure your traffic complies with all guidelines listed in the [Appropriate Use of Electronic Resources](https://policies.northwestern.edu/docs/appropriate-use-policy-final.pdf) policy and any other relevant institutional rules. If you are unsure about some computing policy, please ask the relevant administrative contact at Northwestern University. I will not answer any questions related to "is ______ allowed on the VPN?" It is safest to assume all your traffic is visible to the IT Department when it is sent through University WiFi or proxy. 
