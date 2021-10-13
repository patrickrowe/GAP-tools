# GAP-tools
A collection of miscellaneous scripts and tools for building GAP potentials


## ./scripts/
### /data_collation/
- Collate_Training_Database.ipynb
  - Take a large set of raw CP2K output, sort and filter and convert to GAP input format, with automatic selection of element-wise sigmas.
### /structure_generation/
- Random_Structure_Search_Cell_Generator.ipynb
  - Generate a large number of random bulk structures. Suitable for performing a random structure search to perform the first stages of GAP iterative training.
