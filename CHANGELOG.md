## 1.1.3

- Typos fixed.
- Bug in `byte_reader.dart` fixed.

## 1.1.2

- Optimizes to avoid or cheapen `as` casts where possible.
  Uses `as dynamic` with a context type where a cast cannot be avoided,
  for better dart2js performance.

## 1.1.1

- Populate the pubspec's `repository` field.
- Use `package:lints` for linting.
## 1.1.0

- Null safe.
- Adds `JsonWriter` for JSON sinks which generate JSON-like structures.
  Allows injecting "source" (of a matching format) directly into the structure.
- Adds `JsonProcessor`. Like a `JsonSink` but gets the `JsonReader` so it can
  process the values itself instead of getting the processed value.
- Adds `JsonReader.hasNextKey` and some methods on `StringSlice`.

## 1.0.1

- Add CHANGELOG.md.

## 1.0.0

- Initial Release
