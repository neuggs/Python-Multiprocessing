# Python Multiprocessing
A simple project that shows how Python multi-processing works using the Wikipedia corpus. The project consists of three Jupyter Notebooks and incrementally shows various elements of Python multi-processing. For a little something extra, logging is also used extensively within the Notebooks. Each of the three parts builds on the prior part, starting with reading, tokenizing, and finally word counting the corpora.

For the first two steps, there's code that shows the effects of multi-processing on processing speed.

There's one other extra - using Google Cloud to run part 3. This is because the last part is very CPU intensive, so I shifted everything to run from Google. How the code was run is outside of this description, but running Google jobs is pretty easy and the documentation is fantastic. 

# Requirements
You will need the Wikipedia featured articles JSON files. ADD URL TO THE FILES HERE.

You also need to have the Google Cloud SDK installed and a Google instance running (for part 3).

You will also need the following packages installed in Python (you can use `pip install <PACKAGE_NAME>` within Anaconda (for instance) to install these packages, presuming you have Anaconda (or similar Python distribution) installed.(Some of thse are likely already installed.)

* pandas
* logging
* timeit
* os
* multiprocessing
* datetime
* sklearn
