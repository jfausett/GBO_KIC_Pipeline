Pipeline for processing Tabby's Star data aquired with the Great Basin Observatory (GBO).  Tabby_pipe.py is the primary backend, containing a series of routines to find, parse, process, and plot data.  Tabby_API.py is a short script for the automated execution of Tabby_pipe and looks for new data to process.  Repository includes a number of useful modules from Thacher Observatory; however, currently using IRAF for primary photometry so many of them are not used at this point.  Future versions will eliminate the dependency on IRAf and allow for a transition to Python 3 by using Astropy for apperature photometry.