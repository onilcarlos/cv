From https://favicon.io/favicon-converter/

- Generate the favicon.ico from your image: ![Image from PNG to .ico](/favicon_io/favicon-32x32.png)
- Download and Unzip the file favicon_io.zip
- Upload the directory **/favicon_io/** in your root directory with the follow files:

* android-chrome-192x192.png
* android-chrome-512x512.png
* apple-touch-icon.png
* favicon-16x16.png
* favicon-32x32.png
* favicon.ico
* site.webmanifest

Add this code to the head of your index o default templeate

```
<link rel="shortcut icon" href="{{ site.baseurl }}/favicon_io/favicon.ico">
<link rel="apple-touch-icon" sizes="180x180" href="{{ site.baseurl }}/favicon_io/apple-touch-icon.png">
<link rel="icon" type="image/png" sizes="32x32" href="{{ site.baseurl }}//favicon_io/favicon-32x32.png">
<link rel="icon" type="image/png" sizes="16x16" href="{{ site.baseurl }}//favicon_io/favicon-16x16.png">
<link rel="manifest" href="{{ site.baseurl }}//favicon_io/site.webmanifest">
```


