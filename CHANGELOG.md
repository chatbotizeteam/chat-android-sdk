## 1.0.4

- Added API documentation.
- Fixed `resetSession = true` resuming the stored conversation instead of starting a fresh one.
- When the app declares `CAMERA`, the file picker now requests it instead of hiding the camera option.
- Fixed the camera option missing from the file picker on Android 11+ when the camera app is not a system app.

## 1.0.3

- Added support for the prominent CTA button sales experience setting.
- `ChatStarted` is now emitted once the chat is fully ready, so controller calls made from it take effect.
- `endChat()` now also deregisters the push token.

## 1.0.2

- Added `ZowieChatSession.clearAnonymousSession` to clear a stored session without opening the chat.
- Reworked encrypted session storage; sessions stored by earlier versions are not resumed after upgrading.

## 1.0.1

- Documentation updates.

## 1.0.0

- Initial release.

## 0.0.2

- Preview version, not supported. Do not use in production.

## 0.0.1

- Preview version, not supported. Do not use in production.
