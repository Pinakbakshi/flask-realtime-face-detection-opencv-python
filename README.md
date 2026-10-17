# Flask Real-Time Computer Vision Demo

A Flask-based demonstration project for processing camera frames and displaying computer-vision results.

## Compatibility

The original documentation references older Python and OpenCV versions. Check the source and dependency files before running it: a migration to a supported Python 3 environment may be necessary.

## Local setup

1. Inspect the entry point and dependency manifest.
2. Create an isolated Python 3 environment.
3. Install compatible, pinned dependencies.
4. Run the application locally with development/debug settings disabled outside active debugging.
5. Keep the development server bound to localhost unless a secure deployment has been configured.

## Development checklist

- Document tested runtime and dependency versions.
- Handle unavailable cameras and invalid frames gracefully.
- Separate processing logic from web routes.
- Avoid storing or transmitting camera frames unless the application explicitly requires it.
- Do not expose an unauthenticated camera-processing endpoint publicly.
- Add tests for error handling and the main processing functions.

Confirm the setup commands and current capabilities against the source code; this README does not claim the legacy application has already been modernized.
