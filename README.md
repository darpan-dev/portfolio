<img src="assets/images/logo.png" align="right" width="60px"/>

# Portfolio 💙

Flutter Portfolio – by [@Darpan](https://github.com/darpanthummar28)

[![Flutter 3](https://img.shields.io/badge/Flutter-3.32-02569b.svg?style=flat-square&logo=flutter&logoColor=13b9fd)](https://flutter.dev/)
[![Dart 3](https://img.shields.io/badge/Dart-3.8-0175c2.svg?style=flat-square&logo=dart&logoColor=13b9fd)](https://dart.dev/)

## Features ✨

💙 Responsive and adaptive design inspired by [Brittany Chiang](https://brittanychiang.com)\
💙 [Riverpod Architecture](https://codewithandrea.com/articles/flutter-app-architecture-riverpod-introduction/) by [Andrea Bizzotto](https://github.com/bizz84)\
💙 Feature-first structure\
💙 Multiple languages\
💙 Multiple themes\
💙 Multi-platform (Android, iOS, macOS, Windows, Linux, Web)

## Getting started 🚀

If you haven't already, install [Flutter](https://docs.flutter.dev/get-started/install)

**1. Install dependencies:**

```bash
flutter pub get
```

**2. Run the code generator:**

```bash
dart run build_runner build -d
```

> For additional information, refer to the [build_runner](https://pub.dev/packages/build_runner) documentation

<a id="generate-localization-files" style="text-decoration:none">**3. Generate localization files:**</a>

```bash
dart run easy_localization:generate -S assets/translations -f json -O lib/src/localization/generated -o locale_json.g.dart
dart run easy_localization:generate -S assets/translations -f keys -O lib/src/localization/generated -o locale_keys.g.dart
```


## Personalization 🛠️

<details>
  <summary><h3>Content 🖋</h3></summary>

**1. Portfolio Content:**\
Customize the portfolio content by modifying or adding JSON translation files within the [`assets/translations`](assets/translations) folder. Don't forget to [re-generate your localization files](#generate-localization-files) when working locally. For an understanding of how JSON translation files are structured, refer to the [translation template](docs/translation-template.md)

If you add or remove a JSON translation file, remember to update the `languages` key in your other translation files.

> For additional information, refer to the [easy_localization](https://pub.dev/packages/easy_localization) documentation

**2. Your description:**\
Update your description content in the `build/web/index.html`:

```html
<meta name="description" content="..." />
```

</details>

<details>
  <summary><h3>Theme 🎨</h3></summary>

**1. Launcher Icon and Splash Screen:**\
Update your launcher icon and your splash screen in the [`pubspec.yaml`](pubspec.yaml)

Then, run:

```bash
dart run flutter_launcher_icons
dart run flutter_native_splash:create
```

> For additional information, refer to the [flutter_launcher_icons](https://pub.dev/packages/flutter_launcher_icons) and [flutter_native_splash](https://pub.dev/packages/flutter_native_splash) documentations

</details>

