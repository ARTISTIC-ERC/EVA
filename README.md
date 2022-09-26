![Background_web](https://user-images.githubusercontent.com/50483699/180805030-8540f956-fc86-4fc8-a21b-0caf4a75cac3.jpeg)

Electrochemistry Visualization Application
========================================================
This software is dedicated to electrochemical data analysis.
Cycling experiments are often used to follow the evolution of the capacity of a given cell under certain conditions. Electrochemical data may contain though further information about the cell, which can be obtained via deeper analysis techniques. Two of them are the Incremental Capacity Analysis (ICA or dQ/dV x V) and the Differential Voltage Analysis (DVA or dV/dQ x Q). Through them one can check in more details the traits of the Potential x Capacity curve during constant current steps. This program offers the user the possibility of obtaining the ICA and DVA curves of cycling data without data treatment. It also offers the possibility of fitting the linear contributions of the DVA data from positive and negative half cells to the data of their respective full cell, through the slippage and active material mass variables.
This is an alpha version of the software.

_version_ = 1.1.0

[![DOI](https://zenodo.org/badge/517703585.svg)](https://zenodo.org/badge/latestdoi/517703585)


Dependencies
========================================================
The software is available under Linux and Windows distributions. You can download the executable or
the package respectively for Windows or Linux to install the dependencies on your own computer. Please note that
this software is only available for Windows version up to 10.

How to use
========================================================
- For **windows**, download the executable on your computer and launch it.
- For **linux**, download the package and launch the following command line in the same
folder with sudo rights :
  
```bash
sudo dpkg -i ElectrochemistryVisualizationApplication.deb
```

 Contributors
========================================================
  - **Marc Duquesnoy** (@MarcDuquesnoy), marc.duquesnoy@u-picardie.fr
  - **Matheus Leal De Souza** , matheus.leal.de.souza@u-picardie.fr
  - **Mathieu Morcrette**, mathieu.morcrette@u-picardie.fr
  - **Alejandro A. Franco**, alejandro.franco@u-picardie.fr

This project was developed in collaboration with the prototyping unit from 
the LRCS (Amiens, FRANCE).

 
 Licence
========================================================

This repository is under the [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/) licence.