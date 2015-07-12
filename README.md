# ionic-playground
##Resources
1. [Ionic Install Guide](http://ionicframework.com/getting-started/)
2. [What is this thing?](http://blog.ionic.io/where-does-the-ionic-framework-fit-in/)

##Need to Know
- Ionic is kind of like a twitter boostrap equivalent for hybrid apps. It makes style and design patterns easily accessible and lets devs get an app looking pretty, quickly. It uses HTML5, CSS, and JS, so is therefore portable to any platform if you then use something like [Phonegap's](http://phonegap.com/) to deploy it to a wide range of mobile devices.

####tl;dr - Tools exist to package up HTML, CSS, and JS into multi-platofrm native apps. Use Ionic to make those apps look pretty, quickly.

##Steps to Getting Shit on the Screen
1. Install [node.js](https://nodejs.org/)
2. Install XCode
3. Install [Ionic Command line tools](https://www.npmjs.com/package/ionic)
4. Install ionic ```npm install -g cordova ionic```
5. Create an app, name it, and give it a template ```ionic start myApp tabs```
6. Run it:
    ```ruby
      $ cd myApp
      $ ionic platform add ios
      $ ionic build ios
      $ ionic emulate ios
    ```
