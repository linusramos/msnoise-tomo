# msnoise-tomo

[![Build Status](https://travis-ci.org/ThomasLecocq/msnoise-tomo.png)](https://travis-ci.org/ThomasLecocq/msnoise-tomo)
[![Build status](https://ci.appveyor.com/api/projects/status/hkaxi68hikwu6any/branch/master?svg=true)](https://ci.appveyor.com/project/ThomasLecocq/msnoise-tomo/branch/master)

## Documentation

The documentation is available at http://msnoise.org/plugins/msnoise-tomo/doc/

### Requirements

- python3-devel
```
# sudo dnf install python3-devel
```

- register plugin on MSNoise
add 'msnoise_tomo' to MSNoise Admin's config > plugins

### Workflow

1. msnoise plugin tomo install
1. msnoise plugin tomo info
1. msnoise plugin tomo prepare-ccf
1. msnoise plugin tomo ftan
1. msnoise plugin tomo plot
1. msnoise plugin tomo prepare-1d
1. msnoise plugin tomo prepare-tomo
1. msnoise plugin tomo answt
1. msnoise plugin tomo plot3d

### Errors Encountered

- ANSWT : ! FileNotFoundError: [Errno 2] No such file or directory: 'TOMO_FILES/ParamFile.txt'

  copy from https://raw.githubusercontent.com/ThomasLecocq/msnoise-tomo/master/msnoise_tomo/test/data/ParamFile.txt

!! According to the thread https://ds.iris.edu/message-center/thread/3421/, TOMO is still under development as of 2017. Last update on the code was in 2018. Seems like the project not yet complete.

