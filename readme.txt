refs_bibtex 
Git repository of accelerator physics references.  

Professor Steven M. Lund
Physics and Astronomy Department
Facility for Rare Isotope Beams
Michigan State University
lund@frib.msu.edu
517-908-7291

References contained in refs.bib have been used in various 
papers and documents that I have written many years.  Please add to the 
file but keep the present format/naming pattern and make sure to check 
that entries work with no typos before checking in.  Please contact me 
if any questions.   

To initialize the repository, 

   % git clone git@github.com:smlund/project_name.git
   % git pull  

This will create a directory, refs_bibtex where command was run with the
refs.bib archive file.  Descend into that, make mods, then 

To check in mods:

  % 

Entries/names organized alphabetically by name under the following headings. 
Please see refs.bib file for details. Added references should not conflict 
with any previous ones to allow backward compatibility (reprocess old papers). 
Also please use no spaces in names (LaTeX works with but less 
reliable accross platforms in ascii text files).  For year fields, please use 
4 digits, eg. 2015 etc.  If there are degeneracies, please use, yeara yearb, 
etc.  Examples, Davidson.2015a.prstab  etc. Please correct evident typos as 
they become apparent.  But if you want an alternative format, make another 
entry with appropriate content.     

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

