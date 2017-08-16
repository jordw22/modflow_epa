# modflow_epa

### **Table of Contents**

[Introduction](https://github.com/jordw22/modflow_epa#introduction)

[Notebooks](https://github.com/jordw22/modflow_epa#notebooks)

[Installation](https://github.com/jordw22/modflow_epa#installation)

[Getting Started](https://github.com/jordw22/modflow_epa#getting-started)

[Flopy Supported Packages](https://github.com/jordw22/modflow_epa#flopy-supported-packages)

[Floply Model Checks](https://github.com/jordw22/modflow_epa#flopy-model-checks)

[Flopy Changes](https://github.com/jordw22/modflow_epa#flopy-changes)

[MODFLOW Resources](https://github.com/jordw22/modflow_epa#modflow-resources)


Introduction
-----------------------------------------------

This Jupyter Notebook is intended to offer groundwater modeling self study in an easy to learn format.
It provides the student with hands-on experience with the practical application of models. This manual
is complete with problem statements, input data sets, and discussion of results. The problems are designed
to cover modeling priciples, specifics of input/output, options available to the modeler, rules of thumb,
and common modeling mistakes.

Data set preparation time and execution time have been minimized by simplifrying the problems to small size
and to focus only on the aspect that is under consideration. Model grids are generally smaller and more homogenous
than would be unsed in practice, however, the intent and result of each exercise are not compromised by the simplification.

In each notebook you will notice regular text and _italic text_. The regular text is me writing. _The italic text is text
that I have taken straight from the **EPA Manual of Instructional Problems for the U.S.G.S MODFLOW Model**_. The link to view
the original document is located under the [Doc] folder.

This manual is developed for the U.S. Geological Survey modular groundwater model (MODFLOW).

Notebooks
-----------------------------------------------

[Learning the Basics](https://github.com/jordw22/modflow_epa/blob/master/Notebooks/Practice/Learning%20the%20Basics.ipynb)

[MODFLOW Problems](https://github.com/jordw22/modflow_epa/tree/master/Notebooks)

[MODFLOW PDF File](https://github.com/jordw22/modflow_epa/tree/master/Doc)

[Helpful Terms and Definitions](https://github.com/jordw22/modflow_epa/blob/master/terms%20and%20definitions.md)

Installation
-----------------------------------------------

### **Python versions:**

* FloPy requires **Python** 2.7 or **Python** 3.3 (or higher)

### **How to create your own notebooks:**

1. Download **Anaconda**  
	* comes with **Jupyter Notebook** already installed
	* link to download Anaconda: (https://www.continuum.io/DOWNLOADS)
	* follow the instructions on the website and download Anaconda according to which operating system you have
	  (Windows, OS X, Linus)
4. Create folders to hold documents/code
	* make sure the folders have a good structure and have a clean/simple path (you can copy my folder formatting exactly or as a reference for your own)
	* get used to making folders this way as it is a good habit to get into and will benefit yourself and others
2. Install Flopy from USGS: (https://water.usgs.gov/ogw/flopy/#downloads)
	*Use the pip install -> simply copy and paste the code into Anaconda (your terminal) and run it 
	*Flopy creates a file, then Modlflow reads those files and makes more, and then Flopy reads all the files produced by
	 Modflow and produces the results
	*Flopy is 
3. Download Modflow from USGS: (https://water.usgs.gov/ogw/modflow/MODFLOW.html#downloads)
3. Opening a notebook
	* open Anaconda
	* in Anaconda type: jupyter notebook
	* will take you to the website
3. _Optional_: Create a profile online with jupyter notebook and then select [New repository] to create your own

### **How to run my modflow_epa notebooks:**

1. In top right corner click the green [Clone or download] button
2. Select [Download ZIP]
3. Create a folder for these files and place the ZIP file in it
4. Unzip the files
3. Place the modflow executable [mf2005.exe] into a seperate folder before unziping it. **It must be in a folder on the same level as notebook or it will not run!**

Getting Started
-----------------------------------------------

There are a few great ways to learn more about Python, Jupyter Notebook, Modflow, and Flopy.
Some ideas that I found very useful, and would definitely recommend for whenever you find yourself stuck:
*Read up on some of the basic functions of Anaconda and Jupyter Notebook.
*Watch tutorials on youtube (Links to the video series' that I found most helpful below)
Figure out the shortcuts(i.e. how to read code, how to save your project, how to toggle between code and markdown (text)
Read through the entirety of each problem to understand what it is asking before you attempt to code
Draw pictures/graphs and write down key information that you'll need

__Youtube Video Links:__
* [Python 3 Programming Tutorial by codebasics](https://www.youtube.com/playlist?list=PLeo1K3hjS3usILfyvQlvUBokXkHPSve6S)
* [Python Video Notebooks (1-10) by Mark Bakker](https://www.youtube.com/user/wdz57/videos)
* [Jupyter Notebook Tutorial by codebasics](https://www.youtube.com/playlist?list=PLeo1K3hjS3uuZPwzACannnFSn9qHn8to8)
* [Numpy Tutorial](https://www.youtube.com/playlist?list=PLeo1K3hjS3uset9zIVzJWqplaWBiacTEU)
* [Python Pandas Tutorial by codebasics](https://www.youtube.com/playlist?list=PLeo1K3hjS3uuASpe-1LjfG5f14Bnozjwy)
* [Data analysis in Python with pandas by Data School](https://www.youtube.com/playlist?list=PL5-da3qGB5ICCsgW1MxlZ0Hq8LL5U3u9y)
* [Git/SourceTree Turtorial by Virtual Play](https://www.youtube.com/playlist?list=PLpL2ONl1hMLtlY1Y7YJNcA5zumvaITLYs)

I have also created a [Practice\Learning the Basics] notebook that walks through how to use Jupyter Notebook and how to
do some of the basic coding that you will need to know for the problems.

FloPy Supported Packages
-----------------------------------------------

A list of supported packages in FloPy is available in [docs/supported_packages.md](docs/supported_packages.md) on the github repo.


FloPy Model Checks
-----------------------------------------------

A table of the supported and proposed model checks implemented in  FloPy is available in [docs/model_checks.md](docs/model_checks.md) on the github repo.


FloPy Changes
-----------------------------------------------

A summary of changes in each FloPy version is available in [docs/version_changes.md](docs/version_changes.md) on the github repo.

MODFLOW Resources
-----------------------------------------------

* [MODFLOW and Related Programs](http://water.usgs.gov/ogw/modflow/)
* [Online guide for MODFLOW-2000](http://water.usgs.gov/nrp/gwsoftware/modflow2000/Guide/index.html)
* [Online guide for MODFLOW-2005](http://water.usgs.gov/ogw/modflow/MODFLOW-2005-Guide/)
* [Online guide for MODFLOW-NWT](http://water.usgs.gov/ogw/modflow-nwt/MODFLOW-NWT-Guide/)

[Back to Top](https://github.com/jordw22/modflow_epa)