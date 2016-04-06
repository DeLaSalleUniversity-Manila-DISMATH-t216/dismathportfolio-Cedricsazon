# dismathportfolio-Cedric Paul M. Sazon DISMATH EL

dismathportfolio-Cedricsazon created by Classroom for GitHub

#WEEK 1 
- I thought it would just be an ordinary orientation day of the course but before dismissal the class was presented with two questions about Knight and Knaves which gave our mind a fun challenge of our logic.
- After the orientation, I was pretty sure that this course is going to be challenging
- I also realized that you really have to use you head and you have to think alot in this subject.

#WEEK 2
- First day of lessons, I was very excited as to what the course has prepared for the class
- A proposition is a statement that is either true(1) or false(0)
- Logical deduction is a process of reasoning from one ore more statements (premises) to reach a logically certain conclusion
- In order to understand Discrete Math, I had to study the Logical Connectives which was very new to me 
- Logical Connectives
    - Negation (¬, not)
    - Conjunction (∧, and)
    - Disjunction (∨, or)
    - Exclusive Or (⊕, xor)
    - Conditional (→, if,then)
    - Biconditional (↔, iff)
-  And then, the all powerful Truth Table, lists the possible combinations of the input with their corresponding output
-  Logical Equivalences was also discussed 
    - Identity Law
    - Domination Law
    - Negation Law
    - Double Negation Law
    - Idempotent Law
    - Commutative Law
    - Associative Law
    - Distributive Law
    - De Morgan's Law
    - Absorption Law
 - Rules of Inference (terminologies)
    - argument is a sequence of statements that end with a question
    - valid is the conclusion or final statment of the argument, must follow from the truth of the preceding statements, or premises, of the argument
    - fallacy is common form of incorrect reasoning which lead to invalud arguments
    - tautology is a statement that is always true
    * Modus Ponens
    * Modus Tollens
    * Hypothetical syllogism
    * Disjunctive syllogism
    * Addition
    * Simplification
    * Conjuction
    * Resolution
- Implication Equivalence: p→q = ¬p∨q
- At the end of the week, I observed that after every class I feel mentally exhausted
- However, the fun part was an assignment proving that Superman does not exist (logically)

#WEEK 3
- 4 methods of Proof:
    - Direct Proof
    - Proof by Contraposition (Indirect)
    - Proof by Contradiction (Indirect)
    - Proof by Equivalence 

- Direct Proof:
    - First, we assume P is true.
    - Then, we show that q is also true.
    
- Proof by Contraposition:
    - First, we assume ¬q is true.
    - Then, we show that ¬p is true.
    
- Proof by Contradiction:
    - First assume ¬p is true.
    - Then, show that ¬q is true.
    
- Vacaous and Trivial Proof:
    - For Vacuous Proof, p is false because p→q must be true when p is false.
    - For Trivial Proof, q is true, it follows that p→q must also be true.

#WEEK 4
- Proof by Equivalence:
    - p→q and q→p are both true.

- Mathematical Induction:
    - Basis Step
    - Inductive Step

#WEEK 5

  ➤ **Program Correctness**
  
    •Includes 2 steps:
    
      1.) Partial correctness
         
          - initial assertion(input)
          
          - final assertion (output)
    
      2.) Show that the program terminates correctly
  
  ➤ **Hoare Triple**
  
      •Symbol: p{S}q
      
         note:
          
           - p = initial assertion
         
           - {S} = program segment
         
           - q = final assertion
           
      • Steps:
      
        1.) Assume tha p is TRUE
        
        2.) Substitute to the program {S}, showing that q is TRUE
  
  ➤ **Power Series**
  
      - Example: Zeno's Paradox
      
      - Can be solved using GEOMETRIC SERIES formula:
      
        a1/ 1-r
  
  ➤ **Introduction to set theory**
  
      • Set
      
         - Is an unordered collection of objects
        
            a.)Set Difference
            
                 - (A-B) or (A/B)
                 
            b.) Set Intersection
            
                 - A△B
                 
      • Power Set
      
          - Is a set containing all subsets 
  
#WEEK 6 
 
  ➤ **Cardinality**
    
    • Is the total number of distinct elements.
    
    •  New Terminology:
        
        ✓ ℵ₀ 
           
          -is pronounced as “aleph-zero"/“alephnought”/“aleph-null”
  
  ➤ **Review**
  
   • Nested Quantifiers
   
      - 2 quantifiers are nested if one is within the sccope of the other.
      
      - Examples:
      
          ✓ ∀x∀y(x≠y) 
          
          ✓ ∃x∃y(x≠y)
          
          ✓ ∀x∃y(x≠y)
          
          ✓ ∃y∀x(x≠y)
  
  ➤ **Functions**
    
    • Types:
      
       ✓ One-to-one function
       
          - each domain is assigned to a certain co-domain
          
          - no common co-domain
       
       ✓ Onto Function
       
         - each co-domain is assigned to a domain.
         
         - no co-domain is left without a partner. 

#WEEK 7

➤ No Classes for the whole week

#WEEK 8

➤ **Algorithm**

    - is a finite set of precise instruction
    
       ✓ Precondition
    
           - describes the input
    
       ✓ Postcondition
    
           - describes what the output should satisfy
    
        ✓ Properties:
      
           • Input
      
           • Output
      
           • Definiteness
      
           • Correctness
      
           • Finiteness
           
           • Generality
    
➤ **Psuedocode**

    - is a high level description of an algorithm that uses the structural conventions of programming knowledge

#WEEK 9

➤ **Seaching Algorithm**

    - The problem of locating an element in an ordered list

➤ **Linear Search**

    - Precondition: ({A1,A2,...,Ai,...An})
    
      Postcondition: location of x (loc)
      
      i=1
      
      while [(x≠A)^(i≤n)]
       
          i = i+1
        
        if(i≤n)
          
          loc = i
        
        else
        
           loc = -1

➤ **Binary Search**

    -  Precondition: ({A1,A2,...,Ai,...An})
    
       Postcondition: location of x (loc)
    
          while [(i≠j) ≠ (i>j)]
              
             mid = [(i+j)/2]
             
                if x>A(mid) 
                   
                   then i = 1+mid
                   
                else j=mid
                
                if (x==Ai)
                
                    loc=i
                
                else 
                
                   loc = -1;
    
#WEEK 10

➤ **Sorting Algorithm**

    - the problem of putting elements in increasing order

➤ **Bubble sort**

    - Precondition: ({A1,A2,...,Ai,...An})
    
      Postcondition: (X1<X2<...<Xn)
      
          for j: 1 to n-1
      
             for i: 1 to n-j
        
                if(Ai > Aj+1)
          
                   swap (Ai,Ai+1)

➤ **Insertion sort**
 
    - Precondition: ({A1,A2,...,Ai,...An}) ∈ n≥2 for j= 2 to n
    
      Postcondition: (X1<X2<...<Xn)
      
          for j = 2 to n
              
              i = 1
              
          while Aj>Ai
            
              i = i+1
              
           m = Aj
           
           for k = 0 to j-i-1
           
            Aj-k = Aj-i-1
          
          Ai = m

➤ **Greedy Algorithm**
  
  - Selects the best choice instead of considering all sequences
 
  - applied in optimization problems

  - Precondition: ({C1,C2,...,Ci,...Cn})
    
      Postcondition: (C1>C2>...>Cni n ∈ Z+) 
      
          for i = 1 to 4 
      
            while(n≥Ci)
        
                n = n-Ci
          
                   n = n+1

#WEEK 11

➤ **Growth of Functions**

    - is often described using the big o notation

➤ **Big O Notation**
    
    - Let f and g be functions from R to Ri f(x) is O(g(x)) if there are constants c and k such that 
       
       |f(x)|≤ C|g(x)| whenever x>k

➤ **Big Omega**

    - lower bound of a function
    
➤ **Big Theta**

    - lower and upper bound of a function
   
➤ **Complexity of Algorithms**

    - can be expressed in term of the number of operationsused by the algorithm when the input has a particular size

#WEEK 12

➤ No Classes for the whole week

#WEEK 13

➤ **Graph Theory**

    - consist of vertices/nodes and degrees/edges

➤ **Handshaking Theorem**

    - formula: 2e = Σ(degrees)*v
    
➤ **Euler Path**

    - covers all the edges/degrees
    - is open 
    - has a different starting and ending point
    
➤ **Euler Circuit**

    - covers all the edges/degrees
    - is closed 
    - has the same starting and ending point
    
➤ **Hamilton Path**

    - covers all the nodes/vertices
    - is open
    - has a different starting and ending point
    

➤ **Hamilton Circuit**

    - covers all the nodes/vertices
    - is closed
    - has the same starting and ending point

➤ **Matrices**

    • Adjacency Matrix
       - relationship between the nodes/vertices
       
    • Incidence Matrix
       - relationship between the edges/degrees

➤ **Isomorphism**

    - is the comparison of 2 graphs

➤ **Planar**

    - is a plane that has no intersecting lines/edges/degrees

➤ **Non-Planar**

    - is a plane that has intersecting lines/edges/degrees

➤ **Euler's Formula**

    - formula: r = e(edges) - v(vertices) + 2

