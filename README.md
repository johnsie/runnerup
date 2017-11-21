TargetRunner - Amazefit Edition
========


A fork of of the Runner Up running app,  with a front end made specifically for Amazefit watches


The Amazefit watch currently runs a custom version of Android 5.01 (not wear) so this project will focus on that platform. I'll mostly be modifying the xml files for the user interface rather than messing around too much with the back end of the app.


[![Build Status(Under Construction)](https://targetrunner.com/amazefit)](https://targetrunner.com/amazefit)



## Watch Features

* Android 5.1
* WIFI
* GPS
* Heart Monitor (Not sure if I'll have access to this data)
* Bluetooth



## Short Term Todos

* Set up the project on development machine (Done)
* See if apk will run out of the box on the amazefit watch (Todo)
* Make any adjustments necessary for the apk to be able to run. Eg. remove any dependencies like Play Services (Todo)
* Amend GUI to that something fits on the watch screen (Todo)
* Set up basic website with project management tool (Todo)




## Planned Features

* GPL (Based on Runner Up, which is designed for Phones and wear devices).
* Even more mediocre GUI developed by myself and aimed at the Amazefit Smartwatch.
* Audio Cues from Runner Up (distance, pace etc)
* Sync to various platforms using Runner Ups back end.
* Training plans (longterm goal)




## Release
Releases can be downloaded either:

* on the [Direct APK Download](https://targetrunner.com/amazefit).



## Build
Depending on your IDE, see according documentation:

* for Android Studio, please see [how to build with Android Studio](Documentation/howto-build-with-android-studio.txt).
* for NetBeans IDE, please see [how to build with NetBeans IDE](Documentation/howto-build-with-netbeans-ide.txt).
* for Eclipse, please see [how to build with Eclipse](Documentation/howto-build-with-eclipse.txt). __UPDATE: Eclipse is currently broken__.

## Dependencies
* [Ant Plugin](http://www.thisisant.com): Used to retrieve heart rate monitor data.
* [GraphView](https://github.com/jjoe64/GraphView.git): Used to plot data in a nicely way.
* [MapBox](https://mapbox.com): Used to display map to the user.
* We will atttempt to remove the Google Play Services dependencies as this watch does not support Google Wear

## Contributing

Patches, forks, pull requests, suggestions or harsh flame is welcome! Please
Please read the [contributing guidelines](CONTRIBUTING.md).

### How can I contribute?

Thanks for asking! You can check [TODO list](TODO.md) and [open issues](https://github.com/jonasoreland/runnerup/issues). You can also work on your own wishes :-).

### Translations

<img border="0" src="https://www.transifex.com/projects/p/runner-up-android/resource/stringsxml/chart/image_png"/><br/><a target="_blank" href="https://www.transifex.com/projects/p/runner-up-android/resource/stringsxml/"><img border="0" src="https://ds0k0en9abmn1.cloudfront.net/static/charts/images/tx-logo-micro.646b0065fce6.png"/></a>

Interested in helping to translate RunnerUp? Contribute [on Transifex](https://www.transifex.com/projects/p/runner-up-android).

## License
This project is under GNU GPL v3. See [LICENSE](LICENSE.md) for more information.

## Donations
If your already donate to <a href="http://www.unhcr.org">UNHCR</a>, <a href="http://www.unicef.org/">UNICEF</a> and/or other important things, you might donate using paypal <a href="https://www.paypal.com/cgi-bin/webscr?cmd=_xclick&business=runnerup%2eandroid%40gmail%2ecom&lc=US&item_name=RunnerUp&button_subtype=services&currency_code=EUR&tax_rate=25%2e000&bn=PP%2dBuyNowBF%3abtn_buynow_LG%2egif%3aNonHosted"><img src="https://www.paypalobjects.com/en_US/i/btn/btn_donate_SM.gif" alt="[paypal]" /></a>.
