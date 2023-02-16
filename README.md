# Setup QEMU

A github action for installing [QEMU](https://www.qemu.org/). Works on Linux, Windows and macOS runners.

# Example

```yaml
      - name: Setup QEMU
        uses: visualdoj/setup-qemu@v1

      - name: Run QEMU
        run:  qemu-system-x86_64 --version
```

# Issues

* On Windows: `PATH` may be polluted with some other programs from `MSYS2`.
