# QR-generator-clean-code-architecture

## Folder Structure
```
my_flutter_project/
├── lib/
│   ├── data/
│   │   ├── datasources/
│   │   │   ├── remote_data_source.dart
│   │   │   └── local_data_source.dart
│   │   ├── repositories/
│   │   │   ├── repository.dart
│   │   │   └── repository_impl.dart
│   │   └── models/
│   │       ├── domain_model.dart
│   │       ├── data_model.dart
│   │       └── mapper.dart
│   ├── domain/
│   │   ├── entities/
│   │   │   └── entity.dart
│   │   ├── repositories/
│   │   │   └── repository.dart
│   │   ├── usecases/
│   │   │   └── usecase.dart
│   │   └── value_objects/
│   │       └── value_object.dart
│   ├── presentation/
│   │   ├── pages/
│   │   │   └── some_page.dart
│   │   ├── widgets/
│   │   │   └── custom_widget.dart
│   │   ├── blocs/
│   │   │   ├── some_bloc.dart
│   │   │   └── bloc_event.dart
│   │   ├── utils/
│   │   │   └── some_utility.dart
│   │   └── main.dart
│   ├── core/
│   │   ├── errors/
│   │   │   └── failures.dart
│   │   ├── navigation/
│   │   │   └── navigator.dart
│   │   └── utils/
│   │       └── constants.dart
│   └── injections.dart
├── test/
├── android/
├── ios/
├── pubspec.yaml
└── README.md
```

