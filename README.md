# NVMExplorerDataVisualizationTutorial

This is a Data Visualization Tool for the open source software 'NVMExplorer' by Lillian Pentecost and Alexander Hankin, 2021. Said software in a cross-stack broad design exploration framework to evaluate and compare different on-chip memory solutions including non-volatile embedded memory technologies such as RRAM, PCM, STT, FeFET, CTT with system level constraints and application level impacts on the loop. The framework and the published notebook can be found here: https://github.com/lpentecost/NVMExplorer 

During my two research fellowships with Dr. Lillian Pentecost as my PI, I developed this visualization tool which provides the missing data analysis and visualization tutorials that the original project was lacking. For this, I made the automated tool in Jupyter Notebook, written in Python with the data science libraries Pandas and Matplotlib, as well as some Jupyter integrated modules. The newly implemented software parses the output csv files written by NVMExplorer, and then makes a lot of necessary graphs and toggles based on all of the input parameters and memory technologies considered when running the simulation software. 

The visualization tutorial drives the user through a cross stack narrative, starting with comparing data specific with each memory cell type. Then, the user delves into array level statistics with generic traffic patterns of read and writes. Finally, the graphs tell the story of how the cells behave under specific application traffic patterns, including graph processing, DNNs, and SPEC which are general scientific computations and uses.

Additionally, the tool provides customizable toggles and filtering so that the suer can look at the data at specific ranges or types of cells. Moreover, if other variables want to be looked at by the user, doing so is as easy as changing one line of code with the name of the variable, all of which are provided at the top.

The tool is a great way to gain a cohesive understanding of the memory cells and the impact of using each of them at runtime for certain applications. It can help researchers answer their questions on which cell could be better in terms of energy efficiency, latency, or durability depending on their individual pursuits.

More detailed information is found in the paper and the poster included in teh repository, as well as very exhaustive instructions in the Jupyter Notebook itself.
