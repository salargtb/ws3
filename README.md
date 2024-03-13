# ws3

---
ws3 (Wood Supply Simulation System) is a Python package for modelling landscale-level wood supply planning problems.

Read the tutorial here:
https://ws3.readthedocs.io/en/dev/

---

## Table of Contents

- [Modules](#modules)
- [Examples](#examples)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgments](#acknowledgments)
- [Contact](#contact)


## Modules 

ws3 has 5 main modules as follows:

- common.py: This module contains definitions for global attributes, functions, and classes that might be used anywhere in the package.
- core.py: 
- forest.py: This module implements functions for building and running the wood supply simulation models.
- opt.py: This module implements functions for formulating and solving optimization problems. 
- spatioal.py: This module implements the ``ForestRaster`` class, which can be used to allocate an aspatial disturbance schedule (for example, an optimal solution to a wood supply problem generated by an instance of the ``forest.ForestModel`` class) to a rasterized representation of the forest inventory.


## Examples 

- 010_ws3_model_example-fromscratch.ipynb: This notebook has an example of building a new ``ws3 `` model from scratch.
- 020_ws3_model_example-woodstock.ipynb: This notebook has an example of building a ws3 model from Woodstock-format text input files.
- 030_ws3_libcbm_sequential-fromscratch.ipynb: his notebook creates the linkages between ``ws3`` and ``libcbm`` from scratch (i.e., all code required to create these linkages is developed directly in this notebook).
- 031_ws3_libcbm_sequential-builtin.ipynb: This notebook replicates what ``030_ws3_libcbm_sequential-fromscratch.ipynb`` does, but using ``ws3`` built-in ``CBM`` linkage functions.
- 040_ws3_libcbm_neilsonhack-fromscratch.ipynb: This notebook shows how to implement the Neilson hack (i.e., generate carbon yield curves from a CBM for use in a forest estate model) using ``ws3`` and ``libcbm``.


## Installation

Instructions on how to install the ws3 and any prerequisites can be find on  "example/000_venv_python_kernel_setup.ipynb".


## Usage

Instructions on how to use the project. Include examples and code snippets.

## Contributing

Feel free to contribute to the model if you have suggestions or improvements.

## License

MIT License
Copyright (c) 2015-2018 Gregory Paradis

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

- The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

- THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
 FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT.
IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.


## Acknowledgments

Acknowledge any individuals or organizations that contributed to the project.

## Contact

Contact information for questions, feedback, or issues related to the project: Gregory Paradis - gregory.paradis@ubc.ca
