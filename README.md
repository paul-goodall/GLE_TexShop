# Use TexShop for GLE editing

## INSTRUCTIONS

To use TexShop as your editor for GLE:

1. Ammend 'gle_path' below to reflect the gle binary
2. copy this gle.engine file into the TexShop Engines dir (on a Mac this is ~/Library/TeXShop/Engines/gle.engine)
3. Create a .tex file (not a .gle file) and open with TexShop
4. Add the following shebang to the top of your .tex file: '% !TEX TS-program = gle'
5. Write some GLE code and then Typeset and voila!
