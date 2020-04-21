<h1> Drifter dataset for the manuscript "Investigating transport in a tidally-driven coral atoll flow using Lagrangian Coherent Structures" </h1>

The observed drifter trajectories can be found in [Drifter_trajectories.mat](https://github.com/NSF-ALPHA/LCS_Scott_Reef/blob/master/Drifter_data/Drifter_trajectories.mat). Details about the variables contained in the MATLAB file are below.

Data collected by Margaux Filippi, margaux@mit.edu, Massachusetts Institute of Technology/Woods Hole Oceanographic Institution.

Resources provided by:
- Thomas Peacock, tomp@mit.edu, Massachusetts Institute of Technology
- Ryan Lowe, ryan.lowe@uwa.edu.au, The University of Western Australia
- Greg Ivey, greg.ivey@uwa.edu.au, The University of Western Australia
- James Gilmour, j.gilmour@aims.gov.au, Australian Institute of Marine Science 

The drifter trajectories were collected during an  Australian Institute of Marine Science cruise around Scott Reef, Western Australia, in October 2016. The drifters were released on October 2nd (first 9 drifters) and October 3rd (next 12 drifters). The dataset here has been cropped to the first two months. 

- [Drifter_trajectories.png](https://github.com/NSF-ALPHA/LCS_Scott_Reef/blob/master/Drifter_data/Drifter_trajectories.png) shows all the trajectories.
- [Drifter_trajectories_temporal_resolution.png](https://github.com/NSF-ALPHA/LCS_Scott_Reef/blob/master/Drifter_data/Drifter_trajectories_temporal_resolution.png) shows the individual temporal resolution (i.e., all time datapoints) for each trajectory (start position), for both days of releases.
- [Drifter_trajectories.mat](https://github.com/NSF-ALPHA/LCS_Scott_Reef/blob/master/Drifter_data/Drifter_trajectories.mat) contains the following variables:
  - the positions of each individual trajectory are in the cell named Drifters_traj_2mo;
  - the longitudes and latitudes are in the matrices x-longitudes and y-latitudes, respectively, with the rows corresponding to the drifter numbers and the columns to the time stamps;
  - t_array2 contains the time array in MATLAB's <i>datenum</i> format. The increment is one minute. The start and end times are 02-Oct-2016 14:46:00 and 02-Dec-2016 14:46:00, respectively.
