# akuma

😈 A dangerous untrustworthy code style adviser

## What Akuma does

Generate configurable comments on large lines function declarations.

## Getting Started

```shell
npm install akuma
```

## Commands

`--write`  
generate comments on any function declaration exceeds configured line limitation in specific files.

```shell
akuma --write index.js
```

`--line`  
set function declaration line limitation, `default: 50`

```shell
akuma --write index.js --line 100
```
