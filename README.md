# bind-zone-sublime-syntax

This repository contains a `.sublime-syntax` file for BIND Zone files. This file was created using [st2-zonefile](https://github.com/sixty4k/st2-zonefile) and [SublimeSyntaxConverter](https://github.com/aziz/SublimeSyntaxConvertor) for use with [`bat`](https://github.com/sharkdp/bat/blob/e608b331425ca2ce8f8d0bd37e7f90901f91eb99/README.md#adding-new-syntaxes--language-definitions).

## Usage with `bat`

```bash
mkdir -p "$(bat --config-dir)/syntaxes"
cd "$(bat --config-dir)/syntaxes"
git clone https://github.com/dronenb/bind-zone-sublime-syntax.git
bat cache --build
```
