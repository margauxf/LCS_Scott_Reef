<h1> Dataset for the manuscript "Investigating transport in a tidally-driven coral atoll flow using Lagrangian Coherent Structures" </h1>

Data repository for the manuscript submitted to Geophysical Research Letters.

<h2>Drifter data</h2>

The observed drifter trajectories can be found at [AUS_Drifters_unshifted.mat].

Data collected by:
Margaux Filippi, margaux@mit.edu, Massachusetts Institute of Technology/Woods Hole Oceanographic Institution
Thomas Peacock, tomp@mit.edu, Massachusetts Institute of Technology
Ryan Lowe, ryan.lowe@uwa.edu.au, The University of Western Australia
Greg Ivey, greg.ivey@uwa.edu.au, The University of Western Australia
James Gilmour, j.gilmour@aims.gov.au, Australian Institute of Marine Science 

The drifter trajectories were collected during an  Australian Institute of Marine Science cruise around Scott Reef, Western Australia, in October 2016. The drifters were released on October 2nd (first 9 drifters) and October 3rd (next 12 drifters). The dataset here has been cropped to the first two months. 

- [master/AUS_Drifters.png] shows all the trajectories.
- [master/AUS_Drifters_temporal-res.png] shows the individual temporal resolution (i.e., all time datapoints) for each trajectory (start position), for both days of releases.
- [master/AUS_Drifters.mat] contains the following variables:
  - the positions of each individual trajectory are in the cell named Drifters_traj_2mo;
  - the longitudes and latitudes are in the matrices x-longitudes and y-latitudes, respectively, with the rows corresponding to the drifter numbers and the columns to the time stamps;
  - t_array2 contains the time array in MATLAB's <i>datenum</i> format. The increment is one minute. The start and end times are 02-Oct-2016 14:46:00 and 02-Dec-2016 14:46:00, respectively.



<h2>Velocity data</h2>

The numerical velocity fields from the SUNTANS model [[Rayson et al., 2019]](https://doi.org/10.1016/j.ocemod.2017.12.007) can be found on the THREDDS server hosted by the [Shadden Lab at Berkeley](https://shaddenlab.berkeley.edu/) :
- The surface velocity fields can be accessed [here](http://transport.me.berkeley.edu/thredds/catalog/public/ScottReef/catalog.html?dataset=public/ScottReef/ScottReef3D_250m_201610_surface_uv_nodes_newgrid_trimmed.nc).
- The non-divergent components of the above velocity fields can be accessed [here](http://transport.me.berkeley.edu/thredds/catalog/public/ScottReef/catalog.html?dataset=public/ScottReef/ScottReef_channel_nondivergent.nc).


<h3>Reference</h3>
M. D. Rayson, G. N. Ivey, N. L. Jones and O. B. Fringer. Resolving high-frequency internal waves generated at an isolated coral atoll using an unstructured grid ocean model. <i>Ocean Modelling</i>, 12267-84, 2018.
