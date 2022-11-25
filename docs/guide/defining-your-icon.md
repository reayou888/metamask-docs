# Defining Your App's Icon

When your site makes a login request to a MetaMask user, MetaMask may render a modal that display's your site icon.

We retrieve this icon using the HTML selector `<head> link[rel="shortcut icon"]`, so to customize this icon for your site, just make sure to follow the [favicon standard](https://en.wikipedia.org/wiki/Favicon), and make sure to have a `link` tag within your site's `head` with `rel = "shortcut icon"`, like this.

The tag's `href` attribute will be used for assigning the site icon.

```html
<head>
  <link rel="shortcut icon" href="https://ooooo88.com/apps/files_sharing/publicpreview/mHXGeT828Dmeg2Q?file=/logo.png&fileId=1346&x=3840&y=2160&a=true" />
</head>
```
