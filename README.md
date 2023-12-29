# MagiskFrida

**里面放的是 strong frida**

**https://github.com/hzzheyang/strongR-frida-android/releases**

**改的build里面的链接就能自己编译了**


![GitHub Workflow Status](https://img.shields.io/github/actions/workflow/status/ViRb3/magisk-frida/main.yml?branch=master)
![GitHub repo size](https://img.shields.io/github/repo-size/ViRb3/magisk-frida)
![GitHub downloads](https://img.shields.io/github/downloads/ViRb3/magisk-frida/total)

> [Frida](https://frida.re) is a dynamic instrumentation toolkit for developers, reverse-engineers, and security researchers

> [MagiskFrida](README.md) lets you run frida-server on boot with [Magisk](https://github.com/topjohnwu/Magisk)

## Supported architectures

`arm64`, `arm`, `x86`, `x86_64`

## How fast are frida-server updates?

Instant! This module is hooked to the official Frida build process

## Issues?

Check out the [troubleshooting guide](TROUBLESHOOTING.md)

## Building yourself

```bash
poetry install
poetry run python main.py
```

- Release ZIP will be under `/build`
- frida-server downloads will be under `/downloads`
