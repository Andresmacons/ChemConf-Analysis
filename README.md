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

## Reference
If you use any ChemConf-Analysis, please include this citation:

Additionally, please include the corresponding references for the following programs:
- Chemcoord: O. Weser, B. Hein-Janke, R. A. Mata, J. Comput. Chem. 2023, 44(5), 710. https://doi.org/10.1002/jcc.27029 
- Pandas: The pandas development team. (2024). pandas-dev/pandas: Pandas (v2.2.3). Zenodo. https://doi.org/10.5281/zenodo.13819579
- Numpy: Harris, C.R., Millman, K.J., van der Walt, S.J. et al. Array programming with NumPy. Nature 585, 357–362 (2020). https://doi.org/10.1038/s41586-020-2649-2
