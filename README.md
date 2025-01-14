# TurbulanceAssignment
## User Modifications
### HPCJournalFile (By Aniruddha)

Change name
Ensure correct name of the Ansys cas.h5 file is used - in 2 places one at the start and one after solve

ensure correct number of iterations are used

ensure correct name od output dat.h5 file is used.

-----------------------------------------------------------------
### Level7_tui.jou (By Nicolas)

Journal files for setup and runnning in HPC. 

Changes should be made with: 

1: File Name 

2: Solver settings

-------------------------------------------------------------------

### Fluent.sub (By Aniruddha)

Job name

User email - very important

Number of processors- very important read instructions provided

Name of the journal file to access.

------------------------------------------------------------------
### test_auto_script.mlx (By Jawad)

Matlab file for changing data into tempate form.

-------------------------------------------------------------------
### A few additional comments

To run the simulation o the HPC via linux terminal use  - qsub fluent.sub

In the HPC make separate folder for every run otherwise the files with similar names will be overwritten. 

Don't run 2 jobs simultaneously
