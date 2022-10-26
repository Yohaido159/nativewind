<div align="center">
<p align="center">
  <a href="https://nativewind.dev" target="_blank">
    <img src="https://nativewind.dev/img/logo.svg" alt="Tailwind CSS" width="70" height="70">
    <h1 align="center" style="color:red;">NativeWind</h1>
  </a>
</p>
<img alt="GitHub branch checks state" src="https://img.shields.io/github/checks-status/marklawlor/nativewind/next">
<img alt="npm" src="https://img.shields.io/npm/v/nativewind">
<img alt="npm" src="https://img.shields.io/npm/dt/nativewind">
<img alt="GitHub" src="https://img.shields.io/github/license/marklawlor/nativewind">
</div>
<br />

`NativeWind` is a complete tooling solution to use [Tailwind CSS](https://tailwindcss.com) on all React Native platforms (ios/android/web/window/macos/etc). It can be used either as a utility styling library or for building your own component library.

On native devices, `NativeWind` pre-builts your styles and uses a minimal runtime for dynamic styles. While in your browser, it provides a compatibility layer between React Native and your CSS.

In addition to styling, `NativeWind` provides optional Babel plugins to create a consistent developer experience, such as supporting a `className` prop on any component.

## In Action

Click the picture to go to a live example!

<a href="https://snack.expo.dev?name=Hello World&dependencies=react,react-native,nativewind@latest&platform=web&supportedPlatforms=ios,android,web&code=import%20React%20from%20'react'%3B%0Aimport%20%7B%20withExpoSnack%20%7D%20from%20'nativewind'%3B%0A%0Aimport%20%7B%20Text%2C%20View%20%7D%20from%20'react-native'%3B%0Aimport%20%7B%20styled%20%7D%20from%20'nativewind'%3B%0A%0Aconst%20StyledView%20%3D%20styled(View)%0Aconst%20StyledText%20%3D%20styled(Text)%0A%0Aconst%20App%20%3D%20()%20%3D%3E%20%7B%0A%20%20return%20(%0A%20%20%20%20%3CStyledView%20className%3D%22flex-1%20items-center%20justify-center%22%3E%0A%20%20%20%20%20%20%3CStyledText%20className%3D%22text-slate-800%22%3E%0A%20%20%20%20%20%20%20%20Try%20editing%20me!%20%F0%9F%8E%89%0A%20%20%20%20%20%20%3C%2FStyledText%3E%0A%20%20%20%20%3C%2FStyledView%3E%0A%20%20)%3B%0A%7D%0A%0A%2F%2F%20This%20demo%20is%20using%20a%20external%20compiler%20that%20will%20only%20work%20in%20Expo%20Snacks.%0A%2F%2F%20You%20may%20see%20flashes%20of%20unstyled%20content%2C%20this%20will%20not%20occur%20under%20normal%20use!%0A%2F%2F%20Please%20see%20the%20documentation%20to%20setup%20your%20application%0Aexport%20default%20withExpoSnack(App)%3B%0A">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://user-images.githubusercontent.com/3946701/178458845-c9ac0299-6809-4002-99a0-78030f27b06a.png">
    <img src="https://user-images.githubusercontent.com/3946701/178458837-df03c080-eb13-4dcc-9080-186b061a8678.png">
  </picture>
</a>

## Highlights

- Works on all RN platforms, uses the best style system for each platform.
- Uses the Tailwind CSS compiler (always get up-to-date features)
- Native styles are computed at build time
- Babel plugin for simple setup and improving intellisense support
- Respects all tailwind.config.js settings, including themes, custom values, plugins

## Styling Features

- Supports `px`/`%`/`rem`/`vw`/`vh`
- Polyfills pseudo classes - hover / focus / active are available on compatible components
- Supports arbitrary classes / media queries
- Supports `clamp()`
- Platform only variants eg. `android:text-black`
- Group and named groups allow styling based upon parent state
- Create simple layouts with `gap`/`space`/`divide`

## Built your own multi-platform component library

- Create complex components with the `styled()` helper
- Supports dynamic theme values via CSS variables (which work on Native!)
- Supports light / dark mode
-

- Supports group and named groups allowing styling based upon parent state

## Documentation

All documentation is on our website https://nativewind.dev
