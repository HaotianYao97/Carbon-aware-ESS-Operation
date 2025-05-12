This repository contains a carbon-aware ESS operation framework. It optimizes ESS operation using real-time energy prices and marginal emission intensity data.

Files Description
main.ipynb — The main executable Jupyter Notebook.

HOEP.csv — Dataset containing the Hourly Ontario Energy Price (HOEP), used as the electricity price signal in the optimization.

Main_EI.csv — Dataset of hourly marginal emission intensity (MEI) of the Ontario grid, used to quantify the environmental impact of ESS operations.

To execute the simulation:
1. Ensure HOEP.csv and Main_EI.csv are placed in the same directory as main.ipynb.
2. Run main.ipynb directly.
