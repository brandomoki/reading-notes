# React Native

## getting started with react native

- Name three Core Components of React Native and describe what they do.
  - text contains text, view container that supports a layout, Image displays images

- What problem does React Native solve (why call it native)?
  - With React Native, you use native UI controls and have full access to the native platform.” So basically, React Native is a JavaScript library that allows you to use native UI controls and everything in the native platform
- What are the building blocks of a React Native app? How does that compare to a React app?
  - components

## expo

- What solution does expo provide?
  - Expo is an open-source framework for apps that run natively on Android, iOS, and the web.
- Expo tries to manage as much of the complexity of building apps as possible, which is why we call it the ____ workflow.
- What is the difference between React Native and Expo?
  - The expo package provides a suite of features that make it easier to develop, and scale complex React Native applications

## expo snack

- Checkout this tool. What does snack allow you to do?
  - Expo Snack is an open-source platform for running React Native apps in the browser. It dynamically bundles and compiles code and runs it in the Expo Client or in a web-player. 

## ejecting

- What does “eject” mean within the context of Expo?
  - Expo allows you to eject your pure-JS project from the Expo iOS/Android clients, providing you with native projects that can be opened and built with Xcode and Android Studio. Those projects will have dependencies on ExpoKit, so everything you already built will keep working as it did before.
- When should you not eject?
  - Your Expo project needs a native module that Expo doesn't currently support
- Why might you choose to eject?
  - If you have native demands that expo cant meet
