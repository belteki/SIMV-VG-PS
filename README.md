# SIMV-VG-PS
Jupyter Notebooks used for processing and analysis of ventilator parameters and carbon dioxide measurements in infants receiving **SIMV-VG ventilation with pressure support** used on spontaneous breaths

This repository contains the Python code used for data processing, statistical analysis and visualization described in the following paper:

Balajthy A, Balazs G, Kovacs T, Belteki G. Synchronized intermittent mandatory ventilation with volume guarantee and pressure support in neonates: Detailed analysis of ventilator parameters. *Pediatr Pulmonol.* 2023 Mar 17. doi: 10.1002/ppul.26384. Epub ahead of print. PMID: 36929855.

Link to the paper: [https://fn.bmj.com/content/early/2022/06/14/archdischild-2021-323498](https://fn.bmj.com/content/early/2022/06/14/archdischild-2021-323498)

Contact: gusztav.belteki@addenbrookes.nhs.uk; gbelteki@aol.com

____


The outputs (numbers, tables, graphs) of the cells of the Jupyter Notebooks
(.ipynb files) have been suppressed in order to comply with copyrights.
Some of the corresponding data and graphs can be found in the paper and its
only supplementary material.

This code can be viewed in any web browser. If the code is displayed (rendered)
in Github, copy and paste the URL (web adress) of the Notebook into [nbviewer](https://nbviewer.jupyter.org) for a read-only display.

To run the code, you can use Jupyter install locally on your computer or [Google Colab](https://colab.research.google.com).

Raw data are not shared but the user can run the code on his or her own data obtained in the same format.

____

Packages required to run this Notebook:

Python version: 3.9.12

pandas version: 1.4.4.

matplotlib version: 3.6.2

NumPy version: 1.21.5

I recommend downloading these packages using the freely availably Anaconda
built: https://www.continuum.io/downloads

____

# Jupyter Notebooks

1. [Recording_list_debrecen](Recording_list_debrecen.ipynb): Generates a list of all recordings and export it as a text file.

2. [Clinical_details_processing debrecen](Clinical_details_processing_debrecen.ipynb): Imports and processes the clinical data for these recordings and exports them as an edited Excel and csv files.

3. [Carbon_dioxide data_processing_debrecen](Carbon_dioxide_data_processing_debrecen.ipynb): For the list of patients with clinical details available, imports the blood gases the and transcutnaeous data, performs initial processing on them and exports them as pickle archives.

4. [Transcutaneous_CO2_data_processing](Transcutaneous_CO2_data_processing.ipynb): Further processing the transcutaneous CO2 data.

5. [SIMV_VG-PS_processing](SIMV_VG_PS_processing.ipynb): Processing the recordings containing SIMV-VG-PS ventilation mode

6. [SIMV_VG-PS_analysis](SIMV_VG_PS_analysis.ipynb): Analysis of the recordings containing SIMV-VG-PS ventilation mode

7. [SIMV_VG_PS_E_Figure_1](SIMV_VG_PS_E_Figure_1.ipynb): Generate **E_Figure 1** of the SIMV-VG-PS paper
