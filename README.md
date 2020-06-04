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
