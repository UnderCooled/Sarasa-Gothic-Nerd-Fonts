# Changelog

All notable changes to this project will be documented in this file.

## [HEAD](https://github.com/jonz94/Sarasa-Gothic-Nerd-Fonts/compare/v0.40.7-1...HEAD)

## [v0.40.7-1](https://github.com/jonz94/Sarasa-Gothic-Nerd-Fonts/compare/v0.40.7-0...v0.40.7-1) (2023-05-21)

### ✨ Features

- Upgrade nerd fonts to v3.0.1 ([#19](https://github.com/jonz94/Sarasa-Gothic-Nerd-Fonts/pull/19)), closes [#18](https://github.com/jonz94/Sarasa-Gothic-Nerd-Fonts/issues/18)

## [v0.40.0-0](https://github.com/jonz94/Sarasa-Gothic-Nerd-Fonts/compare/v0.39.0-0...v0.40.0-0) (2023-02-04)

### 📝 Documentation

- Add notes about web fonts ([#16](https://github.com/jonz94/Sarasa-Gothic-Nerd-Fonts/pull/16)), closes [#6](https://github.com/jonz94/Sarasa-Gothic-Nerd-Fonts/issues/6)

## [v0.39.0-0](https://github.com/jonz94/Sarasa-Gothic-Nerd-Fonts/compare/v0.38.0-0...v0.39.0-0) (2023-01-28)

### ✨ Features

- Upgrade nerd fonts to v2.3.3 ([76469e1](https://github.com/jonz94/Sarasa-Gothic-Nerd-Fonts/commit/76469e14e95b5dd631a0169472fa22d2cc4f68a9))

### 📝 Documentation

- Add note on font face differences ([#15](https://github.com/jonz94/Sarasa-Gothic-Nerd-Fonts/pull/15)), closes [#14](https://github.com/jonz94/Sarasa-Gothic-Nerd-Fonts/issues/14)

## [v0.37.4-1](https://github.com/jonz94/Sarasa-Gothic-Nerd-Fonts/compare/v0.37.4-0...v0.37.4-1) (2022-10-28)

### ✨ Features

- Upgrade nerd fonts to v2.2.2 ([d291184](https://github.com/jonz94/Sarasa-Gothic-Nerd-Fonts/commit/d291184de53cacd87cad592b793bb629b2ba2bcb))

### ✅ Bug Fixes

- Run font-patcher with `--removeligatures` option ([#13](https://github.com/jonz94/Sarasa-Gothic-Nerd-Fonts/pull/13)), closes [#12](https://github.com/jonz94/Sarasa-Gothic-Nerd-Fonts/issues/12)

## [v0.37.0-0](https://github.com/jonz94/Sarasa-Gothic-Nerd-Fonts/compare/v0.37.0...v0.37.0-0) (2022-09-03)

### ✨ Features

- Implement revision ([8ce5a8d](https://github.com/jonz94/Sarasa-Gothic-Nerd-Fonts/commit/8ce5a8d645aa65ec68d6d5e80f2be252be3b755a))

### ✅ Bug Fixes

- Downgrade nerd fonts back to v2.1.0 ([2445b49](https://github.com/jonz94/Sarasa-Gothic-Nerd-Fonts/commit/2445b4958fe1c8a92641fd0abec5293e0dfa4d7a)), closes [#10](https://github.com/jonz94/Sarasa-Gothic-Nerd-Fonts/issues/10)

## [v0.37.0](https://github.com/jonz94/Sarasa-Gothic-Nerd-Fonts/compare/v0.36.8...v0.37.0) (2022-08-29)

### ✨ Features

- Upgrade nerd fonts to v2.2.1 ([24d54d9](https://github.com/jonz94/Sarasa-Gothic-Nerd-Fonts/commit/24d54d9c4b0d54eef0aadde07c15600aa0c400b9))

### ✅ Bug Fixes

- Run font-patcher with `--adjust-line-height` option ([#9](https://github.com/jonz94/Sarasa-Gothic-Nerd-Fonts/pull/9)), closes [#8](https://github.com/jonz94/Sarasa-Gothic-Nerd-Fonts/issues/8)

## [v0.36.7](https://github.com/jonz94/Sarasa-Gothic-Nerd-Fonts/compare/v0.36.6...v0.36.7) (2022-07-17)

### ✨ Features

- Add TTC format 👉 https://github.com/jonz94/ttc-sarasa-gothic-nerd-fonts ([#7](https://github.com/jonz94/Sarasa-Gothic-Nerd-Fonts/pull/7)), closes [#3](https://github.com/jonz94/Sarasa-Gothic-Nerd-Fonts/issues/3)

- Installation

  - Scoop

  ```
  scoop install sarasa-nerd-font-ttc
  ```

  - Homebrew

  ```shell
  brew install font-sarasa-nerd-font-ttc
  ```

  - Linux

  https://gist.github.com/jonz94/bf5b885e656caa88b6adbf6df93612e2#file-option-2-install-sarasa-nerd-font-ttc-sh

## [v0.35.2](https://github.com/jonz94/Sarasa-Gothic-Nerd-Fonts/compare/v0.35.1...v0.35.2) (2021-11-28)

### ⚠ BREAKING CHANGES / ✨ Features

- In previous version, all variants of the patched fonts have exact same TTF font family name `Sarasa Nerd Font`. Now, each variant of the patched fonts will have proper TTF font family name. See [List of TTF Font Family Name](docs/ttf-font-family-name.md) for more details.

- You will need to apply changes to the font setting of the application after updating fonts to this version. For example: in order to using newer version of `sarasa-mono-tc-nerd-font.zip` in vscode, apply the following changes to vscode's `settings.json`:

```diff
-  "editor.fontFamily": "Sarasa Nerd Font",
+  "editor.fontFamily": "Sarasa Mono TC Nerd Font",
```

### ✅ Bug Fixes

- Resolve font alignment issue ([145000b](https://github.com/jonz94/Sarasa-Gothic-Nerd-Fonts/commit/145000bf0a64ae0bf17b99e483fb40e414ef6cad)), closes [#1](https://github.com/jonz94/Sarasa-Gothic-Nerd-Fonts/issues/1)
- Correct TTF font family name ([339054a](https://github.com/jonz94/Sarasa-Gothic-Nerd-Fonts/commit/339054a9d8c3a70d61abbe60f857031ade8cfee4)), closes [#2](https://github.com/jonz94/Sarasa-Gothic-Nerd-Fonts/issues/2)

## [v0.35.0](https://github.com/jonz94/Sarasa-Gothic-Nerd-Fonts/compare/v0.34.7...v0.35.0) (2021-11-08)

### ✨ Features

- Support [Homebrew](https://brew.sh) by creating custom homebrew tap 👉 https://github.com/jonz94/homebrew-sarasa-nerd-fonts

## [v0.34.7](https://github.com/jonz94/Sarasa-Gothic-Nerd-Fonts/compare/v0.34.6...v0.34.7) (2021-10-24)

### ⚠ BREAKING CHANGES

- The scoop bucket part is now moving to its own repository 👉 https://github.com/jonz94/scoop-sarasa-nerd-fonts ([e918116](https://github.com/jonz94/Sarasa-Gothic-Nerd-Fonts/commit/e9181166332ef7d858aff69577f5c5c7bb52441c))

## [v0.34.2](https://github.com/jonz94/Sarasa-Gothic-Nerd-Fonts/compare/v0.34.1...v0.34.2) (2021-08-31)

### ✨ Features

- Now all the font styles (`fixed`, `fixed-slab`, `mono`, `mono-slab`, `term`, `term-slab`, `gothic`, `ui`) and orthographies (`cl`, `hc`, `j`, `k`, `sc`, `tc`) of Sarasa Gothic is being patched ([47c74a5](https://github.com/jonz94/Sarasa-Gothic-Nerd-Fonts/commit/47c74a580cbb332b81104f8db6b4c44729b6d125))

## [v0.32.14](https://github.com/jonz94/Sarasa-Gothic-Nerd-Fonts/compare/v0.32.13...v0.32.14) (2021-07-25)

### ⚠ BREAKING CHANGES

- The release page now provide **a single `sarasa-mono-tc-nerd-font.zip` file includes all the font variants**, instead of a `.ttf` font file named `Sarasa-Mono-TC-Nerd-Font-Complete.ttf` in previous versions (`v0.32.13` and below)

### ✨ Features

- Now all the font variants (`Regular`, `Italic`, `Bold`, `Bold Italic`, `Light`, `Light Italic`, `Semibold`, `Semibold Italic`, `ExtraXlight`, `Extralight Italic`) of Sarasa Mono TC is being patched ([4cbe8b9](https://github.com/jonz94/Sarasa-Gothic-Nerd-Fonts/commit/4cbe8b964e618d559adcf6e9eaac9d6c0432a828))
