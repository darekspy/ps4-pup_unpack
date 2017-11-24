# pup_unpack
A utility to unpack PS4 update blobs that have been previously decrypted using [pup_decrypt](https://github.com/idc/ps4-pup_decrypt/).

## See also
* [ps4-pup-unpacker, a C++ rewrite](https://github.com/Thunder07/ps4-pup-unpacker). If you are averse to C#/.NET.

## Note
This utility will not unpack the contents of nested filesystems. The filesystem images in updates are FAT32, exFAT, etc images and can be mounted or unpacked with other tools.