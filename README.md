# Q-VS

Q-VS is a powerful software application designed to determine the affinity of a specific receptor with multiple ligands simultaneously. Leveraging the robust capabilities of **AutoDock Vina V1.2.3** and **V1.1.2** as the backend engines, this application offers a streamlined solution for researchers in computational chemistry and drug discovery.

Developed using PyQt5 in the Python language, Q-VS provides an intuitive graphical user interface that makes complex molecular docking tasks more accessible.

## Features

- **Multi-Ligand Docking**: Simultaneously evaluate the binding affinity of numerous ligands to a specific receptor.
- **Integration with AutoDock Vina**: Supports both V1.2.3 and V1.1.2 versions for flexible docking simulations.
- **User-Friendly Interface**: Built with PyQt5, offering a modern and intuitive user experience.
- **Data Analysis and Visualization**: Includes tools for analyzing docking results and visualizing molecular interactions.
- **Report Generation**: Automatically generate detailed reports of docking results in various formats.

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

## Installation

To install the required dependencies, use the following command:

```bash
pip install -r requirements.txt
```

## Setup

1. **Clone the Repository**

   Clone this repository to your local machine using:

   ```bash
   git clone https://github.com/Arifmaulanaazis/Q-VS.git
   cd Q-VS
   ```

2. **Prepare AutoDock Vina**

   Ensure that AutoDock Vina V1.2.3 or V1.1.2 is correctly installed on your system and accessible via the command line. You can download AutoDock Vina from [their official website](http://vina.scripps.edu/).

## Usage

To start the application, execute the `main.py` file:

```bash
python main.py
```

### Workflow

1. **Load Receptor and Ligands**: Import the receptor structure and a list of ligand structures you wish to screen.

2. **Select AutoDock Vina Version**: Choose between V1.2.3 or V1.1.2 for the docking process.

3. **Configure Docking Parameters**: Adjust parameters such as grid box size, exhaustiveness, and number of modes if necessary.

4. **Run Screening**: Initiate the screening process and monitor progress through the application's interface.

5. **Analyze Results**: Review docking scores, visualize binding poses, and export results for further analysis.

6. **Generate Reports**: Create comprehensive reports that summarize the screening outcomes, including tables and charts.

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
Dr.Dra. Azminah M.Si., Arif Maulana Azis, S.Farm., Tegar Achsendo Yuniarta, S.Farm., M.Si, Dr.rer.nat. apt. Ratih. Q-VS V1.0.1. Surabaya, 2023.
```

