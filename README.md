```
Usage: pip2tgz [OPTIONS] PACKAGE...
Make Slackware packages from PIP modules.
Options:
    --help                  Show this help message.
    --version               Show version info and exit.
    -2                      Build a Python 2 package.
    -3                      Build a Python 3 package (default).
    --arch ARCH             Specifies the package architecture.
    --build-tag TAG         Specifies the package build tag.
    --build-number NUM      Specifies the package build number.
    --pkgdir DIR            Output packages to DIR (default: /tmp).
    --no-banner             Leave out the pip2tgz banner in the description.
    --pip CMD               Use CMD as the PIP binary (default: pip3).
    --prefix PREFIX         Use "{PREFIX}-PACKAGE" as the generated package
                              prefix (default is python3-).
    --package-ext EXT       Specifies the package extension (default: txz).
                              Ignored if --dir is specified.
    --no-makepkg            Do not attempt to run makepkg to build a package.
                              Really only useful with --jail.
    --jail-only JAIL        Set the package jail location to JAIL and don't run
                              makepkg to build a package.
    --jail JAIL             Set the package jail location to JAIL. The script
                              will clear this directory before outputting its
                              files there. By default, it uses a temporary
                              directory as the build jail.

Copyright (C) 2021 Dan Church <h3xx@gmx.com>.
License GPLv3+: GNU GPL version 3 or later (http://gnu.org/licenses/gpl.html).
This is free software: you are free to change and redistribute it. There is NO
WARRANTY, to the extent permitted by law.
```
