# sway-workshop-web3rsvp

Please follow the installation instructions prior to the workshop if you have time! MacOS and Linux are supported. If you have windows, you will need a windows subsystem for linux.

## Installation Instructions

1. Install `cargo` using [`rustup`](https://www.rust-lang.org/tools/install)

    Mac and Linux:
    ```bash
    curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh
    ```

2. Check for correct setup:

    ```bash
    $ cargo --version
    cargo 1.62.0
    ```

3. Install `forc` using [`fuelup`](https://fuellabs.github.io/sway/v0.18.1/introduction/installation.html#installing-from-pre-compiled-binaries)

    Mac and Linux:
    ```bash
    curl --proto '=https' --tlsv1.2 -sSf \
    https://fuellabs.github.io/fuelup/fuelup-init.sh | sh
    ```

4. Check for correct setup:

    ```bash
    $ forc --version
    forc 0.18.1
    ```

    *if that doesn't work*

    ![open system preferences](images/system_preferences.png)
    ![click allow](images/allow_forc.png)

## Editor

You are welcome to use your editor of choice.

- [VSCode plugin](https://marketplace.visualstudio.com/items?itemName=FuelLabs.sway-vscode-plugin)
- [Vim highlighting](https://github.com/FuelLabs/sway.vim)
