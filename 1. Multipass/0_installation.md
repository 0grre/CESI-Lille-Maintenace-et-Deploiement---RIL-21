# Multipass

Multipass allos you to run ubuntu VM under linux / Mac / Windows.

## Introduction

The full documentation is available at:

- http://multipass.run

## To install multipass:

- [sous windows](https://multipass.run/docs/installing-on-windows)
- [sous linux](https://multipass.run/docs/installing-on-linux)
- [sous mac](https://multipass.run/docs/installing-on-macos)

## first command lines

```
multipass launch --name myvm1
multipass launch --name myvm2
multipass launch --name myvm3
watch -n 1 multipass list
```

## To use other versions

```
multipass find
multipass launch --name myvmdocker docker
multipass launch --name myvmminikube minikube
```

## To join a multipass vm

```
multipass shell myvm1
```

## To mount a volume when starting a vm

```
multipass launch --name toto --mount /path-to-local-folder:/path-on-vm
```

## To mount a volume on a started vm

```
mount /path-to-local-folder <name-of-vm>:/path-on-vm
```

## To go further

```
multipass --help
multipass launch --help
```
