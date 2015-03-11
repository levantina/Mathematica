# MATHEMATICA AS PROGRAMMING LANGUAGE AND SOFTWARE - Mathematica code, projects and exercises.

These files are a collection of Mathematica 9.0 notebooks: 

- practice2012: 
This is a series of solved exercises that I did as a training before attending on July 2013 the Wolfram Science Summer School (WSSS) in Boston (MA).

- practice2013:
These are exercises and assignments that I did before and during the WSSS.

TURING MACHINE Homework:
homeworkTM_5_3.nb -> This notebook describe the Turing Machine with 5 States and 3 Colors (more details here: http://reference.wolfram.com/language/ref/TuringMachine.html). There are 30^15 possible different rules of evolution, from an initial state. The goal of the homework was to find some interesting TMs. I created two criteria, one based on the average width of the TM during its evolution (that helps to exclude the trivial TMs), and the other one based on the entropy, that means the larger the entropy the better. I also observed how widths are distributed in a random sample of 10^4 TMs. And I selected my favorite TM.

RANDOM WALK 2D and 1D Exercise:
randomwalk_problem17.nb -> This notebook creates and plots a random walk in one and two dimensions, according to different rules and lattice forms.

- WSSS Project: 
“What popularity tells us about a Wikipedia sub-graph?”

These files are the Mathematica notebooks and descriptions of the personal project that I developed during the Wolfram Science Summer School on July 2013. Studying the popularity time series of Wikipedia articles I observed two global behaviors. In this context “popularity” is the number of daily/weekly visits of a page on the Internet. I observed also that, at the considered time scale, the popularity diffuses instantly in the graph, following the links. I described all characteristics of the Wikipedia sub-graph that I build for the analysis, given an initial page. I tried to predict the real connections of the graph from popularity, according to my hypothesis. 

DESCRIPTION: posterValentina.pdf -> It describes briefly the project in every aspect. It provides also a short description of the results, with graphics.

WIKIPEDIA NETWORK: createNetwork.nb -> It builds the Wikipedia sub-graph starting from an initial page, considering all the articles within two-cliks distance inside English Wikipedia. It also considers links multiplicity.

PROJECT: projectComplete -> All the functions, code lines, graphics, data manipulations for developing the project, in one Mathematica notebook. Given the graph (obtained in createNetwork.nb), starting with the download of the visits (popularity) time series (for a certain time window) of the wikipedia articles, and ending with the links prediction for that graph.

- Thesis:
Useful code for the initial data gathering for my Master’s Thesis, basically a further development of the WSSS Project described above.

