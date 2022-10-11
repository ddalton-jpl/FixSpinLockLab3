NAME: DILLON DALTON, SCHUYLER ASPLIN

DESCRIPTION: unzip the submitted dDaltonCSCDLab3.zip you get a folder named FIXSPINLOCKLAB3

TO COMPILE: cd into FIXSPINLOCKLAB3, cd into src, javac *.java

TO RUN: java Alternation

1. Why the provided solution does NOT work? Which statement(s) cause the program to hang up?
 - The given program does not work because the lock causes the while loop to stick and not alternate values

2. How did you fix that problem?
- Created a Syncronized method that pulls the while loop out of a sync block

3. How does your changes fix the problem?
- The hold on the lock is short lived and allows the hold to alternate
