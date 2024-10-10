Shortest Job First
====
In this program, we want to consider 5 jobs A through E with runtimes 3,5,2,2,2 and arrival times of 0,0,5,5,5. We will instruct a user to input the # of jobs when asked and to input the assigned run and arrival times accordingly in order to calculate and output an average wait time.

How It's Made
====
[User Input]

The user will be prompted to insert the # of jobs and for each job the user will provide specific run and arrival times respectfully. The user will also be prompted to input the job execution order.

[Wait Time Calculation]

The program calculates the wait time for each job based on the specified execution order. Waiting time is calculated as the difference between the job's start time and its arrival time.

[Average Wait Time]

The program calculates and outputs the average waiting time for all jobs, which gives a measure of how long, on average, a job waits before it starts execution

[Output]

The job execution order is displayed along with the wait time for each job. The average wait time is also displayed.

Running The Program
====
Programming language: Python

Edge Cases
====
Areas that were considered include an updated function to where the user inputs whatever desired values and the average wait time should still be calculated no matter the job order.
