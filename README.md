# Second Brain — downloads

Installers for **Second Brain**: your Markdown notes as an interactive 3D neural network, with a local AI agent and a built-in MCP server.

**Website:** [romeo-francesco.it/secondbrain](https://www.romeo-francesco.it/secondbrain)

This repository only hosts the installers, published with each release. It contains no source code.

## Download

The [latest release](../../releases/latest) has three files:

| System | File |
| --- | --- |
| Mac with Apple Silicon | `Second-Brain-mac-arm64.dmg` |
| Mac with Intel | `Second-Brain-mac-x64.dmg` |
| Windows (64-bit) | `Second-Brain-win-x64.exe` |

## First launch

**macOS.** The app is not signed with an Apple Developer ID yet, so macOS refuses to open it the first time. After dragging it into Applications, right-click the app, choose **Open**, then **Open** again. Or run:

```bash
xattr -cr "/Applications/Second Brain.app"
```

**Windows.** The installer is not code-signed, so SmartScreen may warn you. Click **More info**, then **Run anyway**.

## License

MIT © Francesco Romeo
