---
---
# Data Analysis Tools

### Presentation: Ipython Notebook
	10 minute video intro to Pandas and Ipython notebook: <https://vimeo.com/59324550>
	To open an ipython notebook `ipython notebook file.ipynb`
	To convert ipython notebook to pdf, first convert to html:
		`ipython nbconvert --to html file.ipynb`
		or
		`ipython nbconvert --to slides file.ipynb`
		Then convert html file to pdf:
		`wkhtmltopdf file.html file.pdf` 
		or simply print to pdf using the browser print function.
	To convert to html slideshow use:
		`ipython nbconvert --to slides file.ipynb --post serve`
		This will run an html slide show.

### Data manipulation and modeling: Python packages
	* pandas - data manipulation: reads data into dataframes
	* numpy - efficient numerical computation and array operations
		(Pandas and SciPy are built on Numpy)
	* scipy - scientific computing package 
		includes optimization, linear algebra, integration, ...
	* scikit-learn - machine learning: includes linear regression,
                logistic regression, classification, clustering,
        	dimension reduction...

### Plotting and visualization:  Python packages
	* matplotlib - plotting library
	seaborn - statistical visualization (based on matplot lib)
	bokeh - interactive visualization

### Data sourcing

#### Python packages:
	requests, zipfile, os
	example:
	'imort requests zipfile'
	`result = requests.get("http://...")`
	`uzf=zipfile.zipfile(StringIO.StringIO(result.content))`

#### Linux comand line:
	another option is to use Linux commands wgets, this can be documented within a makefile.

### Misc
	If these python packages are not already installed, then install via pip
	`pip install package`

	Ppackages are read into a python program via import:
		`import package`
	note: for matplotlib to display graphs use 
		`%pylab inline` 
		`import matplotlib.pyplot as plt`

### Collaboration and version control:  Git

