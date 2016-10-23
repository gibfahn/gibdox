# My Ergodox Configuration

This is the latest version of my ergodox layout. The easiest way to modify it is
with the `import map` button in
[the configurator](https://input.club/configurator-ergodox/).

### Build instructions

Cribbed from [here](https://input.club/configurator-setup/#stepmac)

###### First time setup

 - `brew install dfu-util`

###### Flash - side

 - Plug the correct side directly into computer (don't daisy-chain)
 - If left:  `dfu-util -D left_kiibohd.dfu.bin`
 - If right: `dfu-util -D right_kiibohd.dfu.bin`


### Layout

![Layout](./Layout.png)
