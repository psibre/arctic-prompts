# arctic-prompts #
 
Generate prompts PDF for [CMU ARCTIC](http://festvox.org/cmu_arctic/) dataset.

Run the [Gradle](http://gradle.org/) wrapper script to build the PDF.

    $ ./gradlew

Or possibly on Windows,

    > gradlew.bat

## Requirements ##
 
1. [Java](https://www.java.com/download/)
2. [SoX](http://sox.sourceforge.net/) **with MP3 support** (use the `lame` branch if you can't encode MP3 directly with sox)
3. An up-to-date LaTeX installation, preferably [TeX
Live](https://www.tug.org/texlive/), including the
[latexmk](http://www.ctan.org/pkg/latexmk/) build tool and the packages
    1. [beamer](http://www.ctan.org/pkg/beamer)
    2. [inputenc](http://www.ctan.org/pkg/inputenc)
    3. [media9](http://www.ctan.org/pkg/media9)
4. To get sound working, present the PDF on OSX or Windows with (sadly)
[Flash](http://get.adobe.com/flashplayer/) installed, using (even more sadly)
[Adobe Reader](http://get.adobe.com/reader/)
