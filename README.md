SAS
===

Always wanted to write something about SAS, coding of course, if you may say, programming
If you are a _SQL_ writer like me, then this might be helpful

1. *PROC SQL*, this is the place you can write pass through SQL code, all done now
2. *PROC DATASETS* and *DATA* steps, as we can write pretty much any logic in SQL code than DATA step, there not much need on this, however it comes handy when you need to look at what tables available in the connected schema
3. *PROC MEANS*
4. *PROC FREQ*
5. *Machine Learning* (well, or data mining) related proc such as *PROC REG*, *PROC GLM*, *PROC FASTCLUSTER*, *PROC TREE* etc.

Editor
---
If you are like me, old schooler, using _Vi_ for everyting as a main editor, here is the few lines to have syntax highlights

syn keyword SAS DATA PROC LIBNAME RUN QUIT SQL data proc libname run quit sql MEANS means MeanS FREQ freq Freq TABULATE Tabulate tabulate  
ab ss syn keyword SAS  
hi link SAS keyword  
syn on  
