# Single Grid Plot
The script single_grid_plot.py plots an inputted grid of Latitude, Longitude and Value on the specified project. 
The script is setup to take in GOCE dataset, the same format as the SECS and EICS data. Where columns 1-7 are 
reserved for the date and time. **The latitude and longitude columns are 7 and 8**. The value to be plotted on the 
corresponding coordinates can be specified in the function. 

Usage
------

1. First load the grid as a numpy array. 
    ` example_grid = np.loadtxt('example_grid.txt')`
    
2.  There is one main function in the script polar_plot() its syntax is as:
    `polar_plot([grid],[column to plot],"figure title","figure filename")`
    
Example plot:
-------------
<img src="https://github.com/sonalranjit/GOCE_SECS-EICS/blob/master/Single_grid_plotter/figs/GOCE_asc_030411_polar.png" width="700" height="700" align="middle")/>