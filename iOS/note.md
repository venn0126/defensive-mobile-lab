# iOS Defensive Notes

## Common Hardening Observations

- Enable symbol stripping in release builds
- Implement jailbreak detection for higher-risk apps
- Use certificate pinning
- Store sensitive data in Keychain with appropriate protection classes
- Enforce strict App Transport Security (ATS)
- Remove debugging entitlements in production builds

## Personal Practice

I apply these defensive measures when securing iOS applications I own or am authorized to maintain.
