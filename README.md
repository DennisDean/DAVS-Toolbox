DAVS-Toolbox
============

Data Access and Visualization for Sleep Toolbox

#### Overview
The DAVS-Toolbox is a collection of MATLAB scripts and GUIs for accessing and visualizing polysnonmography (PSG) data. Each of the routines include test scripts and test files which allow the user to evaluate performance, verify steps and serve as a brief tutortial for most programmers.

Data Access Utilities
- [BlockEdfLoad](http://www.mathworks.com/matlabcentral/fileexchange/42784-blockedfload). An efficient EDF loader that provides several options for accessing header and signal information stored in an EDF file. Specific signals and selected 30 second epochs can be retrieved.
- [BlockEdfLoadClass](http://www.mathworks.com/matlabcentral/fileexchange/45227-blockedfloadclass). Class version of blockEdfLoad. Dependent variables are added that provide quick access to EDF header content. The class includes an EDF checker and support for creating EDF lists. 
- [BlockEdfWrite)](http://www.mathworks.com/matlabcentral/fileexchange/46339-blockedfwrite). An EDF creation function designed to worked in conjunction with BlockEdfLoad and BlockEdfLoadClass. The function can be used to record experimental data and generate test data. 

Data Manipuation
- [BlockEdfDeidentify](http://www.mathworks.com/matlabcentral/fileexchange/46423-blockedfdeidentify). Function over-writes the subject id and study date fields in the EDF header.
- [BlockEdfSummarizeClass](https://github.com/DennisDean/BlockEdfSummarizeClass). BlockEdfSummarizeClass can be used to summarize the contents of a folder which contains EDF wiles with the associated annotation file (XML) files. The class is configured to create header and signal summaries, which are written to excel files. An EDF check summary, which compares the EDF content to the EDF specification, can be exported to an EXCEL file.
- [GetMatchedSleepEdfXmlFiles](https://github.com/DennisDean/GetMatchedSleepEdfXmlFiles). Function searches recurrsively within a folder for EDF files. The function assumes EDF files are named as 'prefix'.* and that annotation files are stored in the same folder as the EDF.  The function assumes annotaion files are stores as XML files ('prefixe'.XML.edf).

Data Visualization
- [BlockEdfSignalRasterView](http://www.mathworks.com/matlabcentral/fileexchange/46366-blockedfsignalrasterview). 
- [BlockEdfSignalHeatMapView](http://www.mathworks.com/matlabcentral/fileexchange/46417-blockedfheatmapview). 

Utilities
- [SignalRasterView](http://www.mathworks.com/matlabcentral/fileexchange/46420-blockedfsignalrasterview). 
- [BlockEdfSummarizeFig](https://github.com/DennisDean/BlockEdfSummarizeFig). 
