# unixnu-e5-kernel-builder

Public macOS runner that builds the UniXNU kernel for
[Enceka/UniXNU-e5](https://github.com/Enceka/UniXNU-e5) (Rongyue E5). The
kernel needs a full Xcode with the iphoneos SDK, so the build runs on the
macOS-26 image of GitHub Actions.

Nothing is published here: the private `Enceka/unixnu-build` repository
collects the artifact right after the run and deletes the public run, because
the kernel derives from Apple software and stays private.
