# SVGSymbolsToAISymbols

This Illustrator script will convert SVG symbols to illustrator symbols.

Each file of SVG symbols will be converted into separate a Illustrator symbol palette.

This was developed from the FreehandToAI.jsx distributed by Adobe.

This script will open all SVG symbol ready files specified in the user selected folder and save them as AI symbol palettes

A compatible SVG file must include SVG symbols with an id attribute, like:
```
<symbol id='Name_of_Symbol' ..... >
```
The ID will be used for the name of the symbol once converted to an Illustrator symbol palette.

With an appopriate server-side script, online SVG image libraries can be converted into separate
SVG files with multiple images (symbols) per file. Each file will be converted into a symbol palette
containing each of the included symbols.
