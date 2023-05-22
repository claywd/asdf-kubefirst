# asdf-kubefirst [![Build Status](https://github.com/claywd/asdf-kubefirst/actions/workflows/build.yml/badge.svg)](https://github.com/ganta/asdf-kubefirst/actions/workflows/build.yml)     

kubefirst plugin for [asdf](https://github.com/asdf-vm/asdf) version manager

## Install

```
asdf plugin-add kubefirst https://github.com/Claywd/asdf-kubefirst.git;
asdf plugin-add kubefirst https://github.com/Claywd/asdf-kubefirst.git;
asdf install kubefirst latest;
asdf global kubefirst;
kubefirst version;
```

## Use

Check out the [asdf documentation](https://asdf-vm.com/#/core-manage-versions?id=install-version) for instructions on how to install and manage versions of kubefirst.

## Architecture Override

The `ASDF_KUBEFIRST_OVERWRITE_ARCH` variable can be used to override the architecture that is used for determining which `kubefirst` build to download.
