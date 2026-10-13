# cordova-outsystems-r8-patch

Adds R8 keep rules for other plugins to Android release builds, for when a plugin breaks with R8 and can't be updated yet. It has no source code.

To patch another plugin, add its rules in `src/android/r8-patch.gradle`.
