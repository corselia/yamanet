[![CircleCI](https://circleci.com/gh/corselia/yamanet.svg?style=svg)](https://circleci.com/gh/corselia/yamanet)

# YaManet
**Yet another Manet**

# What is Manet?
- An awesome app
- https://github.com/vbauer/manet

# Installation

## git clone and yarn install (npm install)
```bash
$ git clone git@github.com:corselia/yamanet.git
$ cd yamanet
$ yarn install
```

## Edit a configuration file
- Please refer an official document
    - https://github.com/vbauer/manet/blob/master/README.md

```bash
$ vim ./to_copy_files/config/default.yaml
```

## Copy a configuration file and web front files
- If you change web front files, edit [to_copy_files/public/*](/to_copy_files/public)

```bash
$ cp ./to_copy_files/config/default.yaml ./node_modules/manet/src/config
$ cp -r ./to_copy_files/public ./node_modules/manet
```

# Boot YaManet
```bash
$ ./start_yamanet.sh
```

# Stop YaManet
```bash
$ pkill -f manet
```

# Note
- If you use OS X, perhaps it doesn't work correctly. Please refer a following issue.
    - https://github.com/nwjs-community/nw-builder/issues/75
- If you user Raspberry Pi, maybe you cannot use `PhantomJS` because of ARM

# LICENSE
- [MIT LICENSE](/LICENSE)

# Screenshots
![YaManet Screenshot 01](yamanet_screenshot_01.png)

![YaManet Screenshot 02](yamanet_screenshot_02.png)

![YaManet Screenshot 03](yamanet_screenshot_03.png)
