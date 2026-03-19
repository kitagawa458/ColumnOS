# ColumnOS - OS Based on the LuaOS
This is a OS From the Roblox Placed named ICSCS

## Building

Get the source with:

`git clone --recursive https://github.com/ecchi123/ColumnOS.git`

### Dependencies

#### General

- `clang`
- `nasm`
- `curl`
- `ld.lld`
- `xorriso`

#### arch

- 'lld' (`ld.lld`)
- 'libisoburn' (`xorriso`)

```sh
make
```

## Testing

### Dependencies

- `qemu-system-x86_64`

```sh
make uefi
```
