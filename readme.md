# Assests for PhoenixOS

This repo contains assets for supporting building and using <a href="https://github.com/SJTU-IPADS/PhoenixOS">PhoenixOS</a> (PhOS).

<b>[Background]</b> As PhOS targts at providing seamless experience to our users, we want one could build and run PhOS on native images provided by vendors. We exported assets which are relied by PhOS yet with large size in this repo, so that PhOS's build system can download them from here before start everything.

<b>[Contents]</b> These assets are:

* `go1.23.2.linux-amd64.tar.gz`

    Currently PhOS's building system is written in golang. This tarball contains golang 1.23.2, downloaded from golang official.

* `libclang-static-build.tar.gz`

    PhOS uses libclang for parsing the signature of kernels, and we also use it for auto-generating code of parsers and workers. Note that this asset is from <a href="https://github.com/deech/libclang-static-build">deech/libclang-static-build</a>.
