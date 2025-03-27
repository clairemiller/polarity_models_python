# Polarity Models Python
Code to run various polarity models.

Models contained in `src/models/`.
Code to run models in `src/tasks/`.

Run by doing ```python -m src.tasks.<filename_without_extension>```

Figures in paper are generated by tasks
- `gen_maintenance_fig.py`
- `gen_polarisation_illustration_fig.py`
- `gen_scribble_downreg_koffP.py`
- `gen_scribble_downreg_rhop.py`
- `gen_downregulation_scribble_and_pkc.py`
- `gen_emergence_timeslice_fig.py`
- `comparison_par3addition_goehring.py`

The file `src/figure_helper.py` is used for commonly used colours and labels across figures.

Note that generated savedata filenames are not necessarily unique. It is possible that a change to initial condition or parameters might not change the filename. Be suspicious if you change something and it doesn't rerun the simulation.

#### Dependencies
- scipy (v1.15.2)
- matplotlib (v3.10.0)
- numpy (v2.2.3)
