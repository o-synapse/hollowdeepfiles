# Hollowdeep downloads

Release builds of Hollowdeep live under [Releases](https://github.com/o-synapse/hollowdeepfiles/releases).

- **macOS:** `Hollowdeep-<version>-macos.dmg`. Open it and drag Hollowdeep to Applications.
- **Windows:** `Hollowdeep-<version>-windows.zip`. Extract it and run `Hollowdeep\Hollowdeep.exe`.

Each release includes `SHA256SUMS.txt`. To check a download:

```
shasum -a 256 Hollowdeep-0.1.0-macos.dmg              # macOS
certutil -hashfile Hollowdeep-0.1.0-windows.zip SHA256  # Windows
```

The builds aren't signed by a paid developer account yet. The first time you open the game:
- **macOS:** right-click Hollowdeep in Applications, choose **Open**, then **Open** again.
- **Windows:** SmartScreen may show "Windows protected your PC". Click **More info**, then **Run anyway**.
