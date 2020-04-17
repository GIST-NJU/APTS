An Adaptive Penalty based Tabu Search for Constrained Covering Array Generation
==============================================================================


Experimental results
----
Please refer to the file `results.pdf`.


Executable JAR File
----
To generate a constrained covering array by APTS, use the following command:

java -jar apts.jar  <MODEL_NAME><CONSTRAINT_NAME><CUTOFFTIME>
For example: java -jar apts.jar demo.model demo.constraints 30

Noted: iopg-ft.jar is used to generate a initial CA and it must be in the same directory as apts.jar.