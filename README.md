# NEXORA ENGINE

Native Android 3D engine project. Phase 1 establishes the Android/Kotlin host, C++20 core, JNI bridge, lifecycle handling, input queue, and main loop.

## Build
This repository is built by GitHub Actions. Open the **Actions** tab and download the `nexora-engine-debug-apk` artifact from a successful run.

## Current scope
This is an early engine-core scaffold, not a 3D renderer yet. Vulkan rendering, scene/entity systems, physics, editor tools, and project APK export are planned for later phases.

## Important about updates
Android only accepts an app update when it is signed with the same signing certificate as the installed build. Production in-app updates therefore require a persistent release keystore configured as GitHub Actions secrets. Never commit the keystore or its passwords to this repository.
