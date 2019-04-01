It is my first git repository where i have solved an interesting problem in java.
The plot of the problem is provided below:-

We have a lock  with 4 circular wheels. Each wheel has 10 slots ranging from 0 to 9. The wheels can rotate freely and wrap around: for example we can turn '9' to be '0', or '0' to be '9'. Each move consists of turning one wheel one slot.

The lock initially starts at '0000', a string representing the state of the 4 wheels.

We are given a list of  dead ends, meaning if the lock displays any of these codes, the wheels of the lock will stop turning and lock will get permanently locked.

Given a key representing the value of the wheels that will unlock the lock, we have to return the minimum total number of turns required to open the lock, or -1 if it is impossible.