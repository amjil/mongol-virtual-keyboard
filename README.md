# mongol_virtual_keyboard

A new Flutter project.

Basic 
<br/>
![image](mongol-virtual-keyboard.gif)

Styled
<br/>
<img src="mongol-virtual-keyboard-styled.png" width="300">

## Getting Started

This project is a starting point for a Flutter application.

A few resources to get you started if this is your first Flutter project:

- [Lab: Write your first Flutter app](https://docs.flutter.dev/get-started/codelab)
- [Cookbook: Useful Flutter samples](https://docs.flutter.dev/cookbook)

For help getting started with Flutter development, view the
[online documentation](https://docs.flutter.dev/), which offers tutorials,
samples, guidance on mobile development, and a full API reference.

## Credits
Mongolian Flutter Apps are made possible by the following projects:

- [suragch/mongol](https://github.com/suragch/mongol) - Mongolian vertical script widgets for Flutter apps 
- [suragch/mongol_code](https://github.com/suragch/mongol_code) - Unicode conversion library for traditional Mongolian script 
- [suragch/mongol-library](https://github.com/suragch/mongol-library) - A library to allow vertical script Mongolian in Android apps

## Run Example
1. Install the `clj` command.
2. Init the example `clj -M:cljd init`
3. Copy pubspec.yaml.bak to pubspec.yaml `cp pubspec.yaml.bak pubspec.yaml`
4. Open a simulator `open -a Simulator`
5. Run flutter `clj -M:cljd flutter`

## Roadmap
- Support English key layout.
- Support displaying candidates list & suffix list.
- Support Save active word to Sqlite and can query it when type matched.