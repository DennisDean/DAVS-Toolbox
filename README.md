DAVS-Toolbox
============

Data Access and Visualization for Sleep Toolbox

#### Overview
The DAVS-Toolbox is a collection of MATLAB scripts and GUIs for accessing and visualizing polysnonmography (PSG) data. Each of the routines include test scripts and test files which allow the user to evaluate performance, verify steps and serve as a brief tutortial for most programmers.

MATLAB script files are available for each of the DAVS-toolbox components.  Click on the component name to access the prefferred download site. Components are posted on the MATLAB file exchange website adn on GITHUB. It is reccomended that the MATLAB website be used to download if available. Links to the GITHUB site for MATLAB deposited routines are also provided for individuals who wish to contribute bug fixes, revisions and extensions. 


Data Access
- [BlockEdfLoad](http://www.mathworks.com/matlabcentral/fileexchange/42784-blockedfload) ( [git](https://github.com/DennisDean/BlockEdfLoad)). An efficient EDF loader that provides several options for accessing header and signal information stored in an EDF file. Specific signals and selected 30 second epochs can be retrieved.
- [BlockEdfLoadClass](http://www.mathworks.com/matlabcentral/fileexchange/45227-blockedfloadclass) ([git](https://github.com/DennisDean/BlockEdfLoadClass/)). Class version of blockEdfLoad. Dependent variables are added that provide quick access to EDF header content. The class includes an EDF checker and support for creating EDF file lists. 
- [BlockEdfWrite)](http://www.mathworks.com/matlabcentral/fileexchange/46339-blockedfwrite) ([git](https://github.com/DennisDean/BlockEdfLoadClass/)). An EDF creation function designed to worked in conjunction with BlockEdfLoad and BlockEdfLoadClass. The function can be used to record experimental data and to generate test data.  

Data Manipuation
- [BlockEdfDeidentify](http://www.mathworks.com/matlabcentral/fileexchange/46423-blockedfdeidentify) ([git](https://github/DennisDean/BlockEdfDeidentify/)). Function over-writes the subject id and study date fields in the EDF header. 
- [BlockEdfSummarizeClass](https://github.com/DennisDean/BlockEdfSummarizeClass). BlockEdfSummarizeClass can be used to summarize the contents of a folder which contains EDF wiles with the associated annotation file (XML) files. The class is configured to create header and signal summaries, which are written to excel files. An EDF check summary, which compares the EDF content to the EDF specification, can be exported to an EXCEL file.
- [GetMatchedSleepEdfXmlFiles](https://github.com/DennisDean/GetMatchedSleepEdfXmlFiles). Function searches recurrsively within a folder for EDF files. The function assumes EDF files are named as 'prefix'.* and that annotation files are stored in the same folder as the EDF.  The function assumes annotaion files are stores as XML files ('prefix'.XML.edf). Note that the assumed file structure is designed to work with data formats supported by the [National Sleep Research Resource](https:\\sleepdata.org\). 

Data Visualization
- [BlockEdfSignalRasterView](http://www.mathworks.com/matlabcentral/fileexchange/46366-blockedfsignalrasterview) ([git](https://github.com/DennisDean/BlockEdfSignalRasterView)). Creates raster plots from signal data stored within an EDF file. Raster plots are sometimes referred to as waterfall plots. 
- [BlockEdfSignalHeatMapView](http://www.mathworks.com/matlabcentral/fileexchange/46417-blockedfheatmapview) ([git](https://github.com/DennisDean/BlockEdfSignalRasterView)). Creates heatmaps of signal data stored within an EDF file. 

Data Utilities
- [SignalRasterView](http://www.mathworks.com/matlabcentral/fileexchange/46420-blockedfsignalrasterview) ([git](http://github.com/DennisDean/SignalRasterView)). SignalRasterViewFig is a utility for investigating the contents of an EDF file.  The utility (GUI) can be used to compare the EDF contents to the EDF specification, view the EDF headers, to create raster plots of the EDF signals and to create a power point summary of the generated raster plots. 
- [BlockEdfSummarizeFig](https://github.com/DennisDean/BlockEdfSummarizeFig). The simple GUI can be used to summarize and check EDF files stored within a folder.
