# nerd-font-fira-code

Single family of fonts for trial (WIP).

## Install

On ubuntu:

```bash
$ apt list fontconfig unzip 2>/dev/null | grep -c -e "^fontconfig" -e "^unzip"
2
$ cd && \
  curl -LOs https://github.com/sthagen/nerd-font-fira-code/raw/default/dist/FiraCode.zip && \
  mkdir -p .fonts && \
  unzip -q FiraCode.zip -d "$HOME"/.fonts && \
  fc-cache -fv
```

## Status

Experimental.

**Note**: The default branch is `default`.
