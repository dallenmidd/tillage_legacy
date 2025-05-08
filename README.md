# Data and code for "Tillage leaves persistent legacies on old fields"
Mathematica code and outputs to reproduce the results in the manuscript "Tillage leaves persistent legacies on old fields." 
- `run_panel_simulations.nb` gives Mathemetica code to run the model for simulations whose results are displayed in Figures 1-3. Here six different ecological parameter combinations (perennial mortality is 25%, 50% or 75% and annual seed advantage is 2 or 4) are run for 30 different tillage regime parameters. The outputs are stored in `panel_simulations/`.
- `make_panel_plots.nb` gives the Mathematica code to make Figures 1-3. This uses the model run outputs in `panel_simulations/`.
- `run_timeseries_simulations.nb` gives Mathematica code to run the model simulations whose results are displayed in Figures 4-6 and Figures S1. The outputs are stored in `timeseries_simulations/`.
- `make_timezeries_plots.nb` gives Mathematica code to make Figures 4-6. This uses the model run outputs in `timeseries_simulations/`.
