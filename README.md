
# Modern Control - Gamepad

A native AML plugin project for GTA San Andreas Android.

## Project Goals

- Target game: GTA San Andreas Android 2.10
- Target architecture: ARM64 (arm64-v8a)
- Mod loader: Android Mod Loader (AML)
- Build system: Android NDK and GitHub Actions
- Initial test controller: X3 gamepad

## Development Roadmap

### Phase 1: Build Environment
- [x] Set up GitHub repository
- [x] Verify GitHub Actions
- [x] Verify Android NDK and ARM64 compiler

### Phase 2: AML Plugin
- [ ] Integrate the AML Plugin SDK
- [ ] Build a minimal native plugin
- [ ] Verify plugin loading in GTA SA

### Phase 3: Gamepad Input
- [ ] Detect and inspect X3 gamepad input
- [ ] Test digital buttons
- [ ] Test analog sticks

### Phase 4: Gameplay Controls
- [ ] Map gamepad input to character movement
- [ ] Test camera and vehicle controls
- [ ] Improve compatibility and stability

## Current Status

The cloud build environment and ARM64 compiler have been verified.
The native AML plugin has not been built yet.

## Notes

- Development is managed from an Android phone.
- Cloud compilation is used instead of a local Android compiler.
- Compatibility with the target game and AML version must be tested.
