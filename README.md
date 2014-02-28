DH Curation Guide Data Conversion Project
================

Date: 2014-02-28

Contact: Trevor Muñoz, tmunoz@umd.edu

Description: Content from Version 1 of the [DH Curation Guide](http://guide.dhcuration.org/), initially published in 2012. This repository is chiefly intended to support data conversion and updates. Please do not cite.

License: Guide content is licensed under a [Creative Commons Attribution-NonCommercial-NoDerivs 3.0 Unported License](http://creativecommons.org/licenses/by-nc-nd/3.0/)

### Organization of the Data

All files related to the DH Curation Guide data conversion project can be found in this repository. Files are organized into two subfolders:

##### original_data

Original data in this context is the output of an automated process that  converts HTML files from the online version of the [DH Curation Guide](http://guide.dhcuration.org) to Markdown files.

The HTML files used as input for this conversion process were downloaded at 2014-02-28T13:32. Files were acquired using the following command:

<pre>
    wget \ 
    --recursive \ 
    --no-clobber \
    --html-extension \
    --domains dhcuration.org \
    --no-parent http://guide.dhcuration.org/
</pre>

Process output is stored in `download_log.txt`

NB: This method of collecting data is consciously lossy. By downloading from the live "visible" site, this process does not capture all the Guide files that exist on the server at MITH. Also, this process does not capture all of the files (images, css) required to render the downloaded pages.

The downloaded HTML files were converted to Markdown using Pandoc 1.8.2. The conversion script can be found at: [http://nbviewer.ipython.org/gist/trevormunoz/9278681](http://nbviewer.ipython.org/gist/trevormunoz/9278681)

The "raw" Markdown files, with all of the infelicities to be expected from an automated conversion process are found in this directory and form the starting point for files in `reformatted data`.     

##### reformatted_data

Files in this folder have been edited by hand and represent later stages of the data than files in `original_data`.

### File Naming

Files in `original_data` are named using the following convention which combines the folder/chapter name and the file name of the HTML file:

`[CHAPTER]-index.md`


