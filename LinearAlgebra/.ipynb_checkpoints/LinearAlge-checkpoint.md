 # Linear Algebra

 - Matrices are just linear transformation of vectors

 ## Vectors

 ### Span
- span is a set of linear combinations of 2 vectors 

#### Application in Machine Learning
- Feature Representation: The span of feature vectors can help understand the dimensionality of the feature space and the representational capacity of models.
- Dimensionality Reduction: Techniques like PCA use the concept of span to reduce the number of features while preserving as much variance as possible.

## Linear Transformation
- Dots in a number line(In input space) are evenly spaced in the output space too .. if not thats not a linear trasformation 
- (Transformation is just a function which takes a input and gives you the output)
-  
-  Create a matrix which describes how the trasformation gonna be
-   [[1,2],[2,3]] this is a matrix for transformation where i lands (1,2) j lands (2,3)
    
after the trasformation

- we can consider any vector (2,4) multiply with that matrix we get a linerar trasformation of this vecotor in the desired way we want

- like if we want to see what happens if we rotate a vector 90deg rotation clock wise then first we roate the basis vecotor i and j make a matrix with their landing cord and multiply this matrix with the given vector

## Matrices 
- Matrix multiplication is just Apllying one transformation after other
  (like rotating an vectoer 90 deg than shear like that)

##### "The purpose of computation is insight not number"

# Determinats 
- Determinant just simply says how much that transformation can streach or squeeze the 1x1 matrix
- if the Det is zero it mean the tranformation squeezes the area to a single line or a point
- The scaling can be viewed becase all other sqares scale exaclty the same 

# Matrix Multiplication 
- ## Ax = b
- Here A is a transformation, we are searching for a vector 'x' which lands on the 'b' after appyling that transformation 'A'

## Rank 
- Rank is simply the dimension of the output of a transformation or number of dimensions in the column space 

## Column space 
- Set of all possible dimensions (the span of columns (i,j))

## Null space 
- tells us how all possible solutions are there when a vector is linearly dependent on other (det(A) = 0)
- Ax = b when b is zero and and A is invertable only possiblle valus of x = all zeros
- if A if singular non invertable then then we get bunch if solutions for x inlcuding zeros

## Dot Product
- Dot product is taking 2 (u, w) vectors projecting one(u) vector on to other(w) vector and multiplying the lenght of u on v (After prohecting the u on the v) and the length of the v .
- It takes 2 vetors and produces a scalar
- Tells us the direction the 2 vectors 

## Croos product 
- Take 2 2d vectors , if you move the vecotor to the tip of other vector yoy get a parallelogram . cross product of those 2 vectors give you the area of that parallelogram (determinatn of can find the area for you and the sign tell you its orientation (flipped or not))
- ### vectors in three dimensional space
- these forms a pallelogram but the cross product is a vector whose magnitude is equals to the area of the parellogram and the dorection of the vector would be exctly perpendicular to the plane of the parallegram folloeing right hand tumnb rule (Because there a 2 possible vectors possible with same lenght and the perpunducular)
- 
  