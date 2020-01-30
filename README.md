# mapbox_search_flutter

[![Pub](https://img.shields.io/pub/v/mapbox_search_flutter)](https://pub.dartlang.org/packages/mapbox_search_flutter) <a href="https://flutterawesome.com/a-flutter-package-for-place-search-using-mapbox-api-and-for-static-map-image/">
   <img alt="Awesome Flutter" src="https://img.shields.io/badge/Awesome-Flutter-blue.svg?longCache=true&style=flat-square" />
</a>

#### A Flutter package for place search using MapBox Api

# Installing

Add the following to your `pubspec.yaml` file:

    dependencies:
      mapbox_search_flutter: any

# Example

    MapBoxPlaceSearchWidget(
            popOnSelect: true,
            apiKey:
                "API KEY",
            limit: 10,
            searchHint: 'Your Hint here',
            onSelected: (place) {},
            context: context,
        )

# Screenshots

## Search Widget

<img src="https://github.com/ketanchoyal/mapbox_search/raw/dev/Screenshots/search2.png" alt="Demo"/>

<img src="https://github.com/ketanchoyal/mapbox_search/raw/dev/Screenshots/search1.png" alt="Demo"/>

## Getting Started

This project is a starting point for a Dart
[package](https://flutter.dev/developing-packages/),
a library module containing code that can be shared easily across
multiple Flutter or Dart projects.

For help getting started with Flutter, view our 
[online documentation](https://flutter.dev/docs), which offers tutorials, 
samples, guidance on mobile development, and a full API reference.
