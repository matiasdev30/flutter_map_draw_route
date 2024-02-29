# Driving Route Calculator using Flutter Map and OpenStreetMap

This project provides a simple example of calculating a driving route between two points using Flutter Map and OpenStreetMap.

https://github.com/matiasdev30/flutter_map_draw_route/assets/50122963/62872f51-625d-400a-bdac-5a6336dd47cf

## Installation

Make sure you have Flutter installed. Then, clone the repository and navigate to the project directory.

```bash
git clone https://github.com/matiasdev30/flutter_map_draw_route/
```

Install the required dependencies using Flutter's package manager:

```bash
flutter pub get
```

## Dependencies

This project utilizes the following packages:

- **flutter_map**: ^3.1.0 - A Flutter package for embedding interactive maps directly within a Flutter widget.
- **latlong2**: ^0.8.1 - A package for representing and manipulating coordinates (latitude and longitude) in Dart.
- **http**: ^0.13.5 - A package for making HTTP requests in Dart.
- **cupertino_icons**: ^1.0.2 - Default icons for Cupertino-style apps.
- **open_route_service**: ^1.2.2 - A Dart package for accessing the OpenRouteService API, which provides routing services.

## Usage

To use this example in your Flutter project, follow these steps:

1. Import the required packages into your Dart file:

```dart
import 'package:flutter/material.dart';
import 'package:flutter_map/flutter_map.dart';
import 'package:latlong2/latlong.dart';
import 'package:http/http.dart' as http;
import 'package:open_route_service/open_route_service.dart';
```

2. Copy the necessary code from the example provided in this repository to your project.

3. Modify the code as needed to integrate it into your application.

## Documentation

For detailed documentation on each package used in this project, refer to the following resources:

- [flutter_map](https://pub.dev/packages/flutter_map)
- [latlong2](https://pub.dev/packages/latlong2)
- [http](https://pub.dev/packages/http)
- [cupertino_icons](https://pub.dev/packages/cupertino_icons)
- [open_route_service](https://pub.dev/packages/open_route_service)

## License

This project is licensed under the [MIT License](LICENSE).

## Contributing

Contributions are welcome! Feel free to open an issue or submit a pull request to improve this project.
