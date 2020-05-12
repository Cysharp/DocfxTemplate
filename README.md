# DocfxTemplate
Patchworked DocFX v2 template for Cysharp

The design of this template is strongly inspired by [docs.microsoft.com](https://docs.microsoft.com/).

## Demo
https://cysharp.github.io/MagicOnion/

## Usage

```
$ cd docs

$ ls
docfx.json

$ git clone --depth=1 https://github.com/Cysharp/DocfxTemplate _DocfxTemplate

$ docfx build -t _DocfxTemplate/templates/default-v2.5.2,_DocfxTemplate/templates/cysharp docfx.json
```
