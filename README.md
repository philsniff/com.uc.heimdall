# Heimdall - Let Homey watch over your home

This app enables you to use your Homey as a surveillance system.
All detected motion and open/closed doors and windows on selected sensors will be seen by Heimdall. All these events will be logged and when Heimdall is in a Surveillance Mode the alarm will be triggered.

## How do I get it to work?
* Add a Surveillance Mode button.
* Select the devices to monitor on the settings page. 
* Add flows to activate and deactivate the desired Surveillance Mode.
* Add a flow with the desired actions when the alarm is triggered.
* Add a flow to deactivate the alarm.
* Add an Alarm Off Button.
* Detailed instructions can be found on the Instructions tab in the apps settings.

## Known issues
* The app crashes when the app page in Homeys settings is opened while the app is initializing.

## Planned features
- [X] [Make the Reason tag 'human friendly'](https://github.com/daneedk/com.uc.heimdall/issues/3)
- [X] Redesign the Dashboard.
- [X] Add 'The alarm is deactivated' flow card.
- [X] [Look into cancelling a tripped sensor when a delay countdown is active.](https://github.com/daneedk/com.uc.heimdall/issues/5)
- [ ] [Let Homey tell you what's happening.](https://github.com/daneedk/com.uc.heimdall/issues/6)
- [ ] Look into adding other sensors like smoke/heat/flood.
- [ ] ..

## Version 0.1.7
* Bugfix for [bug introduced in 0.1.6](https://github.com/daneedk/com.uc.heimdall/issues/8)
* Added Homekit compatibility for [Homeykit](https://apps.athom.com/app/com.swttt.homekit) app
* Start with Speech output support

## Version 0.1.6
* Cancel trigger from a tripped sensor when a delay countdown is active
* More translations

## Version 0.1.5 ALPHA
* Researching Homekit compatability

## Version 0.1.4
* Added colors to History view
* Added 'The alarm is deactivated' flow card
* More translations

## Version 0.1.3
* Improved History view
* Improved translations

## Version 0.1.2
* Reason tag 'human friendly'
* States in history 'human friendly'

## Version 0.1.1
* Code cleanup

## Version 0.1.0
* Initial public beta version

Thanks to all testers of the alpha version!

Please remember, Heimdall is not intended to be a full blown security system.

## Donate
If you like the app, consider buying me a beer!  
[![Paypal donate][pp-donate-image]][pp-donate-link]

[pp-donate-link]: https://www.paypal.me/daneedekruyff
[pp-donate-image]: https://www.paypalobjects.com/webstatic/en_US/i/btn/png/btn_donate_92x26.png