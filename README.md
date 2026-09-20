# Green-inequality

This code is for analyzing the seasonal urban greenspace dynamics in global human settlements (2019-2025). 

Seasonal urban greenspace was mapped using the 20 m Copernicus Sentinel-2 Surface Reflectance (L2A) dataset, which offers a nominal 5-day revisit cycle. Specifically, urban vegetation was isolated using the native Scene Classification Layer (SCL) produced by the Sen2Cor algorithm, extracting pixels classified explicitly as vegetation (SCL = 4). Comprehensive mathematical formulations and decision-tree architectures of the Sen2Cor SCL algorithm are detailed in https://step.esa.int/thirdparties/sen2cor/2.3.0/%5BL2A-ATBD%5D%20S2PAD-ATBD-0001%20%5B2.0%5D.pdf.

Relevant data can be found in the Zenodo: https://zenodo.org/records/19343115.
