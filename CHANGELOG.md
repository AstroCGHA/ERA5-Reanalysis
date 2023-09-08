This file encapsulates all of the notable changes of each notebook on this repository.

## As of Sept. 8, 2023

Tweaks(s)
1. Changes to the wind units into 'kt' in Surf. Wind & SWEAT Index notebook.
2. Added a notebook for Barotropic and Baroclinic Potential Vorticity (PV).

Note: Baroclinic PV has pressure level limits to 100-hPa while the other is at 500-hPa for visualization/analysis purposes in this case.

## As of July 20, 2023

Major Tweak(s):
1. Revised the notebook for SRH incorporating and visualizing RM and LM components using Bunkers Internal Dynamics (ID) Method.
2. Changed the method of calculating mean winds in the (1) Bunkers ID & SRH, (2) MSLP, Winds, BRN Shear, and (3) Updraft, EHI, SCP notebooks. Now using numpy with proper indexing.
3. Utilized smooth_n_point to various parameters i.e. evident in MSLP, Winds, BRN Shear notebook.
4. Added a BRN dimensionless parameter. Uncomment if need.
5. Proper units and calculation of composite parameters without calling the magnitude function to make arrays dimensionless.
6. Tweaked the date and time of the Winds & SWEAT Index parameter.
7. Cleared some extraneous 'comments' in the notebooks.

## As of July 9, 2023

Tweak(s):
1. Added a notebook for 0-3 km Streamwise Helicity and 0-500 m Streamwise Vorticity.

## As of June 30, 2023

Tweak(s):
1. Added a notebook for 0-6 km Mean Storm Motion and both 0-1 & 0-3 km Storm-Relative Helicity (SRH).

## As of April 6, 2023

Tweak(s):
1. Changes to the notebook involving Mean Precipitation. New custom cmaps at various rates.
2. Adjusted gaussian smoothing to most of the ERA5 Re notebooks.
3. Subtle changes to plot titles involving symbols instead of proxy abbreviations.
4. Reversed the color scheme in Atmospheric Thickness to accomodate temperature variation.
