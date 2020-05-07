### Generating set and Span

* Consider a vector space V = (V, +, ·) and set of vectors A = {x1, ..., xk} ⊆ V.
* If every vector v ∈ V can be expressed as a linear combination of x1, ..., xk, A is called a generating set of V.
* The set of all linear combinations of vectors in A is called the span of A.
* If A spans the vector space V, we write V = span(A) or V = span(x1, ..., xk).

### Basis

* Consider a vector space V = (V, +, ·) and A ⊆ V.
* A generating set A of V is called minimal if there exists no smaller set A0 ⊆ A ⊆ V that spans V.
* Every linearly independent generating set of V is minimal and is called a basis of V.
* 따라서, Basis (기저)는 여러 개가 될 수 있음
* 표준 기저 (Standard Basis)는 다음과 같음

![image](https://user-images.githubusercontent.com/16822641/81294452-e3909e80-90a9-11ea-8898-305e5747ff18.png)

### Dimension

* There can be many basis of a vector space.
* However, all bases possess the same number of basis vectors.
* <b>The number of basis vectors are called dimension of the vector space.</b>
* The dimension is not necessarily the number of elements in a vector.

### Rank

* Rank of matrix A
    * The number of linearly independent columns of a (m, n) matrix A.
    * (=) The number of linearly independent rows of a (m, n) matrix A.
* Remark (Properties of rank)
    * The columns of A span a subspace U with dim(U) = rk(A).
        * This subspace is called image or range.
    * A matrix A has full rank if rk(A) = min(n, m).
    * A (m, m) square matrix B is invertible iff B has full rank.
