
There are three java files included. They are:

1. Calculate.java
2. ReadFile.java
3. Viterbi.java


Instructions for compiling the program:


1. Compile the programs using the javac command in the following order:

		javac Calculate.java
		javac ReadFile.java
		javac Viterbi.java

2. This producess the .class files.


Instructions for running the program:


1. To run the program, type :

		java Viterbi <arg1> <arg2>

Here arg1 and arg2 atand for the following:

		arg1 : The name of the model file.
		arg2 : The name of the file containing the observation sequences.

		For example

		java Viterbi model.dat test.dat
                This should run the algorithm and the results should be produced.


