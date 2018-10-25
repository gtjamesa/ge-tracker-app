# GE Tracker App

This repository will be used for issue tracking for the [GE Tracker](https://www.ge-tracker.com) mobile app.

The app is currently in closed-beta and will be publicly available very soon.

[https://www.ge-tracker.com/mobile](https://www.ge-tracker.com/mobile)

## Installation

### Android

Please visit the URL for your group and make sure you’re signed in with the Google account you have been invited on. Accept the invite, then there will be a link to download the app. 

* Alpha: [https://play.google.com/apps/testing/com.getracker](https://play.google.com/apps/testing/com.getracker)

* Beta: [https://play.google.com/apps/testing/com.getracker](https://play.google.com/apps/testing/com.getracker) 

### iOS

First, you will need to download the "TestFlight" app. Once this is downloaded, visit the TestFlight email you have been sent which will give you a code to enter into the app. You can then download the GE Tracker app via TestFlight.

## Latest Releases

<table>
  <tr>
    <td>Internal</td>
    <td>Alpha</td>
    <td>Beta</td>
    <td>Production</td>
  </tr>
  <tr>
    <td>0.0.18</td>
    <td>0.0.18</td>
    <td>0.0.18</td>
    <td>-</td>
  </tr>
</table>

## Release Notes

**0.0.18**

* Fixed bug when rendering graph in production only
* Added Bugsnag error tracking 

**0.0.17**

* Added Profit Tracker:
    * Graph
    * Table
    * Most Profitable Items

**0.0.16**

* Graphs can now be zoomed
* Graphs render faster
* RS Updates display on the graphs
* Price data can be long pressed to stay on the graph until long pressed again

**0.0.15**

* Bug fixes
* Added loading indicator to item lists
* Added item count to dashboard toggle lists
* Favourite item stars are working
* Fixed issue with fresh accounts crashing on dashboard

**0.0.14**

* Increased font size input fields by 33%
* Added show/hide toggle to password field
* Bug fixes
* Graph previews and loading added to item screen
* Graph header added
* Added native dashboard

**0.0.13**

* (internal release bugfix)

**0.0.12**

* Fixed number formatting not working on Android
* Added native item screen
* All flip finder + money making screens are now added
* Deep linking has been added so "*.ge-tracker.com" links will open inside the app
* Item icon images are downloaded from CDN and cached onto the device
* Added a provisional version of the native graphs

**0.0.11**

* Fixed Menu Modals not returning to the original application state after adding native authentication flow
* Reduced auth background image overlay to 20% (from 30%)
* Add Pull to Refresh when viewing lists (Highest Margins, High Volume etc.) and items
* Fixed an error when viewing your own profile
* Created ItemList and ListItem components to render lists
* All Flip Finder Menus are native and the majority of Money Making features have been converted to native functionality

**0.0.10**

* Tested on Android 8.0
* Device platform is correctly registered against GE Tracker account
* Back button presses are consistent across hardware (Android) and the header in the App
* Login flow is native and will persist (even with 2FA enabled)
* Natively used font has been changed to Proxima Nova
* Added Android ‘ACCESS_NETWORK_STATE’ permission

**0.0.9**

* Unfinished menus will show as under construction
* Fixed bug for Android >= 7.0 not loading graphs correctly
* Added an unstyled search screen

**0.0.8**

* Arrow in header has been changed (looks nicer)
* Font has been updated to Proxima Nova
* Added Logout link to "My Account" menu
* Changed NavBar border to a darker shade of grey
* Item graphs open separately in a new screen to ensure the flow of the app
* Redux integration has been rewritten slightly - added some middleware
* Device is attached to User account

**0.0.7 (iOS only)**

* Fixed iOS back button having to be pressed 3 times
* GE Tracker logo and Header navigation buttons scale with the device width
* Navigation menus should come from the side instead of the bottom, and no longer act as a modal
* Fixed FI/SI panels closing when clicking inside them (incl. Favourite Star)

**0.0.6**

* Fixed 404s on Profit Tracker menu
* Added start/finished loading animation to the GTWeb Component
* User icon in the header opens the My Account menu
* Changed the NavBar to contain: Dash, Items, Money, Profit, More
* Added a "Back" button in the Header
* Side menu has been removed from all pages

**0.0.5**

* Bug fixes
* Added bottom NavBar and Main Menu, both hooked into the WebView and Native Navigation

**0.0.4**

* First release with the correct package name (versions 0.0.1 - 0.0.3 were testing)
* Header has been converted to Native Android/iOS