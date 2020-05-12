# DocfxTemplate
Patchworked DocFX v2 template for Cysharp

This template styles are highly-inspired by [docs.microsoft.com](https://docs.microsoft.com/).

## Usage

```
$ cd docs

$ ls
docfx.json

$ git clone --depth=1 https://github.com/Cysharp/DocfxTemplate _DocfxTemplate

$ docfx build -t _DocfxTemplate/templates/default-v2.5.2,_DocfxTemplate/templates/cysharp docfx.json
```