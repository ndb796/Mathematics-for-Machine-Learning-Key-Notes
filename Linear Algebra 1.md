### Linear Algebra

* Algebra: Study of a set of objects and a set of manipulation rules
* <b>Linear Algebra: Study of a set of vectors and a set of rules to manipulate vectors</b>

### Vector

* A quantity or phenomenon that has two independent properties: magnitude and direction
* Vectors satisfy
    * vector + vector = vector
    * scalar * vector = vector
* Examples of vectors: Geometric vectors, Polynomials, Audio signals
* For example:

![image](https://user-images.githubusercontent.com/16822641/81254770-05b4fd00-9067-11ea-9ae4-7ee8f22fb4c4.png)

### System of Linear Equations

* 연립 일차 방정식
* System of linear equation is the central part of linear algebra.
    * Many real world problem can be formulated as system of linear equations.
    * Linear algebra gives a tool for solving the system.
* 형태는 다음과 같음

![image](https://user-images.githubusercontent.com/16822641/81255653-2f6f2380-9069-11ea-85aa-6fd0e99f10be.png)

### Geometric Understanding of Linear Equations

* 2차원 상에서의 시스템을 기하학적으로 이해할 수 있음

![image](https://user-images.githubusercontent.com/16822641/81256082-59751580-906a-11ea-9eaf-38de054c51f1.png)

* 3차원이 넘어가는 공간에서는 기하학적으로 표현할 수 없음

### Matrix

* (m, n) matrix A is an (m x n) tuple of elements
* Compact representation of the system of linear equations
* Represent linear mappings

![image](https://user-images.githubusercontent.com/16822641/81256176-a8bb4600-906a-11ea-9557-4d1dacc73189.png)

### Matrix Addition and Multiplication

* Sum of (m, n) matrix A and (m, n) matrix B

![image](https://user-images.githubusercontent.com/16822641/81257151-870f8e00-906d-11ea-889c-05b5db688757.png)

* Multiplication of (m, n) matrix A and (n, k) matrix B

![image](https://user-images.githubusercontent.com/16822641/81257178-92fb5000-906d-11ea-966e-ce4fb222f5b6.png)

* Matrices can only be multiplied if their neighboring dimensions match.
* <b>Hadamard product</b> is an element-wise multiplication.

### Identity Matrix

* Identity matrix is a diagonal matrix where the diagonal entries are filled with ones.

![image](https://user-images.githubusercontent.com/16822641/81257523-73b0f280-906e-11ea-9c19-e73f18e7ed7c.png)

### Properties of Matrices

* 결합법칙 (Associativity)
    * (AB)C = A(BC)

* 분배법칙 (Distributivity)
    * (A + B)C = AC + BC
    * A(C + D) = AC + AD

* Multiplication with identity matrix
    * AI = IA = A

* Multiplication is not commutative (교환법칙은 성립하지 않음)

### Inverse

* 역행렬
* Consider a (n, n) square matrix A.
    * Let (n, n) matrix B have the property that AB = I = BA.
    * B is called the inverse of A.
* Not every matrix has an inverse.
* If an inverse exist, then the matrix is called regular/invertible/nonsingular.
* Otherwise, singular/noninvertible.

### Transpose

* 전치행렬
* For A (m, n) matrix A, <b>the (n, m) matrix B with bij = aji is called the transpose of A.</b>

### Symmetric Matrix

* 대칭행렬
* <b>A (n, n) matrix A is symmetric if A = transpose of A.</b>

### Compact representation of system of linear equations

* We can rewrite the system of linear equations with matrices and vectors

![image](https://user-images.githubusercontent.com/16822641/81260050-2e8fbf00-9074-11ea-8dd2-28e847af0b21.png)

