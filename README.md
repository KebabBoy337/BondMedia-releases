# BondMedia — releases

Builds of BondMedia, a macOS client for Jellyfin. The app updates itself from here (Sparkle);
this repository only holds the update feed (`appcast.xml`) and the release archives.

## Install (first time)

Requires a Mac with Apple Silicon and macOS 27.

1. Download the latest `BondMedia-x.y.z.zip` from [Releases](../../releases) and unzip it.
2. Move `BondMedia.app` to Applications.
3. The app isn't notarized yet, so macOS blocks it until you run this once in Terminal:

   ```
   xattr -dr com.apple.quarantine /Applications/BondMedia.app
   ```

4. Open BondMedia, enter your Jellyfin server address and sign in.

After that, new versions arrive by themselves (BondMedia → «Проверить обновления…»).
