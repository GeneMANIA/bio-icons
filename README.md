# bio-icons

This is a set of icons for biology, representing [model organisms](http://en.wikipedia.bio/wiki/Model_organism) etc.  The icons can be used as plain SVG files or an icon font.

A demo of the icon font can be found in `font-icons/demo`.

The icon set currently includes:

* `.bio-cells` : a group of cells : Saccharomyces cerevisiae, bacteria, etc
* `.bio-fish` : a fish : Danio rerio etc
* `.bio-fly` : a fly : Drosophila melanogaster etc
* `.bio-helix` : a double helix : DNA, gene, etc
* `.bio-human` : a human : Homo sapiens
* `.bio-mouse` : a mouse on its hind legs : Mus musculus or similar rodents
* `.bio-plant` : a potted plant : Arabidopsis thaliana etc
* `.bio-rat` : a rat on all fours : Rattus norvegicus
* `.bio-worm` : a worm : Caenorhabditis elegans etc
* `.bio-yeast` : two budding yeast cells : Saccharomyces cerevisiae
* * `.bio-yeasts` : many budding yeast cells : Saccharomyces cerevisiae



## Building

To build the icon font:

1. Place all SVG files you would like in the font in the `svg-icons` directory.  An icon named `foo.svg` will become `.bio-foo` in the icon font.
1. Install [`fontcustom`](https://github.com/FontCustom/fontcustom).
1. Run `fontcustom compile` to generate the icon font in the `dist` directory.



## Contributing

Contributions and pull requests are welcome to this project.  

Some guidelines:

* If you are adding an icon, please make sure to give credit to the author in this README.
* Place the original icon file in `original-icons/foo` where `foo` is the name of the organism.
* Place the edited/final version of the icon in `svg-icons/foo.svg` where `foo` is the name of the organism.
* Either build the icon font to make sure all is well, or note that you haven't tested it in the pull request.



## Attributions

The following icons were used in this project.  Please note that some or all of these icons may have been modified, and the original files can be found in the `original-icons` directory.

* `cells` : Beans by giulia bianchi from The Noun Project
* `fish` : Fish by Jens Tärning from The Noun Project
* `fly` : Fly by Felipe Perucho from The Noun Project
* `helix` : DNA by Gustav Salomonsson from The Noun Project
* `human` : Vitruvian Man by Budi Hartono from The Noun Project
* `mouse` : Public Domain from The Noun Project
* `plant` : Plant by Cassie McKown from The Noun Project
* `rat` : Rat by Francisca Arévalo from The Noun Project
* `worm` : Fishing Hook by Stephen Hemenway from The Noun Project
* `yeast` & ``yeasts` : Beans by giulia bianchi from The Noun Project
