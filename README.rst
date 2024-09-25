These are the scripts to produce the figures and analysis of the manuscript in review
=====================================================================================


Information
-----------

Hello! These are the scripts used for the figures and the analysis of the manuscript on ice-shelf viability.

- Figure 2 was done with ``/notebooks_for_figures/timeseries_nb_viable_isf_withoutGISS_withhydrofrac.ipynb`` and ``/notebooks_for_figures/2D_subplots_viability_proba.ipynb``
- Figure 3 was done with ``/notebooks_for_figures/2D_subplots_viability_proba.ipynb``
- Figure S1, S2 and S3 were done with ``/notebooks_for_figures/timeseries_nb_viable_isf_withhydrofrac.ipynb``
- Figure S4, S5, S6, and S7 were done with ``/notebooks_for_figures/plot_mass_fluxes.ipynb``
- Figure S8 was done with ``/notebooks_for_figures/timeseries_nb_viable_isf_withhydrofrac.ipynb`` and ``/notebooks_for_figures/2D_subplots_viability_proba_onlyhydrofrac.ipynb``


DATA
----

The associated data can be found on Zenodo: https://doi.org/10.5281/zenodo.13768759.

This is data prepared for the scripts above and is based on models and simulation output presented in previous publications: the ocean model NEMO (`Burgard et al. 2022 <https://doi.org/10.5194/tc-16-4931-2022>`_, `Mathiot and Jourdain 2024 <https://doi.org/10.5194/os-19-1595-2023>`_), the physics- and AI-based basal melt parameterisations (`Burgard et al. 2022 <https://doi.org/10.5194/tc-16-4931-2022>`_, `Burgard et al. 2023 <https://doi.org/10.1029/2023MS003829>`_) , the regional atmospheric model MAR (`Kittel et al. 2021 <https://doi.org/10.5194/tc-15-1215-2021>`_), the ice-sheet model Elmer/Ice (e.g. `Gagliardini et al. 2013 <https://doi.org/10.5194/gmd-6-1299-2013>`_, `Seroussi et al. 2024 <https://doi.org/10.1029/2024EF004561>`_ ), the hydrofracturing criterion estimation (`Jourdain et al. 2024 <https://doi.org/10.5194/egusphere-2024-58>`_), the `CMIP6 data <https://esgf-node.ipsl.upmc.fr/search/cmip6-ipsl/>`_.  Observational estimates were taken from `Davison et al. 2023 <https://doi.org/10.1126/sciadv.adi0186>`_.

To run the scripts above with the data provided, do not forget to change the inputpath in the beginning of the scripts!


PACKAGES NEEDED
---------------

via ``conda install``:

- xarray version 2022.11.0
- numpy version 1.23.5
- tqdm version 4.65.0
- matplotlib version 3.7.2
- seaborn version 0.12.2

via ``pip install``:

- multimelt version 0.4
