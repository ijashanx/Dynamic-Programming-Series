# Dynamic-Programming-Series

Dynamic programming is an optimized version of recursion . It remembers past results ( using memoization or tabulation ) to avoid repeated work.


* FAMOUS QUOTE :- 

" Those who cannot remember the past are condemned to repeat it ."

Depth of above code depicts importance of D.P.

## PROPERTIES OF D.P :- 

###  1.) OVERLAPPING SUBPROBLEMS :- 
If a problem repeats the same calculations for the same inputs again and again, then it has overlapping subproblems.

### 2.) OPTIMAL SUBSTRUCTURE  :-
Problem can be solved using optimal solutions of its subproblems.

## APPROACHES TO SOLVE D.P :- 

### 1.) RECURSION ( BRUTE - FORCE ) ( TOP - DOWN ) :- 

Recursion is a process in which a function calls itself to solve a problem by breaking it down into smaller subproblems.

🔁 Calls itself for smaller inputs
❌ Recomputes same subproblems again and again.    
⚠️ Not efficient for large inputs    

    Complexity	  Time Complexity 	  Space Complexity 

    Worst Case	      O(2ⁿ)	               O(n)(stack)


### 2.) MEMOIZATION ( TOP - DOWN ) :- 
Tend to store the value of subproblems in array , map or dictionary .

📌 Recursion + Caching of already solved subproblems

✅ Avoids recomputation using a dp[] array or Map  
🔄 Top-down recursion  
🧠 Good for recursive thinkers  

### ADVANTAGES :- 

-> It is used with recursion .  
-> It helps in optimizing DP.  
-> It improves Time complexity .  

     Complexity 	 Time Complexity 	       Space Complexity 
      Improved	        O(n)	             O(n)(stack) + O(n)(dp)


### 3.) TABULATION ( BOTTOM - UP ) :-
Tabulation is a bottom-up approach in dynamic programming where we solve all smaller subproblems first, store their results in a table (usually an array), 
and use them to build the final answer.

-> In tabulation no recursion is used , only loops are used.  

📌 Iterative solution from smallest subproblem to final result  
✅ Removes recursion overhead  
✅ Fills dp[] table in order  
🔽 Starts from base case, builds up  

        Complexity     Time complexity          Space complexity                   
         Efficient        O(n)                 O(n)  (table/array)

### 4.) TABULATION USING SPACE OPTIMIZATION :- 
Space Optimization is a technique where we reduce the space used in tabulation (bottom-up DP) by only keeping track of the most recent values needed, 
instead of storing the entire DP table.

📌 Optimize tabulation to use only required previous values  
✅ No recursion, no full dp[] table  
✅ Stores only what is necessary (e.g., last 2 values in Fibonacci)  


       Complexity	Time Complexity 	Space Complexity 
       Best Form	     O(n)	             O(1)


## CONCLUSION :- 

Always start with recursion to understand the problem.  
If it has overlapping subproblems, apply memoization.  
For more efficiency, move to tabulation and finally use space optimization where possible.  
   

