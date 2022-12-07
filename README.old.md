# PWA-test
pwa-test
If you have already existing project and you want to migrate to the new versions of CRA, you can follow this steps:

1 Create somewhere on your computer a new CRA with the service worker template:

npx create-react-app my-app --template cra-template-pwa

2 Copy the service-worker.js from the new created app into your src directory

3 Copy the "workbox-*" dependencies from the package.json into your package.json dependencies

4 (Optional) If you want web-vitals, copy the web-vitals dependency from package.json into your package.json

and don't forget to run again 'yarn install' or 'npm install'

Thats it
