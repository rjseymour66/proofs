| Givens         | Goal           | 
| -------------- |:--------------:| 
|                |                | 
|                |                | 
|                |                | 

⋂ ⋃ ⊆ ∀ ∈ ∉ → ∅ ∃ &nbsp;&nbsp;


## ∀xP(x)

### Start
| Givens         | Goal           | 
| ------------- |:--------------:| 
|      ---      |    ∀xP(x)      | 
|      ---      |                | 
|               |                | 


### End

| Givens         | Goal           | 
| ------------- |:--------------:| 
|      ---      |    P(x)        | 
|      ---      |                | 
|               |                | 

Let x be arbitrary  
... [Proof of P(x) goes here]  
Since x was arbitrary, we can conclude ∀xP(x)

### Example

**Step 1**
| Givens         | Goal           | 
| ------------- |:--------------:| 
|   A \ B ⊆ C   |  A \ C ⊆ B     | 
|               |                | 
|               |                | 

**Step 2**
| Givens         | Goal           | 
| ------------- |:--------------:| 
|   A \ B ⊆ C   |  ∀x(x ∈ A \ C → x ∈ B) | 
|               |                | 
|               |                | 

**Step 3**
| Givens         | Goal           | 
| ------------- |:--------------:| 
|   A \ B ⊆ C   |  x ∈ A \ C → x ∈ B | 
|               |                | 
|               |                | 

**Step 4**
| Givens         | Goal           | 
| ------------- |:--------------:| 
|   A \ B ⊆ C   |     x ∈ B      | 
|   x ∈ A \ C   |                | 
|               |                | 

**Step 5**
| Givens         | Goal           | 
| ------------- |:--------------:| 
|   A \ B ⊆ C   |     x ∈ B      | 
|   x ∈ A       |                | 
|   x ∉ C       |                |

**Step 6**
| Givens         | Goal           | 
| ------------- |:--------------:| 
|   A \ B ⊆ C   |     x ∈ B      | 
|   x ∈ A       |                | 
|   x ∉ C       |                |
|   x ∉ B       |                |
|||

Let x be arbitrary  
&nbsp;&nbsp;[Proof of x ∈ A \ C -> x ∈ B goes here]  
Since x was arbitrary, we can conclude ∀x(x ∈ A \ C → x ∈ B).

_Proof_. Let x be arbitrary. Suppose x ∈ A \ C. This means that x ∈ A and x ∉ C. Suppose x ∉ B. Then x ∈ A \ B, so since A \ B ⊆ C, x ∈ C. But this contradicts the fact that x ∉ C. Therefore, x ∈ B. Thus, if x ∈ A \ C, then x ∈ B. Since x was arbitrary, we can conclude that ∀x(x ∈ A \ C → x ∈ B), so A \ B ⊆ C.

## ∀xP(x) example 2

⋂ ⋃ ⊆ ∀ ∈ ∉ → ∅ ∃ &nbsp;&nbsp;

Suppose A and B are sets. Prove that if A ⋂ B = A, then A ⊆ B.

**Step 1**
| Givens         | Goal           | 
| -------------- |:--------------:| 
|  A ⋂ B = A     |     A ⊆ B      | 
|                |                | 
|                |                | 

Suppose A ⋂ B = A.  
&nbsp;&nbsp;[Proof stuff]  
Therefore, if A ⋂ B = A, then A ⊆ B. 

**Step 2**
| Givens         | Goal           | 
| -------------- |:--------------:| 
|  A ⋂ B = A     | ∀x(x ∈ A → x ∈ B) | 
|                |                | 
|                |                | 


**Step 3**
| Givens         | Goal           | 
| -------------- |:--------------:| 
|  A ⋂ B = A     | x ∈ A → x ∈ B  | 
|                |                | 
|                |                | 

Suppose A ⋂ B = A.  
&nbsp;&nbsp;Let x be arbitrary.  
&nbsp;&nbsp;&nbsp;&nbsp;[Proof stuff]    
&nbsp;&nbsp;Since x was arbitrary, we can conclude that ∀x(x ∈ A → x ∈ B), so A ⊆ B.  
Therefore, if A ⋂ B = A, then A ⊆ B. 

**Step 4**
| Givens         | Goal           | 
| -------------- |:--------------:| 
|  A ⋂ B = A     |    x ∈ B       | 
|  x ∈ A         |                | 
|                |                | 

Suppose A ⋂ B = A.  
&nbsp;&nbsp;Let x be arbitrary.  
&nbsp;&nbsp;&nbsp;&nbsp;Suppose x ∈ A.  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Proof of x ∈ B goes here]  
&nbsp;&nbsp;&nbsp;&nbsp;Therefore, x ∈ A → x ∈ B.  
&nbsp;&nbsp;Since x was arbitrary, we can conclude that ∀x(x ∈ A → x ∈ B), so A ⊆ B.  
Therefore, if A ⋂ B = A, then A ⊆ B. 

_Proof_. Suppose A ⋂ B = A, and suppose x ∈ A. Then since A ⋂ B = A, x ∈ A ⋂ B, so x ∈ B. Since x was an arbitrary element of A, we can conclude that A ⊆ B.  


## ∃xP(x)

⋂ ⋃ ⊆ ∀ ∈ ∉ → ∅ ∃ &nbsp;&nbsp;

### Use a given of the form ∃xP(x)
**existential instantiation** - Introduce a new variable x_0 into the proof to stand for an object for which P(x_0) is true. This means that you can now assume that P(x_0) is true. When you see ∃xP(x), you should apply existential instantiation immediately.  
_When you know something exists, you should give it a name._

### Use a given of the form ∀xP(x)
**universal instantiation** - Introduce any value, say a, for x an duse this given to conclude that P(a) is true.


⋂ ⋃ ⊆ ∀ ∈ ∉ → ∅ ∃ ≠ &nbsp;&nbsp;


## Families of sets

Suppose F and G are families of sets and F ⋂ G ≠ ∅. Prove that ⋂F ⊆ ⋃G.

### Step 1
| Givens         | Goal           | 
| -------------- |:--------------:| 
|   F ⋂ G ≠ ∅    |    ⋂F ⊆ ⋃G     | 
|                |                | 
|                |                | 

### Step 2
| Givens         | Goal           | 
| -------------- |:--------------:| 
|   F ⋂ G ≠ ∅    |   ∀x( x ∈ ⋂F → x ∈ ⋃G)     | 
|                |                | 
|                |                | 

### Step 3
| Givens         | Goal           | 
| -------------- |:--------------:| 
|   F ⋂ G ≠ ∅    |   x ∈ ⋂F → x ∈ ⋃G     | 
|                |                | 
|                |                | 

### Step 4
| Givens         | Goal           | 
| -------------- |:--------------:| 
|   F ⋂ G ≠ ∅    |   x ∈ ⋃G       | 
|    x ∈ ⋂F      |                | 
|                |                | 

### Step 4
Expand the statements logically.
| Givens         | Goal           | 
| -------------- |:--------------:| 
|  ∃A(A ∈ F ⋂ G) | ∃A ∈ G(x ∈ A)  | 
|  ∀A ∈ F(x ∈ F) |                | 
|                |                | 

### Step 4
Since ∃A(A ∈ F ⋂ G), we can say that there is a set, A_0, that is an element of F and G.
| Givens         | Goal           | 
| -------------- |:--------------:| 
|  A_0 ∈ F       | ∃A ∈ G(x ∈ A)  | 
|  A_0 ∈ G       |                |
|  ∀A ∈ F(x ∈ F) |                | 
|                |                | 

_Proof_. Suppose x ∈ ⋂F. Since F ⋂ G ≠ ∅, we can let A_0 be an element of F ⋂ G. Thus, A_0 ∈ F and A_0 ∈ G. Since x ∈ ⋂F and A_0 ∈ F, it follows that x ∈ A_0. But we also know that x A_0 ∈ G, so we can conclude that x ∈ ⋃G.