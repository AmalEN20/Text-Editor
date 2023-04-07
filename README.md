# PWA Text Editor

## Description

This is a text editor Progressive Web Application that runs in the browser where user can create notes or code snippets with or without an internet connection. The content in the text editor is saved with IndexedDB so that it can be retrieved when the app is closed and reopened. User can also download the web app as an icon on desktop. The app is using a package called `idb` to store and retrieve data and using workbox service worker to have static assets pre cached upon loading along with subsequent pages and static assets.

## Installation
- Install [Node.js v16](https://nodejs.org/en/blog/release/v16.16.0/) and [npm](https://www.npmjs.com/)
- Navigate to the root directory and install npm packages:
  ```
  npm install
  ```
  ## Usage
- Execute the app and run the server:
  ```
  npm run start
  ```
## Screenshots
  - Index page
  ![image](https://user-images.githubusercontent.com/116880367/230519266-30115bfc-800a-468c-b02e-997fd7cd301b.png)
  
  - Install app
  ![image](https://user-images.githubusercontent.com/116880367/230519336-050db053-6fe5-45bd-ad41-6b701298cef5.png)

  - App Manifest
  ![image](https://user-images.githubusercontent.com/116880367/230519385-a7a2e282-edc4-4123-aff6-6f88e9829d4b.png)

  - Registered Service Worker
  ![image](https://user-images.githubusercontent.com/116880367/230519443-eb951ae2-2524-4c25-8795-d32298e32e47.png)
  
  - IndexedDB
  ![image](https://user-images.githubusercontent.com/116880367/230519490-73431ed0-0713-4ab9-9bc9-676669f8de12.png)

