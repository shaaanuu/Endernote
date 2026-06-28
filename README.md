# EnderNote

A local-first, Markdown note-taking app built with Flutter.

<p align="center">
  <img src="screenshots/1.png" width="30%" />
  &nbsp;&nbsp;&nbsp;&nbsp;
  <img src="screenshots/2.png" width="30%" />
  &nbsp;&nbsp;&nbsp;&nbsp;
  <img src="screenshots/3.png" width="30%" />
  &nbsp;&nbsp;&nbsp;&nbsp;
  <img src="screenshots/4.png" width="30%" />
  &nbsp;&nbsp;&nbsp;&nbsp;
  <img src="screenshots/5.png" width="30%" />
</p>

## Features

- **Markdown**: write in Markdown, toggle live preview anytime
- **Chests**: vault-style folders to organize notes by project or context
- **Full-text search**: search across all notes instantly
- **Themes**: Catppuccin Mocha, Nord Dark, Nord Light
- **Local storage**: all data stays on device via [Isar](https://github.com/isar/isar) embedded DB
- **Cross-platform**: Android, Linux, Windows _(macOS and iOS builds currently unavailable)_

## Getting Started

```bash
git clone https://github.com/shaaanuu/endernote.git
cd endernote
flutter pub get
flutter run
```

### Android

Grab a prebuilt APK from [Releases](https://github.com/shaaanuu/endernote/releases):

| Variant | For |
| --- | --- |
| `android-universal.apk` | Most devices |
| `android-arm64-v8a.apk` | 64-bit ARM |
| `android-armeabi-v7a.apk` | 32-bit ARM |
| `android-x86_64.apk` | x86 64-bit |
| `android-legacy.apk` | Older devices (Impeller disabled) |

### Linux / Windows

Download `linux.zip` or `windows.zip` from [Releases](https://github.com/shaaanuu/endernote/releases) and extract.

## Contributing

Bug reports, feature requests, and PRs are welcome. See [CONTRIBUTING.md](CONTRIBUTING.md) for details.

## License

[MIT](LICENSE)
