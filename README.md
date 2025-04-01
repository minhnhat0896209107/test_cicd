# test_cicd

A new Flutter project.

## Getting Started

# Build command
- Build Android debug
```bash
flutter build apk --debug --build-name=1.0.0 --build-number=1
```

- Build iOS debug
```bash
flutter build ios --debug --build-name=1.0.0 --build-number=1 --no-codesign
```

# check update data patch
adb logcat | grep flutter