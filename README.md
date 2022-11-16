##  .sass and .scss files are compile to regular css file. 
##  Css file then loaded as linkhref onto html, therefore it is pre-processor.
##  All css files can be bundled as one with webpack plugin "postcss-import".
##  That one file can be written in future syntaxes, drafted stage, with webpack plugin "postcss-preset-env".
##  That one file and all css in it can be minified with webpack plugin "cssnano".
##  That one file can either be loaded as linkhref onto html or an external regular css file with webpack plugin MiniCssExtractPlugin.

##  starting codes
index.html
main.css
#typography.css

##  practice codes
main.sass
main.scss <- main practice>

##  sass (indented way of writing wo braces and semicolon)

## scss features
1. nested properties like flex {direction} & font{size}.
2. variables stores; sizing keywords, whitespaced list & maps.
3. nesting selectors.
4. & or the parent selector.
5. forwardslash comment.
6. builtin functions like; rgb', red', mix', hsl', hue', darken', desaturate', grayscale', invert', fade-in', transparentize', where '=().