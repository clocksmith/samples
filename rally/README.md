# Rally

An app that manages personal finance data. It showcases custom tabs, custom painted widgets,
and custom animations.

**This sample is not currently in a finished state. We're in the process
of building it out.**

## Goals

* Show how to customize a tab bar.
* Show how to create reusable custom widgets with composition and custom painting.
* Show how to create an app with tabs and child navigation screens.

## The important bits

### `/charts/*`

These are the custom charts. The is a circle chart and line chart are custom painters,
while the single vertical bar chart is a simple composition of boxes.

### `/sections/*`

These are the main sections for the tab views and the child screen with the details and line chart.
The financial entity is a reusable screen that is the base for the accounts, bills, and budgets
screens.

## Questions/issues

If you have a general question about any of the techniques you see in
the sample, the best places to go are:

* [The FlutterDev Google Group](https://groups.google.com/forum/#!forum/flutter-dev)
* [The Flutter Gitter channel](https://gitter.im/flutter/flutter)
* [StackOverflow](https://stackoverflow.com/questions/tagged/flutter)

If you run into an issue with the sample itself, please file an issue
in the [main Flutter repo](https://github.com/flutter/flutter/issues).