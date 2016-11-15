## Synopsis

<p>Python code for producing plots of AFM data. The data files are txt files output from Gwyddion after processing (e.g. flattening, 
aligning rows, etc). The txt should be output with a header; this header information is used to scale the axes correctly. 
The exact plotting range can also be adjusted by changing the values of Select_xi, Select_xf, Select_yi, and Select_yf. The
contrast can be adjusted by uncommenting the line with the setting im.set_clim(np.min(Data),20) and changing the numerical value used.</p>

<p> This code can be easily extended to handle other types of 2D data.</p>

## License
MIT license.
