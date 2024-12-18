properties we can add to manifest
1.name- this will be fetched by browser in multiple places eg: splash screen
2.short_name: name under app icon
3.start_url: which page to load in startup on click home screen icon
4.scope: which pages are included in PWA experience
5.display:"standalone" - standalone make the app look like native app
6.background_color: bg color while loading
7.theme_color: eg. on top bar in task switcher
8.description: description of the app
9.dir: read direction of app
10.lang: main language of app
11:orientation:"portrait-primary" restrict the orientation for the user
12.icons: array of app icons [{src,type,sizes}]
13: related_application: if you have alternative native application

check the manifest.json in public folder
