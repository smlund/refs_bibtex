refs_bibtex 
Git repository of accelerator physics references.  

Professor Steven M. Lund
Physics and Astronomy Department
Facility for Rare Isotope Beams
Michigan State University
lund@frib.msu.edu
517-908-7291

References contained in the BibTeX database file refs.bib have been 
used in various LaTeX papers and documents that I have written over 
many years.  Please make use of refs.bib as you see fit and 
add and improve refs.bib to make it more useful in the future. 
Please keep the present format/naming pattern and make sure to check 
that entries work with no typos before updating the git repository if 
you want to contribute.  Please contact me with any questions.   

To initialize the repository, 

   % git clone  git@github.com:smlund/refs_bibtex.git

This will create a directory, ./refs_bibtex where command was run with this 
readme.txt instruction file and the refs.bib archive file.  

To get the latest version descend into directory refs_bibtex and run:

  % git pull 

When modifying the repository (for those with edit privilege, please contact 
me if you want to contribute and I will add you) 

  ... edit refs.bib file etc 
  % git add refs.bib 
  % git commit -m "SML: added journal paper reference" 
  % git push 


The organization of refs.bib is as follows: Entries/names are organized 
alphabetically by BibTeX name label under the headings listed below. 
Please see refs.bib file for details. Added references should not conflict 
with any previous ones (i.e., must be unique labels for all new entries) 
to allow backward compatibility (reprocess old papers, etc.). 
Also please use no spaces in names (LaTeX works with spaces but it is less 
reliable across platforms in ASCII text files when editing etc).  For 
year fields, please use 4 digits, eg. 2015 etc.  If there 
are label degeneracies, please use, yeara yearb, 
etc.  Examples, Davidson.2015a.prstab  etc. Please correct evident typos as 
they become apparent.  BUT if you want an alternative format for an existing 
reference (outside of typo corrections), make another entry with a unique 
name and appropriately modified content.     

  Books @Book{}
    Names:  Author.B.year   
            Abramowitz.B.1972
            Jackson.B.1998

  Papers @Article{} 
    Names: Author.year.journal-abbreviation
           Batygin.2005.nima
           Bieniosek.2007.prstab

    Note: Journal names very abbreviated:
          prl    = Physical Review Letters 
          prstab = Physical Review Special Topics -- Accelerators and Beams 
          
          Find examples and copy!

  Conference Papers @INPROCEEDINGS{} 
    Names: Author.C.year 
           Baartman.C.1998
           Davidson.C.1994

    Note: No attempt to put conference names in name since too many. 


  PhD Theses @PHDTHESIS{} 
    Names: Author.T.year 
           Dorf.T.2010

     Note: No attempt to put institutes in name since too many.


  Lab Reports and E-Prints @TECHREPORT{}
     Names: Author.R.year.lab 
            Barnard.R.2001.lbnl

     Note:  Names for labs very abbreviated.  
            llnl = Lawrence Livermore National Lab 
            pppl = Princeton Plasma Physics Lab 

   Miscellaneous Comments @MISC{} 
     Names:  As wish, no redundancy 

