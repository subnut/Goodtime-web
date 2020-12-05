## How I removed unnessecary glyphs

See [https://stackoverflow.com/a/35754448](https://stackoverflow.com/a/35754448)

I converted the steps into a script `fontforge_script.pe`

To convert any font, copy the font to this directory, and run -
```
fontforge -script fontforge_script.pe font.ttf
```
If using UNIX, you may simply run -
```
./fontforge_script.pe font.ttf
```
Where `font.ttf` is the name of the TTF font file to convert.

After the script finishes executing, there should be a file in the same directory, called `font-extra_glyphs_removed.ttf`
