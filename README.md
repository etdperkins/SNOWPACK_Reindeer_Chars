# SNOWPACK_Reindeer_Chars
Scripts for preparing CESM2 data for SNOWPACK and analyzing outputs for trends in reindeer-sensitive diagnostics.

**Scripts for preparing data from CESM2 for SNOWPACK:**  
* Script4SmetConversion.ipynb

**Scripts for processing outputs of SNOWPACK model:**  
* Script4ProfileConversion.ipynb - extracts relevant raw data from .pro file (ascii) and saves it as a csv file for easier manipulation
* Script4SnowDiagnostics.ipynb - computes diagnostics for problematic snow characteristics from data in csv file resulting from Script4ProfileConversion.ipynb and saves these diagnostics in a NetCDF file
* Script4BreakpointAnalysis.ipynb - analyses trends in the timeseries of problematic snow characteristics from data in NetCDF file resulting from Script4SnowDiagnostics.ipynb including automatic breakpoint detection
