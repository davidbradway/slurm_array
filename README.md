# slurm_array

Run a shell comand that launches a SLURM bactch process that has 2 array jobs with IDs '1' and '2':

```shell
./launch.sh
```

The array job uses the bash shell, sets the job name, the number of cores per machine, the memory required, the job time length, the output and error director(y/ies), and whether to email.

Then you can change to a certain directory and launch a Matlab job in a command line mode that takes the SLURM array task ID ('1' or '2' example) as a variable and runs a Matlab script and saves the output to a numbered file.