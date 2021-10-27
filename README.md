## Dart release CLI

A simple command-line application written in Dart.

The CLI app simply takes a version number and change the old pubspec 
version number to the new version number.

To run the CLI :

### Using Dart VM

```shell
dart bin/release.dart
```

### Using DCli tools

First make sure you have [DCli tools globally installed](https://dcli.noojee.dev/getting-started#option-2-install-dart-dcli) and then:

```shell
# Make sure your file is executable first
chmod +x bin/release.dart

# Run as a simple script
./bin/release.dart
```

### Using dart compile

```shell
dart compile exe bin/release.dart -o release

🕙 Info: Compiling with sound null safety
🕙 Generated: dart-release-cli/release

# Time to run !
./release
```