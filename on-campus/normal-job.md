# Logging in and sbatch jobs

Login
> ssh NETID@prince.hpc.nyu.edu  
> PASSWORD

Submitting a job
> sbatch FILENAME.sbatch

Checking on a job
> squeue -u NETID

Seeing output of a job
> cat slurm-JOBID.out

Canceling a job
> scancel JOBID

Exiting
> ctrl + D
