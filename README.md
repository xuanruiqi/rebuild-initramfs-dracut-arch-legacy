# WARNING

While this tool is still usable and fairly stable, it is no longer being maintained. No new features will be added, and no bugs will be fixed.
The tool has been completely rewritten in Python, to make its source code more readable and extensible. You may want to look at the
[Python version](https://github.com/xuanruiqi/rebuild-initramfs-dracut-arch) instead.

---

# rebuild-initramfs

A helper script for Arch Linux; rebuild initramfs images using dracut.
This is the equivalent of `mkinitcpio -p` and `mkinitcpio -P` for dracut;
it is smart enough to detect installed kernels and rebuild the initramfs images.

## Usage

`rebuild-initramfs [-h | --help] [-v | --verbose]`
Command line options:
  * `-h`, `--help`: prints this help message
  * `-v`, `--verbose`: be more verbose

## License

MIT License.

## Copyright

Xuanrui Qi ([me@xuanruiqi.com](mailto:me@xuanruiqi.com)), 2020.
