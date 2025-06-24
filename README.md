# Dynamic-Programming-Series

Dynamic programming is an optimized version of recursion . It remembers past results ( using memoization or tabulation ) to avoid repeated work.


FAMOUS QUOTE :- 

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
❌ Recomputes same subproblems again and again
⚠️ Not efficient for large inputs

## Complexity	  Time	Space (stack)

    Worst Case	O(2ⁿ)	O(n)

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

### 3.) TABULATION ( BOTTOM - UP ) :-
Tabulation is a bottom-up approach in dynamic programming where we solve all smaller subproblems first, store their results in a table (usually an array), 
and use them to build the final answer.

-> In tabulation no recursion is used , only loops are used.

### 4.) RECURSION 

 ## APPROACHES 
