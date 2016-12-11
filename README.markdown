The only thing I customized is the CSS in `src/common/default.css`.

# Personal Markdown-Here Settings

- Syntax Highlighting CSS: `Solarized Light`

- TeX Mathematical Formulae Support: the following uses `srcset` and provide 3 images in 1x, 2x, 3x respectively:

    ```html
    <img src="https://latex.codecogs.com/png.latex?\dpi{99}{urlmathcode}" srcset="https://latex.codecogs.com/png.latex?\dpi{99}{urlmathcode} 1x, https://latex.codecogs.com/png.latex?\dpi{198}{urlmathcode} 2x, https://latex.codecogs.com/png.latex?\dpi{297}{urlmathcode} 3x" alt="{mathcode}">
    ```

    Unfortunately, email doesn't seem to like `srcset`, so a good compromise will be just 2x:
    
    ```html
    <img src="https://latex.codecogs.com/png.latex?\dpi{198}{urlmathcode}" alt="{mathcode}" style="zoom: 50%">
    ```

    The ppi is chosen such that the text in math match normal text when Latin Modern font is used. For the use of dpi, see <https://www.codecogs.com/pages/forums/pagegen.php?id=2914>

- Enabled `Enable automatic header anchors.`

- Disabled `Enable GFM line breaks.`
