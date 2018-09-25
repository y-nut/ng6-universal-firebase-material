# ng6-universal-firebase-material

This is a starter template to launch an Angular 6 app to Firebase Hosting with Angular Universal (Static/prerendered site). It is prepared to use Angular Material.

Here is how it works:
1. git clone https://github.com/y-nut/ng6-universal-firebase-material
2. npm i
3. Set up Firebase. I don't remember the order but here are the choices to make
3.1 firebase init; 
3.2 firestore (optional), hosting, functions
3.3 Javascript
3.4 public folder: public
3. npm start
4. In root: cp -a dist/app/. functions/dist/
5. In root: cp -a dist/app/browser/. public/

Note to self
The output folder should be functions/dist/browser and functions/dist/server rather than dist/


Credits to
https://github.com/enten/angular-universal
https://github.com/Angular-RU/angular-universal-full-starter
https://hackernoon.com/deploying-angular-universal-v6-with-firebase-c86381ddd445
