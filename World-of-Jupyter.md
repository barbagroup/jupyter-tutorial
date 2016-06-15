# The world of Jupyter
## An environment to think, code, explore data and communicate science

At the center of the Jupyter world are *notebooks*: documents containing a mix of rich text elements—headings, paragraph text, hyperlinks, mathematical symbols and embedded figures—and interactive code elements. The document uses "cells" to divide up the text and code elements: text is formatted using markdown, and code can be executed using the IPython kernel or others (like Julia or R language).

You can use the notebooks to annotate ideas around code, to explain your thought process, or to report on research process and results. Having interactive code right there in the document empowers you to "think with code," trying things out and exploring data as you go. The notebook has also become a very popular platform for teaching and learning, with a growing community of users publishing lessons, even books, using notebooks.

To work on notebooks, you run the Jupyter Notebook App and edit them from your favorite browser. The app gives you a dashboard on a new browser window that connects to the computational engine (called kernel) behind the scenes. You can install Jupyter locally on your computer, or use it on the cloud on paid or free services. You can also share your finished notebooks online as a static web page, via the free [`nbviewer`](http://nbviewer.jupyter.org) service.

Everything in Project Jupyter is free and open source. Via the IPython kernel, you can access the whole ecosystem of Python with its libraries for numerical computing, visualization, data analysis, machine learning and more. Jupyter is a world of sharing code and content, and a productive environment to get things done with code and data.

Get started with Jupyter in this tutorial, and then follow some of the many more available online. 

You can try Jupyter right now on this free service: [https://try.jupyter.org](https://try.jupyter.org). Click on the "Welcome to Python" link there: this demo is a temporary notebook with a single code cell that reads some data and draws a plot. Or you can instead click on the "New" button (top right) and choose Python 3 from the options, to get a blank notebook (also temporary). To try a notebook that you can save on the cloud, use the new free service by Azure: [https://notebooks.azure.com](https://notebooks.azure.com). If you want everything installed in your own laptop computer, download the Anaconda distribution (free) from: [https://www.continuum.io/downloads](https://www.continuum.io/downloads)

### Jupyter tutorial in Wuhan, June 2016

For the Jupyter tutorial at **Huazhong University of Science and Technology** (Wuhan, China), by Prof. Lorena Barba, students should prepare by doing one of these:

1. Create an account on Microsoft **Azure** and test the free cloud notebooks at [https://notebooks.azure.com](https://notebooks.azure.com) — you need an account to be able to save notebooks for later. If you only access the free demos, your work will not be saved.
2. Install **Anaconda** in your laptop computer. Downloading from the [official website](https://www.continuum.io/downloads) could take a long time, but there is a mirror at Tsinghua University, according to the post in: [http://www.tuicool.com/articles/vyyA7rB](http://www.tuicool.com/articles/vyyA7rB)  
We found an error in the URL provided in that post, though. The actual location of the Tsinghua mirror is [https://mirrors.tuna.tsinghua.edu.cn/anaconda/archive/](https://mirrors.tuna.tsinghua.edu.cn/anaconda/archive/)  
Download the latest version for your operating system (we'll be using Python 3). 
After installing, from a terminal, run `conda update conda` and then run `conda update jupyter numpy sympy scipy matplotlib`
3. If your internet is slow or you want to save disk space, you can instead install **Miniconda** from the [official site](http://conda.pydata.org/miniconda.html) or from the [mirror](https://mirrors.tuna.tsinghua.edu.cn/anaconda/miniconda/) in Tsinghua University. Then, you should run three commands from the terminal:  
`conda update conda`  
`conda install jupyter`  
`conda install numpy scipy sympy matplotlib`

## Contents

(Links to notebooks rendered by **nbviewer**.)

1. [The Notebook](http://nbviewer.jupyter.org/github/barbagroup/jupyter-tutorial/blob/master/1--The%20Notebook.ipynb)
2. [The Python world of science and data](http://nbviewer.jupyter.org/github/barbagroup/jupyter-tutorial/blob/master/2--The%20Python%20world%20of%20science%20and%20data.ipynb)
3. [Jupyter like a pro](http://nbviewer.jupyter.org/github/barbagroup/jupyter-tutorial/blob/master/3--Jupyter%20like%20a%20pro.ipynb)


### Interact with the notebooks on Azure cloud:

You can interact with the notebooks right now, without downloading anything—thanks to the new cloud notebooks by Azure—by following this link:
[https://notebooks.azure.com/library/Jbzl8X0qhHw](https://notebooks.azure.com/library/Jbzl8X0qhHw)