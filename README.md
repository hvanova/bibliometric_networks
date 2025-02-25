# Bibliographic Networks: A Python Tutorial
**By Hannah VanWingen and Jordan Earnest**

Networks can provide significant measures to identify data driven patterns and dependencies. Though, given a data file it can be difficult to discern how one may approach creating such a network. In this tutorial, we will use a bibliographic data file downloaded from a query search in [Scopus](https://https://www.scopus.com/search/form.uri) to walk through the process of cleaning the data file, writing a Python script to parse the data into nodes and edges, computing graphical measures using [NetworkX](https://https://networkx.github.io/documentation/stable/index.html), and creating an interactive network display using [HoloViews](https://http://holoviews.org). 

### About Python
We tested multiple Python libraries for ease of use and efficiency, and concluded that building a network is more intuitive in NetworkX than [iGraph](https://igraph.org/redirect.html). However, it took several minutes for NetworkX to render our large graph and any interaction was lagging. [Pyvis](https://pyvis.readthedocs.io/en/latest/#) easily renders a network and can be expanded to incorporate more advanced NetworkX functionality with only a few lines of code, though with still slow manipulation. Holoviews, which runs on top of the native Python visualization library Bokeh, enables NetworkX to render quickly, with versitile manipulation. The graphs are produced in HTML and JavaScript for easy integration into webpages.

### About Colaboratory
While we originally developed this script in a local notebook, we found that running it through Google's cloud-based Jupyter notebook environment [Colaboratory](https://colab.research.google.com) is a smoother option, particularly for nascent coders. We encountered version conflicts between the dependencies when setting up a local notebook environment that were bipassed in Colaboratory. It allows one to use and share Jupyter notebooks from a browser, without having to download, install, or run anything on a computer. Notebooks can be saved to Google Drive, Github or downloaded locally. A single line of code adapts the script render in Colaboratory. 

To open the notebook in Colaboratory, click on the notebook from the repository list. GitHub will open a preview, click this icon  ![Image of Logo](https://colab.research.google.com/assets/colab-badge.svg) from the top of the notebook to open directly in Colaboratory. Alternatively, you can clone or download this repository and put it in Google Drive. Google Drive will recognize the *.ipynb* notebook file format and give you the option to open in Colaboratory. 

- link to put things on a webpage. 
- how to download your graph
- and you have to tell it not to "reset run times" after each time. 
