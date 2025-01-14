![Latest version](https://img.shields.io/maven-central/v/org.matrix.android/matrix-android-sdk2) [![Build status](https://badge.buildkite.com/1f5af13987f4e309ae7d6d09e818e19a5a709008c249238c1a.svg?branch=main)](https://buildkite.com/matrix-dot-org/matrix-android-sdk2)

# matrix-android-sdk2

Matrix SDK for Android, extracted from the Element Android application.

The SDK is still in beta, and replaces the [legacy Matrix Android SDK](https://github.com/matrix-org/matrix-android-sdk) provided by Matrix.org

## Important notice

<b>For now, this project is an extract of the Matrix SDK module from Element Android. Please do not open a pull request on this project. If you want to propose a change on the SDK, please open a PR on https://github.com/vector-im/element-android. Thanks!</b>

## Disclaimer
This is a fork of the original repository, with an implementation for multiple account login. Yes

## About

This repository contains the matrix-android-sdk extracted from the project [Element Android](https://github.com/vector-im/element-android)

Please open any issue in the Element Android project: [Create an issue](https://github.com/vector-im/element-android/issues/new/choose)

## How to integrate the SDK in your application

### Quick start

To integrate the SDK to your application, add the following gradle dependency to the build.gradle of your application module:

```gradle
implementation 'org.matrix.android:matrix-android-sdk2:1.2.1'
```

Latest version: ![Latest version](https://img.shields.io/maven-central/v/org.matrix.android/matrix-android-sdk2)

### API documentation

The Matrix Android SDK2 API documentation can be found here: https://matrix-org.github.io/matrix-android-sdk2

We are currently working to improve it.

### Sample application

You can have a look on the sample app we have written to help starting with the new SDK: https://github.com/matrix-org/matrix-android-sdk2-sample.

This sample app is able to let the user connects to an existing account on any homeserver with password login, display the room list, display a room timeline and send message to a room.

### Element Android

Element Android is the main application developed and maintained by the core team, which uses this SDK. You can find it here: https://github.com/vector-im/element-android

## Migrate from legacy SDK

Sadly there is no official documentation on how to migrate from the old SDK to the new one. Because the new SDK API is totally new, we guess that there is no easy way to handle a migration.

We strongly recommend that any new applications uses this new SDK.
