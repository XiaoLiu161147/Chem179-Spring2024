# Description
This is the reference code for HW1. It reads atomic coordinates from a file, calculates the Lennard-Jones energy, evaluates analytical and numerical forces on atoms, and performs optimization using the steepest descent method with options for a standard approach or enhanced with a golden section line search.

#Build the code on Datahub
`g++ -o hw1 *.cpp -I/usr/include -L/usr/lib -larmadillo`

#Usage
`./hw1 <filename>`
`<filename>`: The path to the input file containing atomic numbers and xyz coordinates.
Or
`./hw1 <filename1> > <filename2>`
`<filename1>`: The path to the input file containing atomic numbers and xyz coordinates.
`<filename2>`: The path to the output file that you want to store the output info.