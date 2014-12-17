Use xfig to edit pictures: http://www.xfig.org/

Text in pictures should have the hidden “special” flag set. Save the .fig and export as “combined PS/Latex (both parts)”. This should leave you with a .pstex and a .pstex_t file. To then turn this into a pdf, run “./makepdf <examplename>” where <examplename>.fig is the figure that you started with.




