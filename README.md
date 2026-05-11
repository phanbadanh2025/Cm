# IP Camera Viewer

Ứng dụng Flutter xem camera IP RTSP (YoSee, Hikvision, Dahua, Generic...)

## Cấu trúc thư mục

```
ip_camera_viewer/
├── pubspec.yaml
├── lib/
│   ├── main.dart
│   ├── core/
│   │   ├── theme.dart
│   │   └── constants.dart
│   ├── models/
│   │   └── camera_model.dart
│   ├── providers/
│   │   └── camera_provider.dart
│   ├── screens/
│   │   ├── home_screen.dart
│   │   ├── add_camera_screen.dart
│   │   └── fullscreen_screen.dart
│   └── widgets/
│       ├── camera_grid.dart
│       ├── camera_tile.dart
│       └── connection_status.dart
```
