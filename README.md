# assignment7.1
1.Why Map-reduce program is needed in Pig Programming?
 Ans:
Programmers who are not so good at Java normally used to 
struggle working with Hadoop, especially while performing any 
MapReduce tasks. Apache Pig is a boon for all such programmers.
Using Pig Latin, programmers can perform MapReduce tasks easily
without having to type complex codes in Java.
Apache Pig uses multi-query approach, thereby reducing the length of codes

2. What are advantages of pig over MapReduce?
Ans:
In Pig queries are converted into Map and reduce jobs and hence
they take advantages of parallel processing. it has ablity to perform
Computation  which cannot be done by Mapreduce 
3. What is pig engine and what is its importance?
Ans:
It acts as interpreter between pig latin script and mapreduce jobs.
It creating environment to execute pig scripts into series of 
mapreduce jobs in parallel manner.

4. What are the modes of Pig execution?
Ans: 
Basically Pig can be run in local and  HDFS mode.
this can be executed via interactive mode,batch mode and Embedded mode
5. What is grunt shell in Pig?
Ans:
 Its an Interactive Shell for executing Pig Commands which Used 
when script file is not provided.it Can execute scripts from Grunt 
via run or exec commands

6. What are the features of Pig Latin language?
Ans:
Rich set of operators,Ease of programming,Optimization opportunities,
Extensibilit,Create User-defined Functions in other programming languages 
such as Java and invoke or embed them in Pig Scripts
Handles all kinds of data 

7. Is Pig latin commands case sensitive?
Ans:
 Unfortunatelly, we cannot decide the pig commands are case sensitive or not.
The names of Pig Latin functions are case sensitive. 
The names of parameters (see Parameter Substitution) and 
all other Pig Latin keywords are case insensitive.
 Keywords LOAD, USING, AS, GROUP, BY, FOREACH, GENERATE,
 and DUMP are case insensitive.
8. What is a data flow language?
Ans:
Data flow language can get stream of data which passes 
one instruction from another instruction processed.
 In computer programming, dataflow programming is a 
programming paradigm that models a program as a directed graph of 
the data flowing between operations, thus implementing dataflow principles 
and architecture
