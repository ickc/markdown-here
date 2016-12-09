The only thing I customized is the CSS in `src/common/default.css`.

# Personal Markdown-Here Settings

- Syntax Highlighting CSS: `Solarized Light`

- TeX Mathematical Formulae Support: the following uses `srcset` and provide 3 images in 1x, 2x, 3x respectively:

    ```html
    <img src="https://latex.codecogs.com/png.latex?\dpi{98}\?{urlmathcode}" srcset="https://latex.codecogs.com/png.latex?\dpi{98}\?{urlmathcode} 1x, https://latex.codecogs.com/png.latex?\dpi{196}\?{urlmathcode} 2x, https://latex.codecogs.com/png.latex?\dpi{294}\?{urlmathcode} 3x" alt="{mathcode}">
    ```

    Unfortunately, email doesn't seem to like `srcset`, so a good compromise will be just 2x:
    
    ```html
    <img src="https://latex.codecogs.com/png.latex?\dpi{197}\?{urlmathcode}" alt="{mathcode}" style="zoom: 50%">
    ```

- Enabled `Enable automatic header anchors.`

- Disabled `Enable GFM line breaks.`
