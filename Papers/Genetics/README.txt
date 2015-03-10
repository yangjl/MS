
README
link of the following file: http://ib.berkeley.edu/labs/slatkin/eriq/latex/index.htm
driected from: http://schneider.ncifcrf.gov/latex.html

- LaTeX Packages -
I have modified and or written several .sty and .bib files for manuscript preparation and other purposes. I offer these here with no warranty and without a whole lot of documentation. They do all come with sample files, though, so Good Luck! I hope these are helpful to whomever finds them. Currently available: JASA, Genetics, JABES.

 

Style file for the Journal of the American Statistical Association: the ASA has stopped providing a decent package for formatting manuscripts for submission to JASA. Yet they still require a particular format. For this I wrote JASA_manu.sty and hacked up harvard.sty into "jasa_harvard.sty." I also hacked up harvard.bst into "ECA_jasa.bst" for use with BibTex.
You may receive all the necessary files as the Stuffit Archive JASA_manu.sit. (232k) This will unstuff into a directory called "jasa."

Or you can download the necessary files individually:

JASA_manu.sty //-> The main style file
jasa_harvard.sty //-> The style file with formatiing information for citations in the text.
ECA_jasa.bst //-> The BibTex style file for formatting the Reference list
JASA_example.tex //-> A .tex file that gives an example how to use these style packages. This is just a strange little excerpt of a paper I once submitted to JASA.
example.bib //-> The BibTex database file for JASA_example.tex
undirgraph.eps //-> A postscript file to be included as a figure in JASA_example.tex
In order get JASA_example to run, follow these steps:

Make sure all the above files are in the same directory or in the LaTeX search path
Run LaTeX on JASA_example.tex
Run BibTeX on JASA_example.aux
Run LaTeX two more times on JASA_example.tex
 

Style file for the Journal Genetics: Genetics has a fairly well-prescribed format for journal submissions. I have written a style file to get that done. And I have hacked up the chicago BibTeX style into something that makes citations and reference lists as required. The publishers handling Genetics can't deal with LaTeX files anymore. They would rather have a Microsoft ".doc" file. The Evil Empire is strangling academia now, even. I've found, however, that the publishers are still willing to do all the retyping that they need to for submissions in LaTeX.
You may receive all the necessary files as the Stuffit Archive genetics_manu.sit. (64k) This will unstuff into a directory called "genetics."

Or you can download the necessary files individually:

genetics_manu_style.sty //-> The main style file
mychicago.sty //-> The style file with formatiing information for citations in the text.
mychicago.bst //-> The BibTex style file for formatting the Reference list
genetics_example.tex //-> A .tex file that gives an example how to use these style packages. This is a short letter I once submitted to Genetics.
genetics_example.bib //-> The BibTex database file for genetics_example.tex
LambdaGraph.eps //-> A postscript file to be included as a figure in genetics_example.tex
BiasGraph.eps //-> A postscript file to be included as a figure in genetics_example.tex
LambdaGraph.eps //-> A postscript file to be included as a figure in genetics_example.tex
In order get genetics_example to run, follow these steps:

Make sure all the above files are in the same directory or in the LaTeX search path
Run LaTeX on genetics_example.tex
Run BibTeX on genetics_example.aux
Run LaTeX two more times on genetics_example.tex
 

Style file for the Journal of Agricultural, Biological, and Environmental Statistics: My JABES style file is very similar to JASA_manu.sty. JABES does not seem to have guidelines as strict as JASA. JABES asks for citations to be done in JASA style. The following should suffice for submissions to JABES.
You may receive all the necessary files as the Stuffit Archive JABES_manu.sit. (236k) This will unstuff into a directory called "jabes."

Or you can download the necessary files individually:

JABES_manu.sty //-> The main style file
jasa_harvard.sty //-> The style file with formatiing information for citations in the text.
ECA_jasa.bst //-> The BibTex style file for formatting the Reference list
JABES_example.tex //-> A .tex file that gives an example how to use these style packages. This is just a strange little excerpt of a paper I once submitted to JASA.
example.bib //-> The BibTex database file for JABES_example.tex
undirgraph.eps //-> A postscript file to be included as a figure in JASA_example.tex
In order get JABES_example to run, follow these steps:

Make sure all the above files are in the same directory or in the LaTeX search path
Run LaTeX on JABES_example.tex
Run BibTeX on JABES_example.aux
Run LaTeX two more times on JABES_example.tex