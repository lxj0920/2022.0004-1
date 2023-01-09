[![INFORMS Journal on Computing Logo](https://INFORMSJoC.github.io/logos/INFORMS_Journal_on_Computing_Header.jpg)](https://pubsonline.informs.org/journal/ijoc)

# Perturbation-based thresholding search for packing equal circles and spheres

This archive is distributed in association with the [INFORMS Journal on
Computing](https://pubsonline.informs.org/journal/ijoc) under the [MIT License](LICENSE).

The software and data in this repository are a snapshot of the software and data
that were used in the research reported in the paper _Perturbation-based thresholding search for packing equal circles and spheres_ by L.J Lai, J.K. Hao, R.B. Xiao, and F. Glover. 

This repository includes the following materials: 
- _source codes of proposed PBTS algorithms respectively for the PECS and PESC problems_ (See [the source codes](src/source_code) directory for the details.)
- _executable codes of proposed PBTS algorithms respectively for the PECS and PESC problems_ (See [the executable codes](src/executable_code) directory for the details.)
- _scripts used to replicate the experiments in the paper_ (See [scripts](scripts) directory for the details.)
- _check procedure aiming to certify the feasibility of best solutions found_ (See [the check procedures](src/check_procedure) directory for the details.)
- _Matlab procedure to show the configurations of solutions of the PECS problem_ (See [matlab](src/matlab) directory for the details.)
- _detailed computatioanl results obtained in our experiments_ (See [the detailed results](results/detailed_results) directory for the details.)
- _best solutions found in the experiments_ (See [the best solutions](results/best_solutions) directory for the details.)

Note: The contents and formats of the files are demonstrated in the ReadMe file of corresponding subdirectory.

## Running the programs

To generate the executable codes (i.e., PBTSPECS and PBTSPESC) of PBTS algorithm respectively for the PECS and PESC problems, one can run the script files 'compile_pecs.sh' and 'compile_pesc.sh' in the [scripts](scripts) directory.

 ### The PECS problem 
_Usage:_ 

./PBTSPECS    N    NumberOfRuns   TimeLimit
- N is the number of unit circles
- NumberOfRuns is the number of times of running the PBTSPECS program 
- TimeLimit is the time limit (in seconds) for each run. 

_Note: See [executable code for PECS](src/executable_code/PECS) directory for the details._
 ### The PESC problem
_Usage:_

./PBTSPESC    N    NumberOfRuns   TimeLimit

- N is the number of unit spheres
- NumberOfRuns is the number of times of running the PBTSPESC program
- TimeLimit is the time limit (in seconds) for each run

_Note: See [executable code for PESC](src/executable_code/PESC) directory for the details._
