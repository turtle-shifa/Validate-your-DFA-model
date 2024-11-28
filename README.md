# Validate-your-DFA-model
Based on your command, you can input your DFA model and visualise the model also. After importing your DFA model, you can test the model with various test cases to see if it is correct or not.

Process:
![Sample DFA](https://example.com/path/to/image.png](https://github.com/monirulHaque/Automata-and-Computability/blob/main/Media/Lecture2/solve9.png)

You can consider this image as an example.

1. You have to input all DFA states separated by space, like (q0 q1 q2). 
2. Input the start state of the DFA, like (q0).
3. Input all accepting states separated by space, like (q1). It can be more, but I consider the above model.
4. Input all alphabets separated by space, like (0 1).
5. Now you have to provide all state information for making DFA.
6. And after completing your input process, you have to stop by just entering "F."
7. Input information from one state to the next state with the transition value, like
   q0 q1 1
   q0 q2 0
   q1 q1 0
   q1 q1 1
   q2 q2 0
   q2 q2 1
8. Now you can see your DFA model.
9. After being satisfied with the diagram, now you can input test cases to validate or check your DFA model. Is it correct? 
10. If correct, then you can see Accepted; otherwise, Not Accepted.
