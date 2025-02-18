---
title: du
categories: |
  filesystem
version: 0.99.0
filesystem: |
  Find disk usage sizes of specified items.
usage: |
  Find disk usage sizes of specified items.
---
<!-- This file is automatically generated. Please edit the command in https://github.com/nushell/nushell instead. -->

# `du` for [filesystem](/commands/categories/filesystem.md)

<div class='command-title'>Find disk usage sizes of specified items.</div>

## Signature

```> du {flags} ...rest```

## Flags

 -  `--all, -a`: Output file sizes as well as directory sizes
 -  `--deref, -r`: Dereference symlinks to their targets for size
 -  `--exclude, -x {glob}`: Exclude these file names
 -  `--max-depth, -d {int}`: Directory recursion limit
 -  `--min-size, -m {int}`: Exclude files below this size

## Parameters

 -  `...rest`: Starting directory.


## Input/output types:

| input   | output |
| ------- | ------ |
| nothing | table  |

## Examples

Disk usage of the current directory
```nu
> du

```
