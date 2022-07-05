# Use TexShop for GLE editing

## INSTRUCTIONS

To use TexShop as your editor for GLE:

1. Ammend `gle_path` variable in `gle.engine` to reflect the gle binary
2. copy this `gle.engine` file into the TexShop Engines dir
    - (on a Mac this is ~/Library/TeXShop/Engines/gle.engine)
3. Create a .tex file (not a .gle file) and open with TexShop
4. Add the following shebang to the top of your .tex file: `% !TEX TS-program = gle`
5. Write some GLE code and then Typeset and voila!

https://user-images.githubusercontent.com/8687443/177263971-0bcbba40-51be-4206-9910-223c8e400ff7.mp4

