# Practice Dart

## create project

use (stagehande)[https://github.com/dart-lang/stagehand/issues]
```
mkdir sample-dart && cd sample-dart
pub global activate stagehand
stagehand console-full
```

## How to use
install package `pub get`
```
pub get
``` 

run the app `dart`
```
dart bin/main.dart
```

compile `dart2aot`
```
dart2aot bin/main.dart bin/main.dart.aot
```

run compiled app `dartaotruntime`
```
dartaotruntime bin/main.dart.aot

// Speed measurment
time dartaotruntime bin/main.dart.aot
```


## Refference 
https://dart.dev/tutorials/server/get-started