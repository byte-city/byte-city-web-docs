# byte-city web-engine JavaScript docs
* You're able to test your website (html only) using in-game command `byteDevTools`.
* Your website can't be hosted on any third-party websites or servers for security reasons.
* Your website can't contain any content hosted on websites or servers different than imgur.com or byte-city.com for security reasons.
* Your website .html file must be accepted by your local server administration to be available on server.
* Your CSS must be included in HTML `<style>` tag.
* Any script added to your website will be disabled for security reasons.
* RegisterWebsite functions should be contained in `<bytium>` tag.

## Functions - Normal browser

### Bytium.RegisterWebsite(websiteName: string, basicBackground: string, statusBarContentColor: string, homeButtonColor: string)
**Creates new website accessible through Bytium and Wizard app with search and link `websiteName.com`**
* websiteName: should contain only alphabetical characters and dashes.
* basicBackground: must be acceptable by CSS `background` property.
* statusBarContentColor: must be acceptable by CSS `color` property.
* homeButtonColor: must be acceptable by CSS `color` property. Default color is white.

## Functions - Darkweb browser

### Wizard.RegisterWebsite(websiteName: string, basicBackground: string, statusBarContentColor: string, homeButtonColor: string)
**Creates new website accessible through Wizard app with link `websiteName.wizard`**
* websiteName: should contain only alphabetical characters and dashes.
* basicBackground: must be acceptable by CSS `background` property.
* statusBarContentColor: must be acceptable by CSS `color` property.
* homeButtonColor: must be acceptable by CSS `color` property. Default color is white.

## Screen Elements

**Home Button**

![Home Button](https://i.imgur.com/UMvKbJP.png)

**Status Bar**

![Status Bar](https://i.imgur.com/zLXBvTL.png)
