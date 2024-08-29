<p align="center">
  <img src="icon.png" alt="Q-VS Icon" width="300" height="300" style="object-fit: cover;">
</p>

<div align="center">
    <img src="https://img.shields.io/github/v/release/Arifmaulanaazis/QVS" alt="GitHub release version">
    <img src="https://img.shields.io/github/release-date/Arifmaulanaazis/QVS" alt="GitHub Release Date">
    <img src="https://img.shields.io/github/last-commit/Arifmaulanaazis/QVS" alt="GitHub last commit">
    <img src="https://img.shields.io/github/downloads/Arifmaulanaazis/QVS/total" alt="GitHub Download count">
</div>



Q-VS is a powerful software application designed to determine the affinity of a specific receptor with multiple ligands simultaneously. Leveraging the robust capabilities of **AutoDock Vina V1.2.3** and **V1.1.2** as the backend engines, this application offers a streamlined solution for researchers in computational chemistry and drug discovery.

Developed using PyQt5 in the Python language, Q-VS provides an intuitive graphical user interface that makes complex molecular docking tasks more accessible. In addition to docking capabilities, Q-VS also includes specialized modules for secondary metabolite searches, ADMET predictions, ligand preparation, and molecular dynamics simulations.

## Features

- **Multi-Ligand Docking**: Simultaneously evaluate the binding affinity of numerous ligands to a specific receptor.
- **Metabolib**: Search for secondary metabolite databases and predict ADMET properties using compound similarity fingerprints. Users can search by plant Latin name, CID, or secondary metabolite name and export results to Excel.
- **Smiles2Structure**: Prepare ligands by converting SMILES strings to various file formats (PDB, PDBQT, SDF, MOL, MOL2) and generate 2D structural images. Users can customize minimization methods (MMFF94 or UFF) and set parameters like energy, conformer count, and maximum repetition.
- **Molecular Dynamic**: Run molecular dynamics simulations using Gromacs 2021.5, which is built for Windows. This feature integrates with CHARMM-GUI for preparation, allowing users to easily run MD simulations by providing the prepared files.
- **Integration with AutoDock Vina**: Supports both V1.2.3 and V1.1.2 versions for flexible docking simulations.
- **User-Friendly Interface**: Built with PyQt5, offering a modern and intuitive user experience.
- **Data Analysis and Visualization**: Includes tools for analyzing docking results and visualizing molecular interactions.
- **Report Generation**: Automatically generate detailed reports of docking results in various formats.


## Pre-installation Requirements

Before installing Q-VS, ensure that your system meets the following prerequisites:

- **Python**: Version 3.9 or higher. It is highly recommended to use [Anaconda](https://www.anaconda.com/products/distribution) or [Miniconda](https://docs.conda.io/en/latest/miniconda.html) for managing your Python environment, as they simplify package management and deployment.

  > **Note**: Anaconda and Miniconda come with many of the required packages pre-installed, reducing the setup time and potential conflicts.

- **Operating System**: Q-VS is now only available on windows.


## Requirements

Before running the application, ensure you have the following Python packages installed:

- `PyQt5`
- `PyQtWebEngine`
- `psutil`
- `openpyxl`
- `pyqtgraph`
- `tabulate`
- `pymol-open-source`
- `pandas`
- `python-docx`
- `svglib`
- `reportlab`
- `numpy`
- `dask`
- `matplotlib`
- `rdkit-pypi`
- `MGLTools`
- `pywin32`
- `qfluentwidgets`
- `qframelesswindow`
- `MDAnalysis`
- `prolif`


## Installation

To install the required dependencies, follow these steps:

1. **Create a Conda Environment**  
   Open your terminal or command prompt and create a new Conda environment:

   ```bash
   conda create -n qvs python=3.9
   conda activate qvs
   ```

2. **Install Dependencies**  
   Use the following command to install all required Python packages:

   ```bash
   pip install -r requirements.txt
   ```
   

## Setup

**Clone the Repository**

Clone this repository to your local machine using:

```bash
git clone https://github.com/Arifmaulanaazis/QVS.git
cd QVS
```


## Usage

To start the application, execute the `main.py` file:

```bash
python main.py
```

### Workflow

1. **Virtual Screening**  
   a. **Load Receptor and Ligands**  
      Import the receptor structure and a list of ligand structures you wish to screen.  
   b. **Select AutoDock Vina Version**  
      Choose between V1.2.3 or V1.1.2 for the docking process.  
   c. **Configure Docking Parameters**  
      Adjust parameters such as grid box size, exhaustiveness, and number of modes if necessary.  
   d. **Run Screening**  
      Initiate the screening process and monitor progress through the application's interface.  
   e. **Analyze Results**  
      Review docking scores, visualize binding poses, and export results for further analysis.  

2. **Metabolib**  
   a. **Search Database**  
      Input the plant Latin name, CID, or secondary metabolite name to search the database.  
   b. **Select Metabolite**  
      Choose a metabolite from the search results to view its details.  
   c. **ADMET Prediction**  
      Click on the selected metabolite to open a new window displaying ADMET data. Export search results to Excel if needed.  

3. **Smiles2Structure**  
   a. **Load SMILES List**  
      Select an Excel file containing the list of SMILES strings for the ligands you wish to prepare.  
   b. **Set Output Options**  
      Choose the output file formats (PDB, PDBQT, SDF, MOL, MOL2) and customization options like minimization method, energy, conformer count, and maximum repetition.  
   c. **Generate Structures**  
      Run the preparation process to generate 3D structures and 2D images, and optionally export the images to a Word document.  

4. **Molecular Dynamic**  
   a. **Prepare Input Files**  
      Use CHARMM-GUI or another third-party software to prepare the molecular dynamics simulation files.  
   b. **Load Prepared Files**  
      Input the folder/path containing the prepared files into the Molecular Dynamic menu of Q-VS.  
   c. **Run Simulation**  
      Start the molecular dynamics simulation using Gromacs 2021.5, and monitor progress until completion.  

## Contributing

We welcome contributions from the community! If you'd like to contribute, please follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Commit your changes (`git commit -am 'Add new feature'`).
4. Push to the branch (`git push origin feature-branch`).
5. Open a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact

For any questions or inquiries, please contact [Arif Maulana Azis](mailto:titandigitalsoft@gmail.com).

## Citation

If you use Q-VS in your research, please cite the following:

```bash
Dr.Dra. Azminah M.Si., apt. Arif Maulana Azis, S.Farm., Tegar Achsendo Yuniarta, S.Farm., M.Si, Dr.rer.nat. apt. Ratih. Q-VS V1.0.1. Surabaya, 2024.
```
