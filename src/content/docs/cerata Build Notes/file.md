---
title: file
description: A simple and lightweight Linux® distribution based on musl libc and toybox
---

- `--disable-static` is used by default
- `file` depends on the same version of itself
- No need to symlink against `libpthread` when building against `musl` libc
