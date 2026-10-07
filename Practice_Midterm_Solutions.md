# CS 205 FALL 2026: INTRO TO DISCRETE STRUCTURES I PRACTICE EXAM: MIDTERM 1

## Instructions

(1) Write your name, NetID, and section number. 

(2) The exam consists of 8 problems (each with multiple subparts) total worth 80 points. Attempt all the problems 1-8. 

(3) You will have 80 minutes to complete the exam. 

(4) You must write your solutions in the space provided. 

(5) Show all your work and steps. Writing down just the final answer without explanation will not give you credit. There will be partial credit for progress towards correct solutions. 

(6) Write clearly and logically. State your assumptions and any facts used. 

(7) You may use any results proved in class without re-proving them, unless the question explicitly asks for the proof. 

(8) No electronic devices allowed. 

## 1. Useful logical equivalences

<table><tr><td>Equivalence</td><td>Name</td></tr><tr><td><eq>p \land \mathbf{T} \equiv p</eq><eq>p \lor \mathbf{F} \equiv p</eq></td><td>Identity laws</td></tr><tr><td><eq>p \lor \mathbf{T} \equiv \mathbf{T}</eq><eq>p \land \mathbf{F} \equiv \mathbf{F}</eq></td><td>Domination laws</td></tr><tr><td><eq>p \lor p \equiv p</eq><eq>p \land p \equiv p</eq></td><td>Idempotent laws</td></tr><tr><td><eq>\neg(\neg p) \equiv p</eq></td><td>Double negation law</td></tr><tr><td><eq>p \lor q \equiv q \lor p</eq><eq>p \land q \equiv q \land p</eq></td><td>Commutative laws</td></tr><tr><td><eq>(p \lor q) \lor r \equiv p \lor (q \lor r)</eq><eq>(p \land q) \land r \equiv p \land (q \land r)</eq></td><td>Associative laws</td></tr><tr><td><eq>p \lor (q \land r) \equiv (p \lor q) \land (p \lor r)</eq><eq>p \land (q \lor r) \equiv (p \land q) \lor (p \land r)</eq></td><td>Distributive laws</td></tr><tr><td><eq>\neg(p \land q) \equiv \neg p \lor \neg q</eq><eq>\neg(p \lor q) \equiv \neg p \land \neg q</eq></td><td>De Morgan’s laws</td></tr><tr><td><eq>p \lor (p \land q) \equiv p</eq><eq>p \land (p \lor q) \equiv p</eq></td><td>Absorption laws</td></tr><tr><td><eq>p \lor \neg p \equiv \mathbf{T}</eq><eq>p \land \neg p \equiv \mathbf{F}</eq></td><td>Negation laws</td></tr></table>

$$
p \to q \equiv \neg p \lor q
$$

$$
p \rightarrow q \equiv \neg q \rightarrow \neg p
$$

$$
p \vee q \equiv \neg p \rightarrow q
$$

$$
p \land q \equiv \lnot (p \rightarrow \lnot q)
$$

$$
\neg (p \to q) \equiv p \land \neg q
$$

$$
p \leftrightarrow q \equiv (p \rightarrow q) \land (q \rightarrow p)
$$

$$
(p \to q) \land (p \to r) \equiv p \to (q \land r)
$$

$$
p \leftrightarrow q \equiv \neg p \leftrightarrow \neg q
$$

$$
(p \to r) \land (q \to r) \equiv (p \lor q) \to r
$$

$$
p \leftrightarrow q \equiv (p \land q) \lor (\lnot p \land \lnot q)
$$

$$
\neg (p \leftrightarrow q) \equiv p \leftrightarrow \neg q
$$

$$
(p \to q) \vee (p \to r) \equiv p \to (q \vee r)
$$

$$
(p \to r) \lor (q \to r) \equiv (p \land q) \to r
$$

<table><tr><td>Rule of Inference</td><td>Tautology</td><td>Name</td></tr><tr><td><eq>p</eq><eq>\underline{p \rightarrow q}</eq><eq>\therefore \underline{q}</eq></td><td><eq>(p \land (p \rightarrow q)) \rightarrow q</eq></td><td>Modus ponens</td></tr><tr><td><eq>\neg q</eq><eq>\underline{p \rightarrow q}</eq><eq>\therefore \neg p</eq></td><td><eq>(\neg q \land (p \rightarrow q)) \rightarrow \neg p</eq></td><td>Modus tollens</td></tr><tr><td><eq>p \rightarrow q</eq><eq>\underline{q \rightarrow r}</eq><eq>\therefore \underline{p \rightarrow r}</eq></td><td><eq>((p \rightarrow q) \land (q \rightarrow r)) \rightarrow (p \rightarrow r)</eq></td><td>Hypothetical syllogism</td></tr><tr><td><eq>p \lor q</eq><eq>\neg p</eq><eq>\therefore \underline{q}</eq></td><td><eq>((p \lor q) \land \neg p) \rightarrow q</eq></td><td>Disjunctive syllogism</td></tr><tr><td><eq>\underline{p}</eq><eq>\therefore \underline{p \lor q}</eq></td><td><eq>p \rightarrow (p \lor q)</eq></td><td>Addition</td></tr><tr><td><eq>\underline{p \land q}</eq><eq>\therefore \underline{p}</eq></td><td><eq>(p \land q) \rightarrow p</eq></td><td>Simplification</td></tr><tr><td><eq>\underline{p}</eq><eq>\underline{q}</eq><eq>\therefore \underline{p \land q}</eq></td><td><eq>((p) \land (q)) \rightarrow (p \land q)</eq></td><td>Conjunction</td></tr><tr><td><eq>p \lor q</eq><eq>\neg p \lor r</eq><eq>\therefore \underline{q \lor r}</eq></td><td><eq>((p \lor q) \land (\neg p \lor r)) \rightarrow (q \lor r)</eq></td><td>Resolution</td></tr></table>

Question 1 (10 points). Let $p , q ,$ and r be propositions. 

(a) Write down the truth table for the compound proposition $C : ( p \oplus q ) \land ( p \lor \neg r ) \land ( \neg p \lor \neg q \lor r )$ . Is C satisfiable? Justify your conclusion and show all steps. 

<table><tr><td>p</td><td>q</td><td>r</td><td>p ⊕ q</td><td>p ∨ ¬r</td><td>¬p ∨ ¬q ∨ r</td></tr><tr><td>T</td><td>T</td><td>T</td><td>F</td><td>T</td><td>T</td></tr><tr><td>T</td><td>T</td><td>F</td><td>F</td><td>T</td><td>F</td></tr><tr><td>T</td><td>F</td><td>T</td><td>T</td><td>T</td><td>T</td></tr><tr><td>T</td><td>F</td><td>F</td><td>T</td><td>T</td><td>T</td></tr><tr><td>F</td><td>T</td><td>T</td><td>T</td><td>F</td><td>T</td></tr><tr><td>F</td><td>T</td><td>F</td><td>T</td><td>T</td><td>T</td></tr><tr><td>F</td><td>F</td><td>T</td><td>F</td><td>F</td><td>T</td></tr><tr><td>F</td><td>F</td><td>F</td><td>F</td><td>T</td><td>T</td></tr></table>


There are rows where all three propositions are T. So (p  q) $\wedge ( p \vee \neg r ) \wedge ( \neg p \vee \neg q \vee r )$ is satisfiable. 


(b) Using truth tables determine if the following three compound propositions are consistent. 

$$
p \wedge q, \neg r, \neg (p \implies r)
$$

<table><tr><td>p</td><td>q</td><td>r</td><td>p ∧ q</td><td>¬r</td><td>p ⇒ r</td><td>¬(p ⇒ r)</td></tr><tr><td>T</td><td>T</td><td>T</td><td>T</td><td>F</td><td>T</td><td>F</td></tr><tr><td>T</td><td>T</td><td>F</td><td>T</td><td>T</td><td>F</td><td>T</td></tr><tr><td>T</td><td>F</td><td>T</td><td>F</td><td>F</td><td>T</td><td>F</td></tr><tr><td>T</td><td>F</td><td>F</td><td>F</td><td>T</td><td>F</td><td>T</td></tr><tr><td>F</td><td>T</td><td>T</td><td>F</td><td>F</td><td>T</td><td>F</td></tr><tr><td>F</td><td>T</td><td>F</td><td>T</td><td>T</td><td>T</td><td>F</td></tr><tr><td>F</td><td>F</td><td>T</td><td>F</td><td>F</td><td>T</td><td>F</td></tr><tr><td>F</td><td>F</td><td>F</td><td>F</td><td>T</td><td>T</td><td>F</td></tr></table>

There are rows where all three propositions are T. So $p \wedge q , \neg r , \neg ( p \implies r )$ are consistent. 

Question 2 (10 points). Suppose you are in a game show where you have two boxes in placed in front of you. In each box, there is either a million dollars or it is empty. It is possible that both boxes have the money, both are empty, or one has the money and the other is empty. 

Each box is closed and you can only choose one box to open. However, each box has a message written on top of it and you are guaranteed that the following holds: 

If Box 1 has money, then its message is true; otherwise it is false. 

If Box 2 is empty, then its message is true; otherwise it is false. 

The messages are: 

Box 1: “Both boxes have money or both boxes are empty.” 

Box 2: “The other box has money and this box is empty.” 

Define p, q to be propositions: 

• <sup>p:</sup> <sup>Box</sup> <sup>1</sup> <sup>has</sup> <sup>money.</sup> 

q: Box 2 has money. 

(1) Translate Box 1’s message into a compound proposition involving propositions p,q. 

(2) Translate Box 2’s message into a compound proposition involving propositions p,q. 

(3) Use a truth table to determine what is inside each box. 

(4) Which box would you choose to open? 

## Solution:

(1) Box 1’s message says: $( p \land q ) \lor ( \neg p \land \neg q )$ . This is logically equivalent to $p \Leftrightarrow q$ by the laws for biconditional statements. 

(2) Box 2’s message says: $p \wedge \neg q$ 

(3) Now Box 1 has money if and only if its message is correct. So we have $p \Leftrightarrow ( p \Leftrightarrow q )$ as our first constraints. 

Box 2 is empty ( q) if and only if its message is correct. So we have $\neg q \Leftrightarrow ( p \land \neg q )$ . This is our second constraint. 

We construct a truth table to find the truth values of p and q that satisfy both logical constraints simultaneously. 

<table><tr><td>p</td><td>q</td><td>$ \neg q $</td><td>$ p \Leftrightarrow q $</td><td>$ p \land \neg q $</td><td>$ p \Leftrightarrow (p \Leftrightarrow q) $</td><td>$ \neg q \Leftrightarrow (p \land \neg q) $</td></tr><tr><td>T</td><td>T</td><td>F</td><td>T</td><td>F</td><td>T</td><td>T</td></tr><tr><td>T</td><td>F</td><td>T</td><td>F</td><td>T</td><td>F</td><td>T</td></tr><tr><td>F</td><td>T</td><td>F</td><td>F</td><td>F</td><td>T</td><td>T</td></tr><tr><td>F</td><td>F</td><td>T</td><td>T</td><td>F</td><td>F</td><td>F</td></tr></table>

Conclusion: The truth table has two rows where both final columns are True: Row $1 \ \mathrm { \Omega } ( p { = } T ,$ q=T) and Row 3 $\scriptstyle ( p = F , \ q = T )$ 

In both of these valid scenarios, the proposition q is True. The proposition p can be either True or False. 

Therefore, we can conclude: Box 2 has money. We cannot determine the contents of Box 1. (4) So we will choose Box 2 to be opened. 

Question 3 (10 points). (a) Let $p , q , r$ be propositions. Obtain the negations of the following propositions using logical equivalences and De Morgan’s laws. 

(1) $p \implies ( q \lor r )$ 

(2) $( p \land q ) \implies r$ 

(3) $\neg p \lor ( \neg q \land p )$ 

Solutions: 

(1) 

$$
\begin{array}{c} \neg (p \implies (q \lor r)) \equiv p \land \neg (q \lor r) \\ \equiv p \land \neg q \land \neg r \end{array}
$$

(2) 

$$
\neg ((p \land q) \implies r) \equiv (p \land q) \land \neg r\tag{3}
$$

$$
\begin{array}{c} \neg (\neg p \lor (\neg q \land p)) \equiv \neg (\neg p) \land \neg (\neg q \land p) \\ \equiv p \land (q \lor \neg p) \end{array}
$$

(b) Let $p , q$ be propositions. Use the list of standard logical equivalences to determine whether 

$$
((p \vee q) \wedge (p \implies r) \wedge (q \implies r)) \implies r
$$

is a tautology. Show all the steps and state which law is being used at each step. 

Solution: 

$$
\begin{array}{l l} ((p \lor q) \land (p \implies r) \land (q \implies r)) \equiv (p \lor q) \land ((p \lor q) \implies r) & (\text {Use} (p \implies r) \land (q \implies r) \equiv (p \lor q) \implies r) \\ \equiv (p \lor q) \land (\neg (p \lor q) \lor r) & (\text {Use} p \implies q \equiv \neg p \lor q) \\ \equiv ((p \lor q) \land (\neg (p \lor q)) \lor ((p \lor q) \land r) & (\text {Distributive law}) \\ \equiv F \lor ((p \lor q) \land r) & (\text {Negation law}) \\ \equiv (p \lor q) \land r & (\text {Identity law}) \end{array}
$$

Now 

$$
\begin{array}{r l} ((p \lor q) \land r) \implies r & \equiv \neg ((p \lor q) \land r) \lor r \\ & \equiv \neg (p \lor q) \lor \neg r \lor r \\ & \equiv \neg (p \lor q) \lor T \\ & \equiv T \end{array}
$$

Question 4 (10 points). True or False. Explain your answer. 

<sup>(1)</sup> ≃<sup>x</sup> $( x ^ { 2 } + x = 2 x )$ , domain: rational numbers. 

False. $. I f x = 2 , t h e n x ^ { 2 } + x = 6 b u t 2 x = 4 . S o x ^ { 2 } + x = 2 x i s F a l s e .$ 

<sup>(2)</sup> ⇐<sup>x</sup> $( x ^ { 2 } = 2 x - 1 )$ , domain: real numbers. 

True. It is true for $x = 1$ 

(3) $\begin{array} { r } { \forall x \forall y \exists z \ ( z = \frac { x } { y - 1 } ) } \end{array}$ , domain: real numbers. 

False. For $y = 1$ , there is no z because $\frac { x } { y - 1 }$ is not defined. 

<sup>(4)</sup> ≃<sup>x</sup>≃<sup>y</sup> $( x ^ { 2 } \neq y ^ { 3 } + 4 )$ , domain: integers. 

False. $I f x = 2 , y = 1 , t h e n \ x ^ { 2 } = y ^ { 3 } + 4 .$ 

<sup>(5)</sup> ≃<sup>x</sup>⇐<sup>y</sup> $( x ^ { 2 } \neq y ^ { 3 } + 4 )$ , domain: integers. 

True. For all $x ,$ we can take $y = 1$ . Then $x ^ { 2 } \neq 5$ for all integers x. 

Question 5 (10 points). (a) Consider the predicate 

$$
P (x, y): (x - 1) ^ {(y - 1)} \text {is a rational number.}
$$

Suppose the domain of $P$ is all pairs $( x , y )$ , where x, y are both rational numbers. Determine the truth value of the quantified statement: $\forall x \forall y P ( x , y )$ . Explain your answer. 

Solution: The statement is False. 

We disprove the statement by giving a counterexample. Let $x = 3$ and $\begin{array} { r } { y = \frac { 3 } { 2 } } \end{array}$ 

We evaluate $P ( 3 , { \frac { 3 } { 2 } } )$ , which is the assertion $( x - 1 ) ^ { ( y - 1 ) } \in \mathbb { Q } .$ 

$$
(3 - 1) ^ {(\frac {3}{2} - 1)} = 2 ^ {1 / 2} = \sqrt {2}
$$

Since $\sqrt { 2 }$ is irrational, the proposition $P ( 3 , { \frac { 3 } { 2 } } )$ is false. 

We have found x, y rational for which $P ( x , y )$ is false. Therefore, the quantified statement is $f a l s e$ 

(b) Consider the quantified statement 

$$
\exists y \exists x ((x ^ {2} + y ^ {2} = 1) \land \forall z (x + z = z + y)).
$$

Determine its truth value, and express the negation of the statement. Assume that the domain is Z. 

Solution: False. Note that $x + z = y + z$ implies that $x = y .$ . So the predicate is $x ^ { 2 } + y ^ { 2 } = 1$ and $x = y .$ So we have $x ^ { 2 } + y ^ { 2 } = x ^ { 2 } + x ^ { 2 } = 2 x ^ { 2 }$ . Therefore $2 x ^ { 2 } = 1$ , and hence $\begin{array} { r } { x = \pm \frac { 1 } { \sqrt { 2 } } } \end{array}$ . This is not possible because the domain is integers. So there are no integers $x , y$ such that $x ^ { 2 } + y ^ { 2 } = 1$ and $\forall z ( x + z = y + z )$ 

Negation: 

$$
\begin{array}{r l} \neg (\exists y \exists x ((x ^ {2} + y ^ {2} = 1) \land \forall z (x + z = z + y))) & \equiv \forall y \neg (\exists x ((x ^ {2} + y ^ {2} = 1) \land \forall z (x + z = z + y))) \\ & \equiv \forall y \forall x \neg ((x ^ {2} + y ^ {2} = 1) \land \forall z (x + z = z + y))) \\ & \equiv \forall y \forall x ((x ^ {2} + y ^ {2} \neq 1) \lor \neg (\forall z (x + z = z + y))) \\ & \equiv \forall y \forall x ((x ^ {2} + y ^ {2} \neq 1) \lor (\exists z (x + z \neq z + y))) \end{array}
$$

Question 6 (10 points). (a) Let $p , q , r$ be propositions. Using the Disjunctive Normal Form (DNF) method, construct a compound proposition C which has the following truth table. 

<table><tr><td>p</td><td>q</td><td>r</td><td>C</td></tr><tr><td>T</td><td>T</td><td>T</td><td>F</td></tr><tr><td>T</td><td>T</td><td>F</td><td>T</td></tr><tr><td>T</td><td>F</td><td>T</td><td>F</td></tr><tr><td>T</td><td>F</td><td>F</td><td>T</td></tr><tr><td>F</td><td>T</td><td>T</td><td>F</td></tr><tr><td>F</td><td>T</td><td>F</td><td>T</td></tr><tr><td>F</td><td>F</td><td>T</td><td>T</td></tr><tr><td>F</td><td>F</td><td>F</td><td>T</td></tr></table>

## Solution:

DNF rule: In the last column, the entries in row 2, 4, 5, 6, 7 are T. So we have the following miniterms: 

(1) Row 2: $p \land q \land \neg r .$ 

(2) Row 4: $p \wedge \neg q \wedge \neg r .$ 

(3) Row $6 \colon \neg p \land q \land \neg r$ 

(4) Row $7 \colon \neg p \land \neg q \land r$ 

(5) Row $8 \colon \neg p \land \neg q \land \neg r$ 

Compound proposition C $: ( p \wedge q \wedge \neg r ) \vee ( p \wedge \neg q \wedge \neg r ) \vee ( \neg p \wedge q \wedge \neg r ) \vee ( \neg p \wedge \neg q \wedge r ) \vee ( \neg p \wedge \neg q \wedge \neg r )$ 

(b) Design a circuit that computes the compound proposition C. 

Solution: Let us simplify using Boolean algebra. 

C = pqr + pq r + pqr + p qr + p q r = pr(q + q) + p r(q + q) + p qr $= p \overline { { r } } + \overline { { p } } \overline { { r } } + \overline { { p } } \overline { { q } } r$ since $q + \overline { { q } } = 1$ , equivalently in terms of propositional logic $q \vee \neg q \equiv T$ = r(p + p) + p qr 

![image](https://cdn-mineru.openxlab.org.cn/result/2026-10-07/1a600387-ec5b-40ef-8e7b-f795ae6b8780/e89e116eb5c7f1da93bbcfd7cca99b7d43eb14af9c5882e96e07f0976603d846.jpg)


Question 7 (15 points). For each claim below, prove or disprove the claim. To prove a claim, you need to provide a complete proof. To disprove a claim, you need to provide at least one counter example. 

(1) For every non-negative integer $n \geq 0$ , the expression $n ^ { 2 } + n + 1 1$ is prime. 

## Solution:

This claim is false. To see this, note that when $n = 1 1$ , the expression $n ^ { 2 } + n + 1 1$ is equal to $1 1 ^ { 2 } + 1 1 + 1 1 = 1 1 ( 1 1 + 1 + 1 ) = 1 1 \times 1 3$ , which is not prime. 

(2) If the product of integers m and n is odd, then both m and n must be odd. 

Solution: 

We will prove the contrapositive of the given statement, which amounts to showing that if at least one of m and n is even, then the product of m and n is also even. Without loss of generality, let m be even. Then there exists $k \in  { \mathbb { Z } }$ such that $m = 2 k$ . Then we have, $m n = 2 k n = 2 k ^ { \prime }$ , where $k ^ { \prime } = k n \in \mathbb { Z }$ , which means mn is even. 

(3) ${ \sqrt { 2 } } + { \sqrt { 4 } }$ is irrational. (You can use that $\sqrt { 2 }$ is irrational). 

## Solution:

Assume for the sake of contradiction that ${ \sqrt { 2 } } + { \sqrt { 4 } }$ is rational. 

Then there exist m $\textstyle \gamma , q \in \mathbb { Z } , q \neq 0$ such that $\textstyle { \sqrt { 2 } } + { \sqrt { 4 } } = { \frac { m } { q } }$ 

Then $\textstyle { \sqrt { 2 } } = { \frac { m } { q } } - { \sqrt { 4 } } = { \frac { m } { q } } - 2 = { \frac { m - 2 q } { q } } = { \frac { p } { q } }$ , where $p = m - 2 q$ 

Note that since m and q are integers, it follows that p is also an integer. 

Therefore we get that ${ \sqrt { 2 } } = { \frac { p } { q } } .$ , where $p , q$ are integers and $q \neq 0$ . This is a contradiction as we know that $\sqrt { 2 }$ is irrational. 

Question 8. (5 points) Suppose C is a circuit with input variables p, q, r, and the circuit uses only AND, OR gates (it does not use NOT-gates). 

(a) What is the output of an AND gate when one of its inputs is 0? 

Solution: If one of the inputs is 0, output of AND is 0. 

(b) What is the output of an OR gate when one of its inputs is 1? 

Solution: If one of the inputs is 1, output of OR is 1. 

(c) Suppose that for p = 0 and for some input values of q, r, the output of the circuit C is 1. Prove that if we change the input of p to be p = 1, and keep the q, r values unchanged, the output of the circuit C is still 1. 

Solution: 

Let us think what happens to the outputs of AND/OR gates inside the circuit C, when we change p = 0 to p = 1 and keep q, r same. 

AND gates: Consider any AND gate where p was an input. Since p = 0 initially, the output of this AND gate must have been 0, no matter what the contribution form q, r is. 

Now if p is changed to 1, the output can become 1, if the contribution from q, r was already 1. Otherwise, if the contribution from q, r was 0, then the output of AND gate does not change and remains 0. 

So the output of AND gates remains the same 0 or increases to 1. 

OR gates: Consider any OR gate where p was an input. The output of the OR gate will become 1, when p is changed to 1. So the outputs of OR gates will increase to 1, when p is changed to 1. 

For any further AND/OR gates, one of these two will happen: 

1. Its inputs increased from 0 to 1. 

2. Its input was 1 and stayed as 1. 

So the final output of the circuit can only increase from 0 to 1 or it can stay the same as 1. 

So there is no way the final output can decrease from 1 to 0. 

(d) Can the circuit C compute the NOT operation? In other words, can the NOT operation be expressed in terms of AND,OR operations? Explain your answer. 

Solution: No. The circuit C can not compute NOT operation. If C had computed p, then changing p = 0 to p = 1, would have to change the output from 1 to 0. This is a contradiction because of part (c) above. 