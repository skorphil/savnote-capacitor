## Linux Fedora

### Android tools

Android CLI
```shell
 curl -fsSL https://dl.google.com/android/cli/latest/linux_x86_64/install.sh | bash 
```

Android SDK
```shell
android sdk install \
"ndk/30.0.16248370" \
"platforms;android-35" \
"build-tools/36.0.0" \
"platform-tools" # includes ADB
```

Add to PATH in `fish`
```shell
set -Ux ANDROID_HOME $HOME/Android/Sdk # Not sure if its needed
fish_add_path $ANDROID_HOME/cmdline-tools/latest/bin $ANDROID_HOME/platform-tools $NDK_HOME # Not sure if its needed
```

### Java
> Gradle 8.14.3 supports up to Java 24
Select supported version of JDK from installed
```shell
sudo alternatives --config java
```


## License scaffold
```shell
gh repo license view MIT > LICENSE
```


## References
- [Install Android CLI](https://developer.android.com/tools/agents)