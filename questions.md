1. (a) What does it mean to say that a set $S = \{ \mathbf { u } _ { 1 } , \dots , \mathbf { u } _ { k } \}$ of vectors in $\mathbb { R } ^ { n }$ is linearly independent? Give the precise definition in one or more full sentences. Then describe what this means in terms of the matrix A with columns $\mathbf { u } _ { 1 } , \ldots , \mathbf { u } _ { k }$ 

(b) Do the three vectors ${ \bf u } _ { 1 } = \left[ \begin{array} { r } { 1 } \\ { 3 } \\ { - 2 } \end{array} \right] , { \bf u } _ { 2 } = \left[ \begin{array} { r } { 3 } \\ { 5 } \\ { - 3 } \end{array} \right]$ , and $\mathbf { u } _ { 3 } ~ = ~ \left[ { \begin{array} { r } { 1 } \\ { - 1 } \\ { 2 } \end{array} } \right]$ make up a linearly independent set? Justify your answer using the matrix A as in (a). 

2. (a) What is meant by the span of a set $S = \{ \mathbf { u } _ { 1 } , \dots , \mathbf { u } _ { k } \}$ of vectors in $\mathbb { R } ^ { n } ?$ Give the precise definition in one or more full sentences. Then describe what this means in terms of the matrix A with columns $\mathbf { u } _ { 1 } , \ldots , \mathbf { u } _ { k }$ 

(b) Suppose that ${ \bf u } _ { 1 } = \left[ \begin{array} { r } { 1 } \\ { 3 } \\ { - 2 } \end{array} \right] , { \bf u } _ { 2 } = \left[ \begin{array} { r } { 3 } \\ { 5 } \\ { - 3 } \end{array} \right]$ , and $\mathbf { u } _ { 3 } = \left[ { \begin{array} { r } { 1 } \\ { - 1 } \\ { 2 } \end{array} } \right]$ . Is the span of the set of vectors $S = \{ \mathbf { u } _ { 1 } , \mathbf { u } _ { 2 } , \mathbf { u } _ { 3 } \}$ all $\mathbb { R } ^ { 3 } ?$ Justify your answer using the matrix A as in (a). 

3. Answer questions 1 and 2 when $\mathbf { u } _ { 3 }$ is changed to $\mathbf { u } _ { 3 } = \left[ { \begin{array} { r } { 1 } \\ { - 1 } \\ { 1 } \end{array} } \right]$ 

4. In $\mathrm { ( a ) - ( c ) }$ below we suppose that we have a system of equations $A \mathbf { x } = \mathbf { b }$ and that we have used row operations to transform the augmented matrix $\left[ A \ \mathbf { b } \right]$ to the reduced row-echelon form $[ R { \textbf { c } } ]$ given below. In each case, determine (i) whether the original equations have a solution; (ii) if they do have a solution, whether or not it is unique; and (iii) if it is not unique, how many free parameters there are in the solution. Then write the solution explicitly as a fixed vector plus a linear combination of vectors y that satisfy $A \mathbf { y } = 0$ with the free variables as coeficients. 

(a) 

$$
[ R \mathbf {c} ] = \left[ \begin{array}{c c c c c c} 1 & 5 & 0 & 2 & 8 & 0 \\ 0 & 0 & 1 & - 1 & 0 & 0 \\ 0 & 0 & 0 & 0 & 0 & 1 \end{array} \right]\tag{b}
$$

$$
[ R \mathbf {c} ] = \left[ \begin{array}{c c c c c} 1 & 0 & 0 & 0 & 2 \\ 0 & 1 & 0 & 0 & - 1 \\ 0 & 0 & 1 & 0 & 3 \\ 0 & 0 & 0 & 1 & 4 \end{array} \right]\tag{c}
$$

$$
[ R \mathbf {c} ] = \left[ \begin{array}{l l l l l l l} 0 & 1 & 2 & 0 & - 2 & 0 & 2 \\ 0 & 0 & 0 & 1 & 3 & 0 & - 1 \\ 0 & 0 & 0 & 0 & 0 & 1 & 3 \\ 0 & 0 & 0 & 0 & 0 & 0 & 0 \end{array} \right]
$$

5. In each part below, give a $m \times n$ matrix R in reduced row-echelon form satisfying the given condition, or explain briefly why it is impossible to do so. 

(a) $m = 3 , n = 4$ , and the equation $R \mathbf { x } = \mathbf { c }$ has a solution for all c. 

(b) $m = 3 , n = 4$ , and the equation $R \mathbf { x } = \mathbf { 0 }$ has a unique solution. 

(c) $m = 4 , n = 3$ , and the equation $R \mathbf { x } = \mathbf { c }$ has a solution for all c. 

(d) $m = 4 , n = 3$ , and the equation $R \mathbf { x } = \mathbf { 0 }$ has a unique solution. 

(e) $m = 4 , n = 4$ , and the equation $R \mathbf { x } = \mathbf { 0 }$ has no solution. 

(f) $m = 4 , n = 4$ , and the equation $R \mathbf { x } = \mathbf { 0 }$ has a nontrivial solution. 

(g) $m = 4 , n = 4$ , and for every c the equations $R \mathbf { x } = \mathbf { c }$ have a solution containing a free parameter. 

6. (a) Suppose that u and v are solutions of the system of equations $A \mathbf { x } = \mathbf { 0 }$ . Show that $c \mathbf { u } + d \mathbf { v }$ is also a solution, for any scalars c and d. 

(b) Why does the above conclusion not hold (in general) if the system of equations is $A \mathbf { x } = \mathbf { b }$ with b a nonzero vector? 

7. Suppose that 

$$
A = \left[ \begin{array}{c c} 1 & 3 \\ - 1 & 2 \end{array} \right], \quad B = \left[ \begin{array}{c c c} 3 & 2 & - 1 \\ - 1 & 2 & 0 \end{array} \right], \quad C = \left[ \begin{array}{c c} - 2 & 3 \\ 3 & - 3 \\ 4 & 1 \end{array} \right].
$$

Which of the following quantities are defined? Calculate those that are defined. 

(a) BA (b) AB (c) $3 C - 2 B ^ { T }$ (d) BC (e) $C A B$ (f) $C + 2 A \quad \mathrm { ( g ) } \ C ^ { T } C .$ 

8. Let A be an $m \times n$ matrix of rank r. What can you conclude about m, n, and r (other than $r \leq m$ and $r \leq n$ which is always true) if the equation $A \mathbf { x } = \mathbf { b }$ has 

(a) exactly one solution for some b and no solution for other b? 

(b) infinitely many solutions for all b? 

(c) exactly one solution for every b? 

(d) infinitely many solutions for some b and no solutions for other b? 

(e) exactly one solution when $\mathbf { b } = \mathbf { 0 } ?$ 

9. (a) Suppose that A and B are $4 \times 5$ matrices and that B is obtained from A by the row operation given below. In each case give an elementary matrix E such that $B = E A$ 

$$
\mathbf {r} _ {1} \leftrightarrow \mathbf {r} _ {4},
$$

$$
\mathbf {r} _ {3} + 3 \mathbf {r} _ {2} \rightarrow \mathbf {r} _ {3},
$$

$$
7 \mathbf {r} _ {2} \rightarrow \mathbf {r} _ {2}.
$$

(b) Give the inverses of the elementary matrices found in (i), (ii), and (iii) above. (You can do this without calculation; think about reversing the corresponding row operations.) 

10. A certain $3 \times 3$ matrix $A = \left[ \mathbf { a } _ { 1 } \ \mathbf { a } _ { 2 } \ \mathbf { a } _ { 3 } \right]$ has reduced row echelon form $R = \left[ { \begin{array} { r r r } { 1 } & { 0 } & { - 3 } \\ { 0 } & { 1 } & { 2 } \\ { 0 } & { 0 } & { 0 } \end{array} } \right]$ 

(a) Find a nontrivial linear relation on the columns of A, that is, a relation $c _ { 1 } \mathbf { a } _ { 1 } + c _ { 2 } \mathbf { a } _ { 2 } + c _ { 3 } \mathbf { a } _ { 3 } = \mathbf { 0 }$ with $c _ { 1 } , \ : c _ { 2 } .$ , and $c _ { 3 }$ not all zero. 

(b) Suppose that $\mathbf { a } _ { 1 } = { \left[ \begin{array} { l } { 0 } \\ { 4 } \\ { 5 } \end{array} \right] }$ and $\mathbf { a } _ { 2 } = { \left[ \begin{array} { l } { 1 } \\ { 2 } \\ { 3 } \end{array} \right] }$ . Find $\mathbf { a } _ { 3 } .$ 

11. (a) Suppose that A is a square matrix. What does it mean to say that A is invertible? (Give the definition, not one of the many equivalent conditions in Theorem 2.6 of the text.) 

(b) Suppose that A and B are invertible $n \times n$ matrices. Show that $( A B ) ^ { - 1 } = B ^ { - 1 } A ^ { - 1 }$ 

(c) Suppose that A is an invertible $n \times n$ matrix. Show that $( A ^ { T } ) ^ { - 1 } = ( A ^ { - 1 } ) ^ { T }$ 

12. Use row reduction to show that the matrix $\left[ { \begin{array} { r r r } { 0 } & { 2 } & { - 1 } \\ { 1 } & { - 1 } & { 2 } \\ { 2 } & { - 1 } & { 3 } \end{array} } \right]$ is invertible and to find its inverse. 

13. Do the True-False questions from Sections 1.1–1.4, 1.6, 1.7, 2.1, 2.3, and 2.4 that are listed in the homework assignments. 