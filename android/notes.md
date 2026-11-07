# Android Defensive Notes

## Common Hardening Observations

- Always enable R8 obfuscation in release builds
- Implement basic root and emulator detection for sensitive apps
- Use certificate pinning for critical API communications
- Prefer EncryptedSharedPreferences over regular SharedPreferences
- Disable `android:allowBackup` if the app handles sensitive data
- Remove all debug logs before release

## Personal Practice

I use these checks when hardening Android applications under my control.
