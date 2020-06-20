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