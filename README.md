# asdf-kubefirst

kubefirst plugin for [asdf](https://github.com/asdf-vm/asdf) version manager

## Install

```
asdf plugin-add kubefirst https://github.com/Claywd/asdf-kubefirst.git
```

## Use

Check out the [asdf documentation](https://asdf-vm.com/#/core-manage-versions?id=install-version) for instructions on how to install and manage versions of Kubectl.

## Architecture Override

The `ASDF_KUBEFIRST_OVERWRITE_ARCH` variable can be used to override the architecture that is used for determining which `kubefirst` build to download.
