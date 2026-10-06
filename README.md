## Prerequisites
- Android CLI
- Android SDK `platform-tools`
- Java 21

## Quick Start
Install dependencies
```shell
pnpm i
pnpm approve-builds
```

Install android capacitor package
```shell
pnpm install @capacitor/android
```


### Build in run
Plug phone with adb (wired or wireless)
```shell
pnpm build
pnpm exec cap run android
```

### Live Reload