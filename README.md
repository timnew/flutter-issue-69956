# Flutter issue 69956 demo

This is a minimum reproducible demo of the flutter integration bug: https://github.com/flutter/flutter/issues/69956

## Steps to reproduce

1. Build and launch the Android app
2. Press the `Launch Flutter Activity` button, flutter app will be launched
3. Pressed the `Exit` button on flutter screen, to pop the main screen from navigator.
4. A funny screen show appear
5. Press physical back would return to Android Activity
6. Press `Launch Flutter Activity` button again, a blank screen would shown