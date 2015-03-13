---
---
# Data Analysis Tools

## Presentation: Ipython Notebook
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


##Python packages:

###Data manipulation and modeling 
	Pandas - data manipulation: reads data into dataframes
	NumPy - efficient numerical computation and array operations
		(Pandas and SciPy are built on Numpy)
	Scipy - scientific computing package 
		includes optimization, linear algebra, integration, ...
	Scikit-learn - machine learning: includes linear regression,
                logistic regression, classification, clustering,
                dimension reduction...

###Plotting and visualization	
	Matplotlib - plotting library
	Seaborn - statistical visualization (based on matplot lib)
	Bokeh - interactive visualization

###Data sourcing
	Requests, Zipfile, Os
  example:
	`result = requests.get("http://...")`
	`uzf=zipfile.zipfile(StringIO.StringIO(result.content))`
  another option is to use Linux commands wgets, this can be documented within a makefile.

###Misc
If these packages are not already installed, then install via pip
	`pip install package`

These packages are read into a python program via import:
	`import package`
note: for matplotlib to display graphs use 
	`%pylab inline` 
	`import matplotlib.pyplot as plt`

## Collaboration and version control

Git