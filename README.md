Tweaked Instagram to remove distractions and annoyances
`Version v0.6.0` | `Tested on Instagram v350.0.12`

# Building from source
### Prerequisites
- XCode + Command-Line Developer Tools
- [Homebrew](https://brew.sh/#install)
- [CMake](https://formulae.brew.sh/formula/cmake#default) (`brew install cmake`)
- [Theos](https://theos.dev/docs/installation)
- [pyzule](https://github.com/asdfzxcvbn/pyzule?tab=readme-ov-file#installation) **\*only required for sideloading**

### Setup
1. Install iOS 14.5 frameworks for theos
   1. [Click to download iOS SDKs](https://github.com/xybp888/iOS-SDKs/archive/refs/heads/master.zip)
   2. Unzip, then copy the `iPhoneOS14.5.sdk` folder into `~/theos/sdks`
2. Clone SCInsta repo from GitHub: `git clone --recurse-submodules https://github.com/SoCuul/SCInsta`
3. **For sideloading**: Download a decrypted Instagram IPA from a trusted source, making sure to rename it to `com.burbn.instagram.ipa`.
   Then create a folder called `packages` inside of the `SCInsta` folder, and move the Instagram IPA file into it. 

### Run build script
```sh
$ chmod +x build.sh
$ ./build.sh <sideload/rootless/rootful>
```

# Credits
- Huge thanks to [@BandarHL](https://github.com/BandarHL) for creating the original BHInstagram/BHInsta project, which SCInsta is based upon.
