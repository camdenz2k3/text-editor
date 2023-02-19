# Just Another Text Editor
## Description
This single page app is a text editor that runs in the browser and offline that meets the PWA criteria 

Technical criteria the application meets:
- Uses IndexedDB to create an object store and includes both GET and PUT methods
- The application works without an internet connection
- Automatically saves content inside the text editor when the DOM window is unfocused
- Bundled with webpack
- Create a service worker with workbox that Caches static assets
- The application should use babel in order to use async / await
- Application must have a generated manifest.json using the WebpackPwaManifest plug-in
- Can be installed as a Progressive Web Application

## User Story
```
AS A developer
I WANT to create notes or code snippets with or without an internet connection
SO THAT I can reliably retrieve them for later use
```
## Visual
Here is a picture of the deployed page:
![deployed](/Assets/deployed.png)
And this is what the application looks like if you install it:
![downloaded](/Assets/downloaded.png)
## Deployed Link
https://jat-editor.herokuapp.com/