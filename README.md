**English | [简体中文](README.zh-CN.md)**

<p align="center">
  <img src="./assets/readme/hero-en-v2.svg" width="100%" alt="homebrew-ygn: Small tools. One tap.">
</p>

A personal Homebrew tap for macOS utilities maintained by YanGN.

## Casks

| App | Purpose | Requirements |
|---|---|---|
| [FinderWrap](https://github.com/YanGN-ST/FinderWrap) | Wrap arrow-key navigation across Finder icon rows | macOS 13+, Apple Silicon |
| [Duty](https://github.com/YanGN-ST/Duty) | Monitor and restore selected default file associations | macOS 14+, Apple Silicon |

Install with `brew install --cask yangn-st/ygn/<name>`.

FinderWrap requires Accessibility and Input Monitoring permissions. Its fixed self-signed build is not notarized; verify the source and allow it in Privacy & Security if macOS blocks the first launch. macOS 15 and 27 require hardware verification.

Duty is not notarized. Verify the source and follow macOS guidance if the first launch is blocked.

## Install

```sh
brew tap yangn-st/ygn
brew install --cask yangn-st/ygn/finderwrap
```

Review a third-party tap and its casks before confirming Homebrew's prompt. Use `brew upgrade --cask <name>` to update and `brew uninstall --cask <name>` to remove an app.

<details>
<summary>Maintenance</summary>

FinderWrap cask updates are manual and require checking the fixed signing identity and release artifacts. Cask files live in `Casks/`; `Scripts/` contains update and verification tooling.

</details>

## License

See [LICENSE](LICENSE). Individual applications have their own licenses.
