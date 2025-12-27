# based-ayu

Based on [vscode-ayu version 1.1.0](https://github.com/ayu-theme/vscode-ayu/tree/29e8a12959371f31adbf9edbbb942711d672ddaf).

![vscode-ayu](assets/header.png)

> Source from: https://github.com/dempfi/ayu

A simple theme with bright colors and comes in three versions — *dark*, *light* and *mirage* for all day long comfortable work.

> Note that this isn't a theme maintained by the original [Ayu theme](https://github.com/dempfi/ayu) author so please report issues related to this theme here.

## Install

```shell
ext install based-ayu
```

Then go to `Preferences > Color Theme > Based Ayu Light(or Based Ayu Dark, or Based Ayu Mirage)`.
If you want to setup File Icon, then go to `Preferences > File Icon Theme > Based Ayu`.

## Screenshots

#### Light
![Light](assets/light.png)
![Light Bordered](assets/light-bordered.png)

#### Mirage
![Mirage](assets/mirage.png)
![Mirage Bordered](assets/mirage-bordered.png)

#### Dark
![Dark](assets/dark.png)
![Dark Bordered](assets/dark-bordered.png)

## Development

Install dependencies
```shell
npm install
```

Update themes and build VSIX package
```shell
npm run build && npm run package
```
