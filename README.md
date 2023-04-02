# DALAI_TEST

## INSTALL DALAI

- `dalai` repository is hosted at [github.com/cocktailpeanut/dalai](https://github.com/cocktailpeanut/dalai)

- the easiest way to use `dalai` is as follows

    - Install `node.js`. It comes with `npm` and `npx`

    - Create a isolated node environment

        ```bash
        mkdir dalai_test
        npm init
        ```

    - Install `dalai`

        ```bash
        npm install --loglevel verbose dalai
        ```
        After installing a `dalai`, the `dalai` binary should be stored in `./node_modules/.bin/dalai`
    
    - Download models

        `dalai` makes the processing of downloading models easy. Below is an example of downloading `alpaca 7B` model. Please refer to [cocktailpeanut.github.io/dalai](https://cocktailpeanut.github.io/dalai) for more details

        ```bash
        npx dalai --home . alpaca install 7B
        ```
        *`npx dalai <args>` is identical to executing `./node_modules/.bin/dalai <args>`*

    - Run the web UI

        ```bash
        npx dalai --home . serve
        ```
