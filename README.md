# Uncertainty-Aware Reconstruction of Generator Bearing Temperatures from Operational Datasets in Hydropower Systems

GitHub Repository for the paper of the bearing temperature reconstruction of the Grunnai Hydropower Plant


**Definition**: The frequent start-stop cycles and sustained off-nominal operation pose significant wear on electro-mechanical components of the hydroelectric power plant. Bearing temperature channels are the primary continuous indicator of generator mechanical health in most plant configurations. The research questions (RQs): Can the generator bearing temperatures be reconstructed from the remaining SCADA instrumentation? How can uncertainties propagate into the inputs carrying the reconstruction information? 

---

### Directory Organization
```
Home/
├── Input_Data/                         # Datasets
├── Publication_Figures/                # Generated figures for the paper in pdf/png format
├── Grunnai_G2_PESGM2027_d102026.ipynb  # Main Jupyter notebook
├── requirements.txt                    # Python dependencies
└── README.md                           # Project documentation
```

### How to run

1. Environment Setup (Using pip)
```
cd C:\Users\...\<full_path_to_.txt_file>
pip install -r requirements.txt
```

2. Open and work with the Jupyter notebook

Navigate to the dataset directory and load data into the notebook.
```
folder_path = r"C:\Users\...\<dataset>
```

### Version History

| Author   | Version | Date       | Change                                         |
|--------  |---------|------------|------------------------------------------------|
| Duy Tran | 1.0     | 28.05.2026 | The original algorithm                         |
| Duy Tran | 1.1     | 02.10.2026 | Finalize the script for conference submission  |

### Contribution

This is a reproducible notebook for one of the paper used in the PhD research of the author. 
For questions or collaboration:

Author: Duy Tran
Main Supervisor: Thomas Øyvang
Co-Supervisor: Sambeet Mishra
Institution: University of South-Eastern Norway

### Citation and License

Please cite the below publication if you use this repository. The code is released under the MIT License, meaning users are free to use and modify it with explicit citation or written permission.

[Article_Link_to_be_updated_soon](https://doi.org/)

```
To be updated
```

If you find this work useful, please consider starring the repository!
Best from the authors