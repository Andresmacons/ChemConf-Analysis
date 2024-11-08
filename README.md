# ChemConf-Analysis
Combined Python/Linux scritp for conformational analysis of a xyz file containing multiple structures, based on RMSD and additional geometrical constrains.

Available for Jupyter Notebooks and command lines, including:

## Instructions

- Get your .xyz file with multiple structures. Make sure the .xyz file saved the geometries in the proper format, including atom number and energy. This is crucial for line counting and slicing the document.
- Run the script. It will create the required new folders:
- Once finishing, you will obtain the .xyz files for every "unique" conformer in the file.

## Requirements
- Python
- Linux

## License
ChemConf-Analysis is freely available under an [MIT](https://choosealicense.com/licenses/mit/) license

## Reference
If you use any ChemConf-Analysis, please include this citation:

Additionally, please include the corresponding references for the following programs:
- Chemcoord: [paper](https://doi.org/10.1002/jcc.27029) and [documentation](https://chemcoord.readthedocs.io/en/v2.1.2/)
- Pandas: [documentation](https://pandas.pydata.org/docs/) and Zenodo repository [link](https://doi.org/10.5281/zenodo.13819579)
- Numpy: [paper](https://doi.org/10.1038/s41586-020-2649-2) and [documentation](https://numpy.org/)
