# Zowie Chat Android SDK — moved

This SDK is now the **Zowie Conversation SDK for Android**, developed in
[zowie-ai/conversation-sdk-android](https://github.com/zowie-ai/conversation-sdk-android).
This repository is archived and gets no further releases.

The Maven repository stays the same. To switch, replace the dependency:

```kotlin
// before
implementation("ai.zowie:chat-android-sdk:1.0.4")

// after
implementation("ai.zowie:conversation-sdk:2.0.0")
```

and change imports from `ai.zowie.chat` to `ai.zowie.conversationsdk`. Component
names stay the same. See the new repository for the full documentation and
changelog.

Versions 1.x stay available from the same Maven repository, so existing builds
keep working. Their documentation is at
[tag 1.0.4](https://github.com/chatbotizeteam/chat-android-sdk/blob/1.0.4/README.md).
