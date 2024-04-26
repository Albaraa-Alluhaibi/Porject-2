# Banker's Algorithm for Deadlock Avoidance
# Albaraa Alluhaibi
# CS33211

## Overview

This program implements the Banker's Algorithm for deadlock avoidance in operating systems. The Banker's Algorithm ensures that the system doesn't enter a deadlock state by checking for safety before allocating resources to processes.

## How to Use

1. Ensure you have a C++ compiler installed on your system.

2. Compile the program using the following command:

###

  g++ banker.cpp -o banker
  
###

3. Prepare an input file (`input.txt`) containing the following information:
- Number of processes (`n`)
- Number of resource types (`m`)
- Allocated resources for each process
- Maximum resources required for each process
- Available resources

4. Run the program command :

###

./banker

###

5. Follow the on-screen instructions to provide the input file.
6. The program will output whether the system is in a safe state and the safe sequence if it is.

## Input Format

The input file (`input.txt`) should follow this format:


## Output

The program outputs whether the system is in a safe state and the safe sequence if it is. If the system is not in a safe state, it will notify accordingly.

example :

P1 -> P3 -> P4 -> P0 -> P2


##remove the program

To remove the program type this command :

rm -r banker

## Credits

This program is developed by Albaraa Alluhaibi.


