# debuild
Scripts to (help) automate the building of our Debian packages

Usage:

```bash

./build <gitrepourl> <release> <arch>
./build https://github.com/64studio/pdk.git stretch amd64
./build https://github.com/64studio/smart.git stretch amd64

```

This file contains the pbuilder path where the built debs are located:

`~/autobuild/tmp/result_dir.log`