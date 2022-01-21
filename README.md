![logobm](https://user-images.githubusercontent.com/50483699/150559101-7c1b3799-4f72-43e0-8abc-4fe8fe912329.png)


AI applied to battery manufacturing process
========================================================

This repository provides necessary computational resources and relevant datasets
for the training session for the _1st BIG-MAP AI Workshop_. This is dedicated to the 
application of AI to battery manufacturing. Feel free to download the repository
to our own machine (Windows/Linux), and launch the codes after checking the dependencies
within Python and RStudio.

- For __RStudio__ : you are invited to create a single *R* document on your own local
environment and use the code from *packages.Rmd* and *RScript-training.Rmd*.
The first RMarkdown document contains only the code to install/load the different libraries. The second document contains the code for the data analysis with relevant comments
for a better knowledge of the overlall approach. If you face errors when installing or loading some _R_
libraries, use the menu on the right in RStudio by clicking on _Install_. Otherwise, use the command prompt within RStudio and install the library with the following command line:

```commandline
install.packages("name_of_package", repos="http://cran.rstudio.com")
```
 
- For __Python__ : we recommend you to work directly on the *Jupyter Notebook* provided
within the folder. The first file *training-example.ipynb* contains a full example
for the settings the training and testing for supervised Machine Learning model. It provides
details on the effect of hyperparameters tuning with different approaches in order
to show the importance of such an approach to improve model performances. Please note this first notebook serves as 
a tutorial for students. It is not required to launch the command lines inside. The second notebook
*training-yourcode.ipynb* is a document for students to use their own code by themselves on another
dataset. The idea is to take advantages of the previous tutorial to apply the code on 
another context. Follow the guilines along the training session for a good application of the code. If you already have 
Jupyter notebook installed and you can not load a library, please open a command prompt and launch:

```commandline
pip install name_of_package
```

We recommend a version of RStudio and Python respectively up to 1.3 and 3.7.

[R and Rstudio installation guide](https://courses.edx.org/courses/UTAustinX/UT.7.01x/3T2014/56c5437b88fa43cf828bff5371c6a924/)

[Jupyter Notebook installation guide](https://docs.jupyter.org/en/latest/install/notebook-classic.html)

RStudio application
=======================================================
For each *Rmd* document, the corresponding HTML output is existing in the same folder. It provides details related to pieces 
of codes. If you are working directly on the *RMarkdown*, you can generate such output HTML
file by clicking on *Knit* through the main menubar. If you are working on your own 
*R* file, please copy/paste every lines from the R code from the two *RMarkdown* to ease the 
compilation of the code.


Python application
========================================================
If Jupyter Notebook is installed on your local machine, you are invited to directly work on the
notebooks provided. If you face some issues to install or load python libraries, you can
use [Google Colab](https://colab.research.google.com/?utm_source=scs-index). During the training session, 
you will have a complete example on how to install and load libraries on your local Colab environment. A video
is available for the user on the loading of resources with an example on how to install a library on the fly.

 Authors
 ========================================================
  - **Marc Duquesnoy**, PhD, marc.duquesnoy@u-picardie.fr
  
 Contributing 
========================================================

 Pull requests are not allowed. For more informations about the library, please contact the authors. Do not hesitate to ask them if inappropriate bugs occur.
 
 License
========================================================
This project is licensed under the [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/) licence.





