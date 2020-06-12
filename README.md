[![Pub](https://img.shields.io/pub/v/mapbox_search_flutter)](https://pub.dartlang.org/packages/mapbox_search_flutter) [![HitCount](http://hits.dwyl.com/ketanchoyal/mapbox_search_flutter.svg)](http://hits.dwyl.com/ketanchoyal/mapbox_search_flutter)
 <a href="https://flutterawesome.com/a-flutter-package-for-place-search-using-mapbox-api-and-for-static-map-image/">
   <img alt="Awesome Flutter" src="https://img.shields.io/badge/Awesome-Flutter-blue.svg?longCache=true&style=flat-square" />
</a>


# About 

This package provides some widgets to use in conjunction to [mapbox_search](https://pub.dev/packages/mapbox_search) library. 

Also, it contains an static map image generator 😆.


# Installing

Add the following to your `pubspec.yaml` file:

    dependencies:
      mapbox_search_flutter: any

# Example
```dart
MapBoxPlaceSearchWidget(
        popOnSelect: true,
        apiKey: "API KEY",
        limit: 10,
        searchHint: 'Your Hint here',
        onSelected: (place) {},
        context: context,
    )
```

# Screenshots

## Search Widget

<img src="https://github.com/ketanchoyal/mapbox_search/raw/dev/Screenshots/search2.png" alt="Demo"/>

<img src="https://github.com/ketanchoyal/mapbox_search/raw/dev/Screenshots/search1.png" alt="Demo"/>