[![](https://jitpack.io/v/codecrunchers-x/WebRTC-Android-Library.svg)](https://jitpack.io/#codecrunchers-x/WebRTC-Android-Library)
# WebRTC Android Library
## Introduction

The **WebRTC Android Library** provides a straightforward way to integrate WebRTC functionalities into your Android application. This library encapsulates the official WebRTC APIs from Google, providing an efficient solution for real-time communication.

> **Note:** jCenter has shut down as of August 15, 2024. The last official released artifact version from the Google WebRTC team is `google-webrtc-1.0.32006`.

## Getting Started

Follow the steps below to integrate the WebRTC Android Library into your project.

### Step 1: Add JitPack Repository

Add the JitPack repository to your root `build.gradle` file in the `allprojects` section  or in `settings.gradle`:

```groovy
repositories {
    google()
    mavenCentral()
    //here add jitpack maven repository.
    maven { url = URI("https://jitpack.io") }
}
```

### Step 2: Add the Dependency

Include the library in your app module's `build.gradle` file:

```groovy
dependencies {
    implementation("com.github.codecrunchers-x:WebRTC-Android-Library:v1.0.32006")
}
```

### Step 3: Remove Old Dependency (If have.)
```groovy
dependencies {
    // Remove this : it will not work!!
    // implementation("org.webrtc:google-webrtc:1.0.32006")
}
```

## Usage

With the library successfully integrated, you can start using WebRTC functionalities in your Android application. Refer to the official WebRTC Android documentation for detailed API usage and examples.

## Important Note

As jCenter is no longer available, the artifact version `google-webrtc-1.0.32006` is the last version officially released by the Google WebRTC team. Ensure to reference this version in your projects.
