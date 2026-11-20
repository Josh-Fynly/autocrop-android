# AutoCrop

AutoCrop is a native Android application for local, offline-first,
confidence-aware batch image cropping.

## Product principles

- **Local-first:** Image processing happens on the device.
- **Non-destructive:** Original images are never overwritten.
- **Confidence-aware:** Uncertain crop decisions require user review.
- **Batch-resilient:** A failure on one image does not stop the entire batch.
- **Memory-bounded:** Image processing is designed for constrained devices.
- **Privacy-focused:** Images are not uploaded to a cloud service.

## Planned capabilities

- Screenshot cropping.
- Uniform border detection and removal.
- Edge-connected whitespace removal.
- Manual crop adjustment.
- Batch processing.
- Output verification.
- User-controlled original cleanup.

## Technology

- Kotlin
- Jetpack Compose
- AndroidX
- Gradle
- GitHub Actions

## Project status

The project is currently in its repository and Android
engineering foundation phase.

Image-processing implementation will begin only after the
Android foundation and its verification gates are complete.

## Development principles

Changes follow this engineering sequence:

Inspect → Plan → Implement → Test → Verify → Gate → Advance.

The `main` branch is reserved for verified changes.
Development work takes place on feature branches and is
integrated through `develop`.
