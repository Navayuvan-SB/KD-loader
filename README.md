# KD-loader
Pre Loader for Klart'Digi

## Steps to be followed
- Copy the `kd-progress.svg` file and paste it in your project directory.
- Make a `div` tag, set below styles and include the svg as a image using the `kd-progress.svg` as it's source.

    ```css
    div {
        position: fixed;
        height: 100vh;
        width: 100vw;
        z-index: 10000;
        display: flex;
        justify-content: center;
        align-items: center;
    }
    ```
- Toggle this div's visiblity according to the loader logic. 