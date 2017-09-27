# Notes

Using Electron and [Electron Builder](https://github.com/electron-userland/electron-builder). Simply Follow the quick setup guide for electron builder for help.

Play with the config.xml: https://cordova.apache.org/docs/en/latest/config_ref/

Plugins can have settings in config.xml, splashscreen editing: https://cordova.apache.org/docs/en/latest/reference/cordova-plugin-splashscreen/

May only need the cart.js. Convert the Cart.html into an angular component and be chilling. And be sure to include the cart.js in index.html

Deploying with Ionic: https://ionicframework.com/docs/intro/deploying/

Generating Resources and icons: https://ionicframework.com/docs/cli/cordova/resources/

crosswalk for performance: https://www.techiediaries.com/mobiledev/boosting-ionic2-apps-performance-with-crosswalk/


This is a starter template for [Ionic](http://ionicframework.com/docs/) projects.

## How to use this template

*This template does not work on its own*. The shared files for each starter are found in the [ionic2-app-base repo](https://github.com/ionic-team/ionic2-app-base).

To use this template, either create a new ionic project using the ionic node.js utility, or copy the files from this repository into the [Starter App Base](https://github.com/ionic-team/ionic2-app-base).

### With the Ionic CLI:

Take the name after `ionic2-starter-`, and that is the name of the template to be used when using the `ionic start` command below:

```bash
$ sudo npm install -g ionic cordova
$ ionic start myBlank blank
```

Then, to run it, cd into `myBlank` and run:

```bash
$ ionic cordova platform add ios
$ ionic cordova run ios
```

Substitute ios for android if not on a Mac.
