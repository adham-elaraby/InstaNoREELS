# InstaNoREELS
A tweak for Instagram to remove distractions \
`Version v0.7.1` | `Tested on Instagram 384.0.0`

FOR EDUCATIONAL PUPOSES ONLY.

---

# Features
### General
- Hide Meta AI
- Disable scrolling reels
- Hide explore posts grid
- Hide trending searches
- Hide notes tray

### Feed
- Hide ads
- No suggested posts
- No suggested reels
- No suggested threads posts

### Hide navigation tabs
- Hide explore tab
- Hide create tab
- Hide reels tab

### Optimization
- Automatically clears unneeded cache folders, reducing the size of your Instagram installation

# Building from source
### Prerequisites
- XCode + Command-Line Developer Tools
- [Homebrew](https://brew.sh/#install)
- [CMake](https://formulae.brew.sh/formula/cmake#default) (`brew install cmake`)
- [Theos](https://theos.dev/docs/installation)
- [cyan](https://github.com/asdfzxcvbn/pyzule-rw?tab=readme-ov-file#install-instructions) **\*only required for sideloading**

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
