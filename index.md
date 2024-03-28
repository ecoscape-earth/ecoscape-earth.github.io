# EcoScape

The EcoScape project aims at modeling animal (and perhaps, in the future, plant) habitats, study their connectivity, and more. 

## Publications

* Natalia Ocampo-Peñuela, Coen Adler, Artie Nazarov, Jasmine Tai, Natalie Valett, Luca de Alfaro. [Diffusion Models For Species-Specific Functional Habitat Connectivity](https://tr.soe.ucsc.edu/research/technical-reports/UCSC-SOE-23-10). Technical Report UCSC-SOE-23-10, 2023.  [Reproduction material](https://github.com/ecoscape-earth/ecoscape-connectivity-paper-reproduction).

## Code Repositories 

* [scgt](https://github.com/ecoscape-earth/scgt), the UC Santa Cruz Geographical Toolkit, contains functions for working with geotiff files. 
* [ecoscape-layers](https://github.com/ecoscape-earth/ecoscape-layers) contains functions for generating habitat and landcover layers for bird species. 
* [ecoscape-connectivity](https://github.com/ecoscape-earth/ecoscape-connectivity) is the tool for computing habitat connectivity. 

The above code can be installed via `pip`, e.g., `pip install ecoscape-connectivity`. 

## Sample Colab Notebooks

Some of the EcoScape software (such as connectivity computation) benefits from GPUs.  On [Google Colab](https://colab.research.google.com), you can use GPUs for free, or at low cost. 
The following Python notebooks, on Google Colab, demonstrate the EcoScape tools: 

* [EcoScape Connectivity Computation](https://colab.research.google.com/drive/1ckDp7zztfawL6Jpur_00KXi_dBl-3ebO?usp=sharing). The notebook shows how to run the EcoScape Connectivity computation given input habitat and landcover layers. 
* [EcoScape Layer Generation and Connectivity Computation](https://colab.research.google.com/drive/1Aby8VqaSMgYySxsLPXfsVgdvZvCFRUtI?usp=sharing). The notebook does the process of studying the connectivity for a species from beginning to end: it computes habitat and  landcover layers from IUCN data, and analyzes the connectivity using the EcoScape algorithm. 

## Project Members
(In alphabetical order)

### Faculty 

* Luca de Alfaro (luca@ucsc.edu)
* Natalia Ocampo-Peñuela (nocampop@ucsc.edu)
* Tyler Sorensen (tyler.sorensen@ucsc.edu)

### Contributors

* Coen Adler (ctadler@ucsc.edu)
* Artie Nazarov (anazarov@ucsc.edu)
* Jasmine Tai (cjtai@ucsc.edu)
* Ian Terry (imterry@ucsc.edu)
* Natalie Valett (nvalett@ucsc.edu)
