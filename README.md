| Given         | Goal           | 
| ------------- |:--------------:| 
|               |                | 
|               |                | 
|               |                | 


## All x for P(x)

### Start
| Given         | Goal           | 
| ------------- |:--------------:| 
|      ---      |    ∀xP(x)      | 
|      ---      |                | 
|               |                | 


### End

| Given         | Goal           | 
| ------------- |:--------------:| 
|      ---      |    P(x)        | 
|      ---      |                | 
|               |                | 

Let x be arbitrary  
... [Proof of P(x) goes here]  
Since x was arbitrary, we can conclude ∀xP(x)

### Example

**Step 1**
| Given         | Goal           | 
| ------------- |:--------------:| 
|   A \ B ⊆ C   |  A \ C ⊆ B     | 
|               |                | 
|               |                | 

**Step 2**
| Given         | Goal           | 
| ------------- |:--------------:| 
|   A \ B ⊆ C   |  ∀x(x ∈ A \ C -> x ∈ B) | 
|               |                | 
|               |                | 

**Step 3**
| Given         | Goal           | 
| ------------- |:--------------:| 
|   A \ B ⊆ C   |  x ∈ A \ C → x ∈ B | 
|               |                | 
|               |                | 

**Step 4**
| Given         | Goal           | 
| ------------- |:--------------:| 
|   A \ B ⊆ C   |     x ∈ B      | 
|   x ∈ A \ C   |                | 
|               |                | 

**Step 5**
| Given         | Goal           | 
| ------------- |:--------------:| 
|   A \ B ⊆ C   |     x ∈ B      | 
|   x ∈ A       |                | 
|   x ∉ C       |                |

**Step 6**
| Given         | Goal           | 
| ------------- |:--------------:| 
|   A \ B ⊆ C   |     x ∈ B      | 
|   x ∈ A       |                | 
|   x ∉ C       |                |
|   x ∉ B       |                |
|||

Let x be arbitrary  
... [Proof of x ∈ A \ C -> x ∈ B goes here]  
Since x was arbitrary, we can conclude ∀x(x ∈ A \ C -> x ∈ B).

_Proof_. Let x be arbitrary. Suppose x ∈ A \ C. This means that x ∈ A and x ∉ C. Suppose x ∉ B. Then x ∈ A \ B, so since A \ B ⊆ C, x ∈ C. But this contradicts the fact that x ∉ C. Therefore, x ∈ B. Thus, if x ∈ A \ C, then x ∈ B. Since x was arbitrary, we can conclude that ∀x(x ∈ A \ C → x ∈ B), so A \ B ⊆ C.