This is a repository for sharing Jupyter notebooks and other files relevant to UCI's research on cluster lensing.

These files are bash scripts, useful for QLens users:

  mkdist_std        
  Run this in a 'chains_..." directory and it will execute mkdist for you, creating the .err file and all
                    the usual pre-plot files.
                    
  mkdist_E          
  Run mkdist to create the .err file (shows parameter 50th-percentile values).
  
  triplot 
  Make the triangle plot.
  
  qllog             To run QLens, potentially on multiple cores in mpi (requires MPI be installed), and copy all output to a
                    .log file. The usage is 
                    qllog <scriptname.in> <n>
                    where n is the number of cores. If n=1, mpi is not used.
    
