# text_fingerprints
Assignment 7 for Information Visualization (CS465): Interactive text fingerprints of uploaded txt files of books giving information of how a document is written. 

Each square block represents 200 words of text and is colored according to the selected metric. 
The metric options are:
  1) Average word length
  2) Hapax Legomena count. A word is considered to be a Hapax Legomena if it only appears in the document once, so the metric is the      measurement of  unique words in the document.
  
  I've uploaded cleaned txt files of Frankenstein and Pride and Prejudice to use with the project. Both files were obtained from Project Gutenburg (http://www.gutenberg.org/). The files were cleaned of Project Gutenberg boilerplate from the start and end of the file, any table of contents or lists of figures, and all instances of '--' and '_'. 
  
To launch, download the provided Frankenstein and Pride and Prejudice txt files or use your own cleaned txt files, and either:
  1) Visit http://www.cs.middlebury.edu/~cbintz/infovis/hw7/assignment7.html
  2) Download assignment7.html, open a terminal, cd into the directory to where you downloaded hw7.html, launch a server (python -m http.server), and navigate to that port in your web browser's address bar.
 
