# Alternative dependency managers support for [YandexMapKit](https://tech.yandex.ru/maps/mapkit/)

# SPM

Add `https://github.com/iserbius/yandex-map-support` to your project dependencioes

# Carthage

Add lines to Cartfile

```
binary "https://raw.githubusercontent.com/iserbius/yandex-map-support/master/YandexRuntime.json"
binary "https://raw.githubusercontent.com/iserbius/yandex-map-support/master/YandexMapKit.json"
binary "https://raw.githubusercontent.com/iserbius/yandex-map-support/master/YandexMapKitPlaces.json"
```

Set `-ObjC` parameter in the `Other linker flags` project phases settings.

Additionally these frameworks are needed to be added to the project:

- "OpenGLES",
- "CoreFoundation",
- "Security",
- "CoreTelephony",
- "CoreLocation",
- "GLKit",
- "CoreGraphics",
- "SystemConfiguration",
- "CoreMotion"
- "resolv",
- "c++"