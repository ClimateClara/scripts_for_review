These are the scripts to produce the figures and analysis of the paper "Ocean warming threatens the viability of 60% of Antarctic ice shelves"
==============================================================================================================================================


Information
-----------

Hello! These are the scripts used for the figures and the analysis of the manuscript on ice-shelf viability.

- Figure 2 and 3 were done with ``/notebooks_for_figures/timeseries_nb_viable_isf_withoutGISS_withhydrofrac_calving0.ipynb`` and ``/notebooks_for_figures/2D_subplots_viability_proba_withoutGISS_calving0.ipynb``
- Figure 4 was done with ``/notebooks_for_figures/2D_subplots_viability_proba_withoutGISS_calving0.ipynb``
- Figure 5 was done with ``/notebooks_for_figures/timeseries_nb_viable_isf_withoutGISS_withhydrofrac_calving0.ipynb`` and ``notebooks_for_figures/2D_subplots_viability_proba_onlyhydrofrac.ipynb``

- Extended Data Figures 1 to 4 were done with ``/notebooks_for_figures/plot_mass_fluxes.ipynb``
- Extended Data Figure 5 was done with ``/notebooks_for_figures/timeseries_nb_viable_isf_withoutGISS_withhydrofrac_calving0.ipynb``
- Extended Data Figure 6 was done with ``/notebooks_for_figures/timeseries_nb_viable_isf_withoutGISS_withhydrofrac.ipynb`` and ``/notebooks_for_figures/2D_subplots_viability_proba.ipynb``
- Extended Data Figure 7 was done with ``/notebooks_for_figures/2D_subplots_viability_proba.ipynb``
- Extended Data Figure 8 was done with ``/notebooks_for_figures/timeseries_nb_viable_isf_withoutGISS_withhydrofrac_ElmerIcegeometries.ipynb`` and ``/notebooks_for_figures/2D_subplots_viability_proba_withoutGISS_ElmerIcegeometries.ipynb``
- Extended Data Figures 10 to 12 were done with ``/notebooks_for_figures/histo_weights_new.ipynb``

In the folder ``notebooks_for_datapreparation``, you will find a few scripts to prepare the data. These are not as detailed and not meant to be run out of the box but permit to give insight into the practical application of the methods described in the paper. For potential inspiration of similar work :)

DATA
----

The associated data can be found on Zenodo: https://doi.org/10.5281/zenodo.16422169.

This is data prepared for the scripts above and is based on models and simulation output presented in previous publications: the ocean model NEMO (`Burgard et al. 2022 <https://doi.org/10.5194/tc-16-4931-2022>`_, `Mathiot and Jourdain 2024 <https://doi.org/10.5194/os-19-1595-2023>`_), the physics- and AI-based basal melt parameterisations (`Burgard et al. 2022 <https://doi.org/10.5194/tc-16-4931-2022>`_, `Burgard et al. 2023 <https://doi.org/10.1029/2023MS003829>`_) , the regional atmospheric model MAR (`Kittel et al. 2021 <https://doi.org/10.5194/tc-15-1215-2021>`_), the ice-sheet model Elmer/Ice (e.g. `Gagliardini et al. 2013 <https://doi.org/10.5194/gmd-6-1299-2013>`_, `Seroussi et al. 2024 <https://doi.org/10.1029/2024EF004561>`_ ), the hydrofracturing criterion estimation (`Jourdain et al. 2025 <https://doi.org/10.5194/tc-19-1641-2025>`_), the `CMIP6 data <https://esgf-node.ipsl.upmc.fr/search/cmip6-ipsl/>`_.  Observational estimates were taken from `Davison et al. 2023 <https://doi.org/10.1126/sciadv.adi0186>`_.

To run the scripts above with the data provided, do not forget to change the inputpath in the beginning of the scripts!

PACKAGES NEEDED
---------------

The .ipynb files can be run by launching a JupyterLab instance in this folder after downloading it. Instructions to install JupyterLab can be found here: https://jupyter.org/install.

via ``conda install``:

- xarray version 2022.11.0
- numpy version 1.23.5
- tqdm version 4.65.0
- matplotlib version 3.7.2
- seaborn version 0.12.2

via ``pip install``:

- multimelt version 0.4

