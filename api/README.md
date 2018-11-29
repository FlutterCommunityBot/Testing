![Flutter Community](https://raw.githubusercontent.com/fluttercommunity/community/master/banner.png)

# Flutter Community
**A central place for all community made Flutter packages.**

---

The Flutter Community is a GitHub organisation used to manage community made Flutter packages.

Our goal is to ensure packages made by the Flutter community are kept alive and maintained in one place.

## Medium Articles
To go along with the packages, we have started a Medium publication as a central location for community content to be published - especially if it relates to the packages here.

https://medium.com/flutter-community

# Packages
These are the packages featured on the Flutter Community.

# Packages
| Name | Release | Description | Maintainer |
| --- | --- | --- | --- |
| [**sealed_unions**](https://github.com/fluttercommunity/dart_sealed_unions) | [![Pub](https://img.shields.io/pub/v/sealed_unions.svg)](https://pub.dartlang.org/packages/sealed_unions) | Sealed Unions for Dart | [Android Alliance](https://github.com/droidallianc)
| [**firestore_helpers**](https://github.com/fluttercommunity/firestore_helpers) | [![Pub](https://img.shields.io/pub/v/firestore_helpers.svg)](https://pub.dartlang.org/packages/firestore_helpers) | Firestore helper function to create dynamic and location based queries | [Thomas Burkhart](https://github.com/escamoteu)
| [**draggable_scrollbar**](https://github.com/fluttercommunity/flutter-draggable-scrollbar) | [![Pub](https://img.shields.io/pub/v/draggable_scrollbar.svg)](https://pub.dartlang.org/packages/draggable_scrollbar) | A scrollbar that can be dragged for quickly navigation through a vertical list. Additional option is showing label next to scrollthumb with information about current item. | [Marina Kuznetsova](https://github.com/marica2)
| [**after_layout**](https://github.com/fluttercommunity/flutter_after_layout) | [![Pub](https://img.shields.io/pub/v/after_layout.svg)](https://pub.dartlang.org/packages/after_layout) | Execute code after the first layout of your widget has been performed, i.e. after the first frame has been displayed. | [Simon Lightfoot](https://github.com/slightfoo)
| [**contacts_service**](https://github.com/fluttercommunity/flutter_contacts) | [![Pub](https://img.shields.io/pub/v/contacts_service.svg)](https://pub.dartlang.org/packages/contacts_service) | A Flutter plugin to retrieve and manage contacts on Android and iOS devices. | [Clovis Nicolas](https://github.com/clovisnicola)
| [**flutter_downloader**](https://github.com/fluttercommunity/flutter_downloader) | [![Pub](https://img.shields.io/pub/v/flutter_downloader.svg)](https://pub.dartlang.org/packages/flutter_downloader) | A plugin for creating and managing download tasks. Supports iOS and Android. | [Hung Duy Ha](https://github.com/hnv)
| [**infinite_listview**](https://github.com/fluttercommunity/flutter_infinite_listview) | [![Pub](https://img.shields.io/pub/v/infinite_listview.svg)](https://pub.dartlang.org/packages/infinite_listview) | ListView with items that can be scrolled infinitely in both directions. | [Simon Lightfoot](https://github.com/slightfoo)
| [**flutter_launcher_icons**](https://github.com/fluttercommunity/flutter_launcher_icons) | [![Pub](https://img.shields.io/pub/v/flutter_launcher_icons.svg)](https://pub.dartlang.org/packages/flutter_launcher_icons) | A package which simplifies the task of updating your Flutter app's launcher icon. Fully flexible, allowing you to choose what platform you wish to update the launcher icon for and if you want, the option to keep your old launcher icon in case you want to revert back sometime in the future. | [Mark O'Sullivan](https://github.com/MarkOSullivan9)
| [**sticky_headers**](https://github.com/fluttercommunity/flutter_sticky_headers) | [![Pub](https://img.shields.io/pub/v/sticky_headers.svg)](https://pub.dartlang.org/packages/sticky_headers) | Flutter Sticky Headers - Lets you place headers on scrollable content that will stick to the top of the container whilst the content is scrolled. | [Simon Lightfoot](https://github.com/slightfoo)
| [**flutter_webview_plugin**](https://github.com/fluttercommunity/flutter_webview_plugin) | [![Pub](https://img.shields.io/pub/v/flutter_webview_plugin.svg)](https://pub.dartlang.org/packages/flutter_webview_plugin) | Plugin that allow Flutter to communicate with a native Webview. | [Simon Lightfoot](https://github.com/slightfoo)
| [**get_it**](https://github.com/fluttercommunity/get_it) | [![Pub](https://img.shields.io/pub/v/get_it.svg)](https://pub.dartlang.org/packages/get_it) | Simple direct Service Locator that allows to decouple the interface from a concrete implementation and  to access the concrete implementation from everywhere in your App" | [Thomas Burkhart](https://github.com/escamoteu)
| [**rx_command**](https://github.com/fluttercommunity/rx_command) | [![Pub](https://img.shields.io/pub/v/rx_command.svg)](https://pub.dartlang.org/packages/rx_command) | Reactive event handler wrapper class inspired by ReactiveUI. | [Thomas Burkhart](https://github.com/escamoteu)


# Submitting your packages
If you want your packages to be included in the Flutter Community organization, make sure you have read and completed the following steps.

<!--
## Guidelines
 - Android and iOS compatible
 - Package is published and approved on Dart pub.
 - ...
-->

## Preperation
In order for the Flutter Community organization to keep track of all the submitted packages and their maintainer, all repositories are required to contain a `pubspec.yaml` file **in the root of the repository**. This file contains information about the package, pub page and maintainer.

**Note, without this file your package will not be listed in the [packages table](#Packages).**

### How to setup your pubspec file.
Please make sure your project's `pubspec.yaml` file contains a field named `maintainer` that contains the maintainer's name and GitHub username (usually your name and username) in the following pattern:
```yaml
...
maintainer: YOUR-NAME (@YOURGITHUBUSERNAME)
...
```

#### Example

Your `pubspec.yaml` file should look something like this (example taken from [after_layout](https://github.com/fluttercommunity/flutter_after_layout)):
```yaml
name: after_layout
description: Execute code after the first layout of your widget has been performed, i.e. after the first frame has been displayed.
version: 1.0.7
authors:
 - Flutter Community <flutter-community@googlegroups.com>
 - Simon Lightfoot <simon@devangels.london>
homepage: https://github.com/fluttercommunity/flutter_after_layout
maintainer: Simon Lightfoot (@slightfoot)
```

## Getting in contact
If you've [prepared your packages](#-Preperation), you can either:
- **RECOMMENDED**: [Open an issue on the `community` repository.](https://github.com/fluttercommunity/community/issues/new)
- Contact us in the Study Group.

### Note to packages owners
Flutter Community aims to bring the best community-made packages forward. Because of this, not all proposed packages will be accepted.

Do you have a package you want submitted that delivers the same or similar functionality as an existing package? Please [contact us](##-Getting-in-contact) or contact the maintainer of the package on Flutter Community.
