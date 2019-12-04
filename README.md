# Reshape-Triggered-Data-from-MATLAB-Data-Acquisition-Toolbox
This is a utility function for use with the Data Acquisition Toolbox for MATLAB. 

When you use an analoginput object from the Data Acquisition Toolbox to capture data which which spans multiple triggers, the data from each trigger is separated by NaNs. This function strips out the NaNs and reshapes the data, adding one dimension for trigger. There will be one "column" in the extra dimension for each trigger, yielding an output array of size NSamples x NChannels x NTriggers.

[![View Reshape triggered data acquisition analog input data on File Exchange](https://www.mathworks.com/matlabcentral/images/matlab-file-exchange.svg)](https://www.mathworks.com/matlabcentral/fileexchange/2184-reshape-triggered-data-acquisition-analog-input-data)
