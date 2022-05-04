# Install dependencies

1.  Install BasicTeX.
    ```shell
    brew install --cask basictex
    ```
1.  Reload your terminal then install packages.
    ```shell
    sudo tlmgr update --self
    sudo tlmgr install latexmk csquotes
    ```

# Build

Use the `latexmk` command to build a PDF in the `build` folder.

```shell
latexmk
```

The `-pv` argument builds and opens a preview, and the `-pvc` argument opens a preview and rebuilds on change.

```shell
latexmk -pv
```

```shell
latexmk -pvc
```
