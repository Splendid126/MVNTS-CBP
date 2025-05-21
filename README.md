# MVNTS-CBP
This repository provides a Windows executable file `MVNTS.exe` for running the **MVNTS** algorithm.

## Usage

To run the `MVNTS.exe` file on a Windows system, use the following command in the terminal or command prompt:

.\MVNTS.exe [max_time] [seed] [lb] [instance_file] [result_file]

### Parameters

- **`[max_time]`**: Maximum runtime of the algorithm in seconds.
- **`[seed]`**: Random seed for reproducibility.
- **`[lb]`**: Lower bound for the solution. The corresponding lower bound for each instance can be found in the file `instances_lb.txt`.
- **`[instance_file]`**: Path to the instance file.
- **`[result_file]`**: Path to the output file where the result will be saved.

### Example

To run the algorithm on a sample instance `cycle100.rnd` for 600 seconds with seed 1 and lower bound 1, and save the result to `cycle100_res.txt`, use the following command:

.\MVNTS.exe 600 1 1 .\Instances\cycle100.rnd .\cycle100_res.txt
