## TurbulanceAssignment
# User Modifications
HPCJournalFile
Change name
Ensure correct name of the Ansys cas.h5 file is used - in 2 places one at the start and one after solve
ensure correct number of iterations are used
ensure correct name od output dat.h5 file is used.

Fluent.sub
Job name
User email - very important
Number of processors- very important read instructions provided
Name of the journal file to access.

A few additional comments
To run the simulation o the HPC via linux terminal use  - qsub fluent.sub

In the HPC make separate folder for every run otherwise the files with similar names will be overwritten. 
Don't run 2 jobs simultaneously
