1. A graph of $y = h ( x )$ is shown below. State for what values of x in the interval $0 < x < 1 0$ $h ( x )$ is not diferentiable. 

![image](https://cdn-mineru.openxlab.org.cn/result/2026-10-27/1eaeb0ab-7f73-4b78-bbe3-c094feb83019/0f30804e91748618322d008d46c427b6c2cf6d9d1aa49968c5ce0db7f907a60b.jpg)


Solution: Answer: $\begin{array} { r } { \boxed { x = 3 , 4 , 6 , 7 } , } \end{array}$ and 9 

Here’s why: $x = 3 , 4$ , and 7 are corners, and a function is not diferentiable at a corner, since the function has diferent slopes on either side of the corner. $\mathrm { E . g . }$ , the function shown approaches $x = 3$ from the left with a slope of −1 and the right with a slope of 1, so it has no tangent line at $x = 3$ 

h is not continuous at $x = 6$ and $x = 9$ , and a function cannot be diferentiable at $x = a$ if it is discontinuous at $x = a$ . (See Theorem 1 on page 131 of the textbook.) 

If you said h is not diferentiable at $x = 8$ , this is incorrect because it is clear from the graph that the tangent line at $x = 8$ is horizontal, so $h ^ { \prime } ( 8 ) = 0$ and, therefore, $h ^ { \prime } ( 8 )$ exists. 

If you said h is not diferentiable at $x = 0 \ \mathrm { o r } \ x = 1 0$ , these are incorrect because they are outside the interval $( 0 < x < 1 0 )$ that the question asks about. 

2. (a) Find $y ^ { \prime }$ where $y = 3 \sqrt [ 5 ] { x ^ { 2 } } - \frac { 5 } { x ^ { 4 } } + e ^ { \pi } + 1 7 ^ { x } ,$ 

Solution: Rewrite y as $3 x ^ { 2 / 5 } - 5 x ^ { - 4 } + e ^ { \pi } + 1 7 ^ { x }$ . Then 

$$
\begin{array}{c} y ^ {\prime} = \boxed {3 \cdot \frac {2}{5} x ^ {- 3 / 5} - 5 (- 4) x ^ {- 5} + 0 + 1 7 ^ {x} (\ln 1 7)} \\ = \boxed {\frac {6}{5 x ^ {3 / 5}} + \frac {2 0}{x ^ {5}} + 1 7 ^ {x} (\ln 1 7)} \end{array}
$$

Note: If you thought the derivative of $e ^ { \pi }$ is $e ^ { \pi }$ , you’re not alone, but $e ^ { \pi }$ is a constant, so its derivative is zero. 

(b) Find $\textstyle { \frac { d y } { d x } }$ where $y = x ^ { 2 } e ^ { x }$ arctan(x). 

Solution: Think of $x ^ { 2 } e ^ { x }$ arctan(x) as the product $x ^ { 2 } \cdot ( e ^ { x } \arctan ( x ) )$ , and then apply the product rule. So, 

$$
\begin{array}{l l} \frac {d y}{d x} = x ^ {2} \frac {d}{d x} \left(e ^ {x} \arctan (x)\right) + \left(e ^ {x} \arctan (x)\right) \frac {d}{d x} x ^ {2} & \text {Product rule} \\ = x ^ {2} \left(e ^ {x} \frac {d}{d x} \arctan (x) + \arctan (x) \frac {d}{d x} e ^ {x}\right) & \text {Product rule again, this time on the} \\ + \left(e ^ {x} \arctan (x)\right) \frac {d}{d x} x ^ {2} & e ^ {x} \arctan (x) \text {term} \\ = \boxed {x ^ {2} \left(e ^ {x} \cdot \frac {1}{1 + x ^ {2}} + \arctan (x) e ^ {x}\right) + \left(e ^ {x} \arctan (x)\right) \cdot 2 x} & \text {Evaluate derivatives of} \\ & \arctan (x), e ^ {x}, \text {and} x ^ {2} \end{array}
$$

If you started the problem with the product $( x ^ { 2 } e ^ { x } ) \cdot \arctan ( x )$ , then you likely would have gotten the answer 

$$
\boxed {\frac {x ^ {2} e ^ {x}}{1 + x ^ {2}} + \arctan (x) \left(x ^ {2} e ^ {x} + 2 x e ^ {x}\right)}
$$

which is equivalent to the answer above. 

(c) Find $f ^ { \prime } ( x )$ where $f ( x ) = \sec \left( { \frac { x ^ { 2 } } { 7 + \log _ { 5 } x } } \right)$ 

$$
\begin{array}{r l} & {\mathrm{Solution:}} \\ & {f ^ {\prime} (x) = \sec \left(\frac {x ^ {2}}{7 + \log_ {5} x}\right) \tan \left(\frac {x ^ {2}}{7 + \log_ {5} x}\right) \frac {d}{d x} \left(\frac {x ^ {2}}{7 + \log_ {5} x}\right) \qquad \begin{array}{l} {\mathrm{By} \quad \mathrm{the} \quad \mathrm{chain}} \\ {\mathrm{rule,} \quad \frac {d}{d x} \sec u \quad =} \\ {\sec u \tan u \frac {d u}{d x}} \end{array} } \\ & {\qquad = \sec \left(\frac {x ^ {2}}{7 + \log_ {5} x}\right) \tan \left(\frac {x ^ {2}}{7 + \log_ {5} x}\right) \left(\frac {(7 + \log_ {5} x) \frac {d}{d x} x ^ {2} - x ^ {2} \frac {d}{d x} (7 + \log_ {5} x)}{(7 + \log_ {5} x) ^ {2}}\right)} \\ & {\qquad \qquad \qquad \qquad \qquad \qquad \qquad \qquad \mathrm{Quotientrule}} \\ & {\qquad = \boxed {\sec \left(\frac {x ^ {2}}{7 + \log_ {5} x}\right) \tan \left(\frac {x ^ {2}}{7 + \log_ {5} x}\right) \left(\frac {(7 + \log_ {5} x) \cdot 2 x - \frac {x ^ {2}}{x (\ln 5)}}{(7 + \log_ {5} x) ^ {2}}\right)}} \\ & {\qquad \qquad \qquad \qquad \qquad \qquad \qquad \qquad \qquad \qquad \qquad \mathrm{Evaluatederivatives.}} \\ & {\qquad \qquad \qquad \qquad \qquad \qquad \mathrm{Derivativeof7is0,andderivativeoflog} _ {5} x \mathrm{is} \frac {1}{x (\ln 5)}.} \end{array}
$$

## (d) Find ${ \frac { d } { d x } } \left( 8 ^ { x ^ { 2 } + 1 } + \ln ( x ^ { 2 } + 1 ) \right)$

Solution: 

$$
\begin{array}{l} \text {ution:} \\ \frac {d}{d x} \left(8 ^ {x ^ {2} + 1} + \ln (x ^ {2} + 1)\right) = 8 ^ {x ^ {2} + 1} (\ln 8) \cdot \frac {d}{d x} (x ^ {2} + 1) + \frac {1}{x ^ {2} + 1} \cdot \frac {d}{d x} (x ^ {2} + 1) \\ \qquad \qquad \qquad \qquad \qquad \qquad \qquad \qquad \qquad \qquad \qquad \qquad \qquad \qquad \qquad \qquad \qquad \qquad \text {By the chain rule,} \\ \text {derivative of $8^u$ is} \\ \text {derivative of $\ln u$ is} \\ \frac {1}{u} \cdot \frac {d u}{d x}. \\ = \boxed {8 ^ {x ^ {2} + 1} (\ln 8) \cdot 2 x + \frac {2 x}{x ^ {2} + 1}} \\ \qquad \qquad \qquad \qquad \qquad \qquad \qquad \qquad \text {Differentiate $x^2 + 1$} \end{array}
$$

(e) Find ${ \frac { d } { d w } } \cos ^ { 5 } ( \sin w ) .$ 

Solution: This is a composite function, and it’s easier to see what is wrapped inside of what if we rewrite $\cos ^ { 5 } ( \sin w )$ as $( \cos ( \sin w ) ) ^ { 5 }$ . So this is sine, wrapped inside a cosine, wrapped inside a fifth power. Using the chain rule, we start from 

the outside and work toward the inside: 

$$
\begin{array}{r l r} \frac {d}{d w} \left(\cos (\sin w)\right) ^ {5} & = 5 \left(\cos (\sin w)\right) ^ {4} \frac {d}{d w} \left(\cos (\sin w)\right) & \text {Derivative of u^{5} is 5u^{4}} \\ & = 5 \left(\cos (\sin w)\right) ^ {4} \left(- \sin (\sin w)\right) \frac {d}{d w} \sin w & \text {times the derivative of u} \\ & = \boxed {5 \left(\cos (\sin w)\right) ^ {4} \left(- \sin (\sin w)\right) \cos w} & \text {Derivative of cos u} \\ & = \boxed {- 5 \cos^ {4} (\sin w) \sin (\sin w) \cos w} & \text {is - sin u times the derivative of u} \\ & & \text {Derivative of sin w is cos w}. \\ & & \text {There are several different ways to write the correct answer.} \\ & & \text {The answers in the boxes are two of the most popular ways.} \end{array}
$$

$$
\mathrm{(f)} y = \tan^ {1 0} \left(\cos^ {4} x ^ {2}\right)
$$

Solution: The dificulty in this problem is understanding what functions are inside what other functions. It helps to rewrite the nesting of functions in a more explicit form: 10 

$$
\tan^ {1 0} \left(\cos^ {4} x ^ {2}\right) = \left[ \tan \left(\left[ \cos (x ^ {2}) \right] ^ {4}\right) \right] ^ {1 0}
$$

Now, apply the chain rule repeatedly, working layer by layer from the outside toward the inside: 

$$
\begin{array}{r l} & {\frac {d}{d x} \left[ \tan \left(\left[ \cos (x ^ {2}) \right] ^ {4}\right) \right] ^ {1 0}} \\ & {= 1 0 \left[ \tan \left(\left[ \cos (x ^ {2}) \right] ^ {4}\right) \right] ^ {9} \cdot \frac {d}{d x} \tan \left(\left[ \cos (x ^ {2}) \right] ^ {4}\right)} \\ & {= 1 0 \left[ \tan \left(\left[ \cos (x ^ {2}) \right] ^ {4}\right) \right] ^ {9} \cdot \sec^ {2} \left(\left[ \cos (x ^ {2}) \right] ^ {4}\right) \cdot \frac {d}{d x} \left[ \cos (x ^ {2}) \right] ^ {4}} \\ & {= 1 0 \left[ \tan \left(\left[ \cos (x ^ {2}) \right] ^ {4}\right) \right] ^ {9} \cdot \sec^ {2} \left(\left[ \cos (x ^ {2}) \right] ^ {4}\right) \cdot 4 \left[ \cos (x ^ {2}) \right] ^ {3} \cdot \frac {d}{d x} \cos (x ^ {2})} \\ & {= 1 0 \left[ \tan \left(\left[ \cos (x ^ {2}) \right] ^ {4}\right) \right] ^ {9} \cdot \sec^ {2} \left(\left[ \cos (x ^ {2}) \right] ^ {4}\right) \cdot 4 \left[ \cos (x ^ {2}) \right] ^ {3} \cdot (- \sin (x ^ {2})) \cdot \frac {d}{d x} x ^ {2}} \\ & {= 1 0 \left[ \tan \left(\left[ \cos (x ^ {2}) \right] ^ {4}\right) \right] ^ {9} \cdot \sec^ {2} \left(\left[ \cos (x ^ {2}) \right] ^ {4}\right) \cdot 4 \left[ \cos (x ^ {2}) \right] ^ {3} \cdot (- \sin (\boldsymbol x ^ {2})) \cdot 2 x} \\ & {= - 8 0 x \cdot \tan^ {9} (\cos^ {4} x ^ {2}) \cdot \sec^ {2} (\cos^ {4} x ^ {2}) \cdot \cos^ {3} x ^ {2} \cdot \sin x ^ {2}} \\ & = [ - 8 0 x ] [ - 8 0 x ] [ - 8 0 x ] [ - 8 0 x ] [ - 8 0 x ] [ - 8 0 x ] [ - 8 0 x ] [ - 8 0 x ] [ - 8 0 x ] [ - 8 0 x ] [ - 8 0 x ] [ - 8 0 x ] [ - 8 0 x ] [ - 6 0 x ] [ - 6 0 x ] [ - 6 0 x ] [ - 6 0 x ] [ - 6 0 x ] [ - 6 0 x ] [ - 6 0 x ] [ - 6 0 x ] [ - 6 0 x ] [ - 6 0 x ] [ - 6 0 x ] [ - 6 0 x ] [ - 6 0 x ]. \end{array}
$$

## (g) Find $f ^ { \prime } ( x ) { \mathrm { ~ i f ~ } } f ( x ) = { \sqrt { 1 + { \sqrt { 1 + { \sqrt { x } } } } } }$

Solution: Computing the derivative requires multiple applications of the chain rule. Working from the outside inward, the first composition is 

$$
y = \sqrt {u} \quad \text { with } \quad u = 1 + \sqrt {1 + \sqrt {x}}.
$$

A first application of the chain rule gives 

$$
f ^ {\prime} (x) = \frac {1}{2 \sqrt {1 + \sqrt {1 + \sqrt {x}}}} \cdot \frac {d}{d x} \left[ 1 + \sqrt {1 + \sqrt {x}} \right]
$$

The next composition is 

$$
y = 1 + \sqrt {u} \qquad \text { and } \qquad u = 1 + \sqrt {x}
$$

so another application of chain rule gives 

$$
\begin{array}{r c l} f ^ {\prime} (x) & = & \frac {1}{2 \sqrt {1 + \sqrt {1 + \sqrt {x}}}} \cdot \frac {1}{2 \sqrt {1 + \sqrt {x}}} \cdot \frac {d}{d x} \left[ 1 + \sqrt {x} \right] \\ & = & \frac {1}{2 \sqrt {1 + \sqrt {1 + \sqrt {x}}}} \cdot \frac {1}{2 \sqrt {1 + \sqrt {x}}} \cdot \frac {1}{2 \sqrt {x}} \\ & = & \frac {1}{8 \sqrt {1 + \sqrt {1 + \sqrt {x}}} \cdot \sqrt {1 + \sqrt {x}} \cdot \sqrt {x}}. \end{array}
$$

3. Compute the derivative. 

(a) $y = \sec ( t e ^ { 3 t } )$ 

Solution: We first use the chain rule. The outer composition is 

$$
y = \sec u \qquad \mathrm{and} \qquad u = t e ^ {3 t}.
$$

Thus we get 

$$
\begin{array}{r} \frac {d y}{d t} = \sec (t e ^ {3 t}) \tan (t e ^ {3 t}) \frac {d}{d t} (t e ^ {3 t}) \\ = \sec (t e ^ {3 t}) \tan (t e ^ {3 t}) (e ^ {3 t} + t (3 e ^ {3 t})) \end{array}
$$

## (b) $y = \csc ( 3 \log _ { 2 } ( 2 - x ) )$

Solution: The derivative requires application of the chain rule. For the outermost function, the composition is 

$$
y = \csc u \qquad \mathrm{and} \qquad u = 3 \log_ {2} (2 - x).
$$

Then 

$$
\frac {d y}{d x} = - \csc (3 \log_ {2} (2 - x)) \cot (3 \log_ {2} (2 - x)) \frac {d}{d x} (3 \log_ {2} (2 - x))
$$

The next composition is 

$$
y = \log_ {2} (u) \qquad \mathrm{and} \qquad u = 2 - x.
$$

Applying the chain rule again, 

$$
\begin{array}{r c l} \frac {d y}{d x} & = & - \csc (3 \log_ {2} (2 - x)) \cot (3 \log_ {2} (2 - x)) \cdot 3 \left(\frac {1}{\ln 2} \cdot \frac {1}{2 - x} \cdot (- 1)\right) \\ & = & \frac {3 \csc (3 \log_ {2} (2 - x)) \cot (3 \log_ {2} (2 - x))}{(2 - x) \ln 2}. \end{array}
$$

$$
\mathrm{(c)} y = x \tan^ {- 1} (\sqrt {x})
$$

## Solution:

The product rule gives 

$$
y ^ {\prime} = 1 \cdot \tan^ {- 1} (\sqrt {x}) + x \cdot \frac {d}{d x} \left(\tan^ {- 1} (\sqrt {x})\right). =
$$

To diferentiate tan<sup>−</sup> $^ { - 1 } ( { \sqrt { x } } )$ , we use the chain rule with the composition 

$$
y = \tan^ {- 1} u \qquad \mathrm{and} \qquad u = \sqrt {x}.
$$

Thus, 

$$
\begin{array}{c} {y ^ {\prime} = \tan^ {- 1} (\sqrt {x}) + x \cdot \frac {1}{1 + (\sqrt {x}) ^ {2}} \cdot \frac {1}{2} x ^ {- 1 / 2}} \\ {= \tan^ {- 1} (\sqrt {x}) + \frac {\sqrt {x}}{2 (1 + x)}.} \end{array}
$$

(d) $y = 5 ^ { \mathrm { a r c s i n ( 2 } x ) }$ 

Solution: Observe that the function in the question is a composite function with $y = 5 ^ { u }$ and $u = \arcsin ( 2 x )$ , and that the derivative of $b ^ { u }$ is $b ^ { u } ( \ln \boldsymbol { b } )$ . Then work from the outside in: 

$$
\begin{array}{r l} & {\frac {d}{d x} 5 ^ {\arcsin (2 x)} = 5 ^ {\arcsin (2 x)} (\ln 5) \cdot \frac {d}{d x} \arcsin (2 x)} \\ & {\qquad = 5 ^ {\arcsin (2 x)} (\ln 5) \cdot \frac {1}{\sqrt {1 - (2 x) ^ {2}}} \cdot \frac {d}{d x} (2 x)} \\ & {\qquad = 5 ^ {\arcsin (2 x)} (\ln 5) \cdot \frac {1}{\sqrt {1 - (2 x) ^ {2}}} \cdot 2} \\ & {\qquad = \boxed {\frac {(2 \ln 5) \cdot 5 ^ {\arcsin (2 x)}}{\sqrt {1 - 4 x ^ {2}}}}} \end{array}
$$

4. Find $f ^ { \prime \prime } ( \pi / 4 )$ where $f ( x ) = \cot ^ { 3 } x .$ 

Solution: 

$$
\begin{array}{r l r} f ^ {\prime} (x) = 3 \cot^ {2} x \cdot \frac {d}{d x} (\cot x) & \text {Chain rule} \\ = 3 \cot^ {2} x \cdot (- \csc^ {2} x) & \text {Derivative of} \cot x \\ = - 3 \cot^ {2} x \csc^ {2} x & \text {Combine terms} \\ f ^ {\prime \prime} (x) = - 3 (\cot^ {2} x \frac {d}{d x} (\csc^ {2} x) + \csc^ {2} x \frac {d}{d x} (\cot^ {2} x)) & \text {Use product rule on} \\ = - 3 (\cot^ {2} x (2 \csc x (- \csc x \cot x) + \csc^ {2} x (2 \cot x (- \csc^ {2} x))) & \text {Evaluate derivatives using the chain rule} \\ = - 3 (- 2 \cot^ {3} x \csc^ {2} x - 2 \cot x \csc^ {4} x) & \text {Combine factors} \\ = 6 \cot x \csc^ {2} x (\cot^ {2} x + \csc^ {2} x) & \text {Factor} \\ f ^ {\prime \prime} (\pi / 4) = 6 (1) (\sqrt {2}) ^ {2} (1 ^ {2} + (\sqrt {2}) ^ {2}) & \text {Substitute actual values of} \cot (\pi / 4) \text {and} \\ = 6 \cdot 2 (1 + 2) = 1 2 \cdot 3 = \boxed {3 6} & \text {csc(\pi / 4). If you don't remember them, you could figure them out from} \\ & \cos (\pi / 4). \\ & \end{array}
$$

5. Find an equation of the line tangent to the graph of $y = { \frac { \sin t } { 1 + \cos t } }$ when $t = \frac { \pi } { 3 }$ 

Solution: We begin by finding $\frac { d y } { d t } ;$ : 

$$
{\frac {d y}{d t}} = {\frac {\cos t (1 + \cos t) - \sin t (- \sin t)}{(1 + \cos t) ^ {2}}} = {\frac {\cos t + 1}{(1 + \cos t) ^ {2}}} = {\frac {1}{1 + \cos t}}.
$$

The slope of the tangent line is $\left. { \frac { d y } { d t } } \right| _ { t = \pi / 3 } = { \frac { 1 } { 1 + 1 / 2 } } = { \frac { 2 } { 3 } }$ and the point on the line is $( \pi / 3 , y ( \pi / 3 ) ) = ( \pi / 3 , \sqrt { 3 } / 3 )$ . Hence the tangent line has equation 

$$
y - \frac {\sqrt {3}}{3} = \frac {2}{3} \left(x - \frac {\pi}{3}\right).
$$

6. Compute the derivative of h(sin x) at $x = \frac { \pi } { 6 }$ , assuming that $h ^ { \prime } ( 0 . 5 ) = 1 0$ 

Solution: Let $g ( x ) = h ( \sin x )$ . Then we see we are asked to compute $g ^ { \prime } ( \pi / 6 )$ . Now g is a composition, so the chain rule tells us that 

$$
g ^ {\prime} (x) = h ^ {\prime} (\sin x) \cdot \cos x.
$$

Hence 

$$
g ^ {\prime} (\pi / 6) = h ^ {\prime} (\sin (\pi / 6)) \cdot \cos (\pi / 6) = h ^ {\prime} (0. 5) \cdot \frac {\sqrt {3}}{2} = 1 0 \cdot \frac {\sqrt {3}}{2} = 5 \sqrt {3}.
$$

7. Let $f ( x )$ and $g ( x )$ be functions so that $f ^ { \prime } ( - 4 ) = g ^ { \prime } ( - 4 )$ and the line tangent to $f ( x )$ at $x = - 4$ is $y = 3 x + 9$ . Compute the following values, if possible. 

(a) f(−4) 

Solution: The tangent line to the graph of f at $x \ = \ - 4$ contains the point $( - 4 , f ( - 4 ) )$ . Since the tangent line at $x = - 4$ has equation $y = 3 x + 9$ , we see that $f ( - 4 ) = 3 ( - 4 ) + 9 = - 3$ 

(b) f<sup>′</sup>(−4) 

Solution: We know that $f ^ { \prime } ( - 4 )$ is the slope of the tangent line to the graph of f at x = −4. Hence $f ^ { \prime } ( - 4 ) = 3$ 

(c) g(−4) 

Solution: This is a value that we cannot determine. 

(d) g<sup>′</sup>(−4) 

Solution: Since $f ^ { \prime } ( - 4 ) = g ^ { \prime } ( - 4 )$ and $f ^ { \prime } ( - 4 ) = 3 { \mathrm { . } }$ we must have $g ^ { \prime } ( - 4 ) = 3 .$ 

8. Each of the limits below can be interpreted as a derivative $f ^ { \prime } ( a )$ . For each limit, determine $f ( x )$ and a, and then use the rules of diferentiation to compute the limit by finding $f ^ { \prime } ( a )$ 

(a) $\operatorname* { l i m } _ { x \to 2 } { \frac { x ^ { 2 0 2 6 } - 2 ^ { 2 0 2 6 } } { x - 2 } }$ 

Solution: Notice that 

$$
f ^ {\prime} (2) = \lim _ {x \to 2} \frac {x ^ {2 0 2 6} - 2 ^ {2 0 2 6}}{x - 2} \mathrm{for} f (x) = x ^ {2 0 2 6}.
$$

Thus $f ( x ) = x ^ { 2 0 2 6 }$ and $a = 2$ . The power rule tells us that $f ^ { \prime } ( x ) = 2 0 2 6 x ^ { 2 0 2 5 }$ Hence 

$$
\lim _ {x \to 2} \frac {x ^ {2 0 2 6} - 2 ^ {2 0 2 6}}{x - 2} = f ^ {\prime} (2) = 2 0 2 6 \cdot 2 ^ {2 0 2 5}.
$$

(b) $\operatorname* { l i m } _ { h \to 0 } { \frac { \ln ( 1 5 + h ) - \ln ( 1 5 ) } { h } }$ 

Solution: This time we have 

$$
f ^ {\prime} (1 5) = \lim _ {h \to 0} \frac {\ln (1 5 + h) - \ln (1 5)}{h} \mathrm{when} f (x) = \ln x \mathrm{and} a = 1 5.
$$

Now $f ^ { \prime } ( x ) = { \frac { 1 } { x } } ,$ so 

$$
\lim _ {h \to 0} \frac {\ln (1 5 + h) - \ln (1 5)}{h} = f ^ {\prime} (1 5) = \frac {1}{1 5}.
$$

9. Suppose that $f ( x ) = { \left\{ \begin{array} { l l } { 6 x ^ { 2 } + 7 , } & { \qquad { \mathrm { i f ~ } } x \leq - 2 } \\ { a x + b , } & { \qquad { \mathrm { i f ~ } } x > - 2 } \end{array} \right. }$ , where a and b are some constants. Use f(x) in parts (a)-(d). 

(a) Compute $\operatorname* { l i m } _ { x \to - 2 ^ { - } } f ( x )$ 

Solution: We see 

$$
\lim _ {x \to - 2 ^ {-}} f (x) = \lim _ {x \to - 2 ^ {-}} 6 x ^ {2} + 7 = 6 (- 2) ^ {2} + 7 = 3 1.
$$

(b) Compute $\operatorname* { l i m } _ { x \to - 2 ^ { + } } f ( x )$ 

Solution: Next we have 

$$
\lim _ {x \to - 2 ^ {+}} f (x) = \lim _ {x \to - 2 ^ {+}} a x + b = a (- 2) ^ {2} + b = - 2 a + b.
$$

(c) If $f ( x )$ is to be continuous at $x = - 2 .$ , what equation involving a and b must be true? 

Solution: For f to be continuous at $x = - 2 .$ , we must have 

$$
\lim _ {x \to - 2} f (x) = f (- 2).
$$

Hence we must have 

$$
3 1 = - 2 a + b.
$$

(d) Assuming f is continuous at $x = - 2$ , find values for a and b that make f diferentiable at $x = - 2$ 

Solution: With the continuity assumption at $x = - 2$ , the derivative at $x = - 2$ will exist provided $\operatorname* { l i m } _ { x \to - 2 ^ { - } } f ^ { \prime } ( x ) = \operatorname* { l i m } _ { x \to - 2 ^ { + } } f ^ { \prime } ( x )$ . We therefore have 

$$
\lim _ {x \to - 2 ^ {-}} f ^ {\prime} (x) = \lim _ {x \to - 2 ^ {+}} f ^ {\prime} (x)
$$

$$
\lim _ {x \to - 2 ^ {-}} (1 2 x) = \lim _ {x \to - 2 ^ {+}} a
$$

$$
- 2 4 = a.
$$

Once we see that $a = - 2 4 .$ , we can solve for b from the continuity condition we found in part $( \mathrm { c } ) \colon - 2 ( - 2 4 ) + b = 3 1 \Rightarrow b = - 1 7 .$ We may conclude that $f$ is diferentiable at $x = - 2$ for $a = - 2 4$ and $b = - 1 7 .$ 

10. Consider the curves $f ( x ) = a x ^ { 2 } - 9 x + b$ and $g ( x ) = x ^ { 2 } + a x + 1$ . Find constants a and b so that the same line is tangent to both curves at $x = 3$ 

Solution: In order for two curves to have the same tangent line at $x = 3 .$ , two things have to be true: 

1. The curves must intersect at $x = 3$ 

2. The curves must have the same slope at $x = 3$ 

The first condition means the functions are equal at $x = 3 { : }$ 

$$
f (3) = g (3)
$$

$$
9 a - 2 7 + b = 9 + 3 a + 1
$$

$$
6 a + b = 3 7
$$

The second condition means the derivatives are equal. Since $f ^ { \prime } ( x ) \ = \ 2 a x \ - 9$ and $g ^ { \prime } ( x ) = 2 x + a ,$ this means: 

$$
f ^ {\prime} (3) = g ^ {\prime} (3)
$$

$$
6 a - 9 = 6 + a
$$

$$
5 a = 1 5
$$

$$
a = 3
$$

This gives us a system of equations in (a and b) (two equations and two unknowns): 

$$
6 a + b = 3 7\tag{1}
$$

$$
a = 3\tag{2}
$$

To solve the system substitute one equation into the other. In this case, substitute $a = 3$ into equation (1), yielding $1 8 + b = 3 7$ , or $b = 1 9$ 

Answer: $\boxed { a = 3 \mathrm { ~ a n d ~ } b = 1 9 }$ 

11. Find a number a so that the tangent lines to $y = x ^ { 3 } + 1 1 x ^ { 2 } + x + 7$ at $x = a$ and at $x = a + 1$ are parallel. 

Solution: The requirement that the tangent lines at $x = a$ and at $x = a + 1$ are parallel means $y ^ { \prime } ( a ) = y ^ { \prime } ( a + 1 )$ . Notice that $y ^ { \prime } ( x ) = 3 x ^ { 2 } + 2 2 x + 1$ . Therefore solving the equation $y ^ { \prime } ( a ) = y ^ { \prime } ( a + 1 )$ for a, we find 

$$
\begin{array}{r l r} & 3 a ^ {2} + 2 2 a + 1 & = 3 (a + 1) ^ {2} + 2 2 (a + 1) + 1 \\ \Rightarrow \quad & 3 a ^ {2} + 2 2 a + 1 & = 3 (a ^ {2} + 2 a + 1) + 2 2 a + 2 2 + 1 \\ & \Rightarrow \quad 0 & = 6 a + 2 5 \\ & \Rightarrow \quad a & = - \frac {2 5}{6} \end{array}
$$

The desired number is $a = - { \frac { 2 5 } { 6 } } .$ 

12. Find constants $a , b ,$ and c so that the graph of the parabola $y = a x ^ { 2 } + b x + c$ passes through the point (0, 2) and has a tangent line with a slope of $3 / 2$ at the point (3, 8). 

Solution: First, observe that $y ^ { \prime } = 2 a x + b . $ Then, note that there are three separate conditions given in the problem statement, which translate to three equations. These conditions are: 

(1) The point (0, 2) is on the parabola, which means $y = 2$ when $x = 0$ . Therefore, $a \cdot 0 ^ { 2 } + b \cdot 0 + c = 2 .$ or, more simply $c = 2 .$ 

(2) The point (3, 8) is on the parabola, which means $y = 8$ when $x = 3$ . Therefore, $a \cdot 3 ^ { 2 } + b \cdot 3 + c = 8 , { \mathrm { o r ~ } } 9 a + 3 b + c = 8 .$ 

(3) $y ^ { \prime } = 3 / 2 { \mathrm { ~ w h e n ~ } } x = 3 , { \mathrm { ~ o r ~ } } 2 a \cdot 3 + b = 3 / 2 , { \mathrm { ~ o r ~ } } 6 a + b = 3 / 2 .$ 

Since $c = 2 .$ , substitute this fact into the second equation, which means the last two equations are: 

$$
\begin{array}{r c l r c l} 9 a & + & 3 b & = & 6 \\ 6 a & + & b & = & 3 / 2 \end{array}
$$

This leaves two equations and two unknowns. The second of the two equations written above implies $b = { \frac { 3 } { 2 } } - 6 a$ , so we substitute this expression for $b$ into the first equation, resulting in: 

$$
\begin{array}{c} {9 a + 3 (\frac {3}{2} - 6 a) = 6} \\ {9 a + \frac {9}{2} - 1 8 a = 6} \\ {- 9 a = \frac {3}{2}} \\ {a = \frac {3}{2 \cdot - 9} = - \frac {1}{6}} \end{array}
$$

Therefore, $\begin{array} { r } { b = \frac { 3 } { 2 } - 6 a = \frac { 3 } { 2 } - 6 ( - \frac { 1 } { 6 } ) = \frac { 3 } { 2 } + 1 = \frac { 5 } { 2 } . } \end{array}$ 

The answer is: $\begin{array} { r } { \boxed { a = - \frac { 1 } { 6 } } , \boxed { b = \frac { 5 } { 2 } } , \boxed { c = 2 } . } \end{array}$ 

13. Find constants a, b, and c so that the graph of the curve $y = a x ^ { 3 } + b x ^ { 2 } + c$ passes through the point $( 0 , - 2 )$ and has a tangent line with a slope of 2 at the point (2, 8). 

Solution: First, observe that $y' = 3ax^{2} + 2bx$ . Then, note that there are three separate conditions given in the problem statement, which translate to three equations. These conditions are:

(1) The point $(0, -2)$ is on the curve, which means y = -2 when x = 0. Therefore, $a \cdot 0^{2} + b \cdot 0 + c = -2$ , or, more simply c = -2.

(2) The point $(2, 8)$ is on the curve, which means y = 8 when x = 2. Therefore, $a \cdot 2^{3} + b \cdot 2^{2} + c = 8$ , or $8a + 4b + c = 8$ .

(3) $y' = 2$ when x = 2, or $3a \cdot 2^{2} + 2b \cdot 2 = 2$ , or $12a + 4b = 2$ .

Since c = -2, substitute this fact into the second equation, which means the last two equations are: $8a + 4b = 10$ $12a + 4b = 2$ This leaves two equations and two unknowns. The first of the two equations can be rearranged as 4b = 10 - 8a, so we substitute this expression for 4b into the second equation, resulting in: $12a + (10 - 8a) = 2$ $4a + 10 = 2$ $4a = -8$ $a = \frac{-8}{4} = -2$ Therefore, $4b = 10 - 8a = 10 - 8(-2) = 10 + 16 = 26$ , so $b = \frac{26}{4} = \frac{13}{2}$ .

The answer is: $a = -2$ , $b = \frac{13}{2}$ , c = -2. 

14. The figure below shows the total distance s traveled by a bicyclist after t hours. 

![image](https://cdn-mineru.openxlab.org.cn/result/2026-10-27/1eaeb0ab-7f73-4b78-bbe3-c094feb83019/95047a00659c0b6ad0c8e39b306d85d2fab16bc4718c97d45145fa511e9b862f.jpg)


Using the graph, answer parts (a) through (c). 

(a) Estimate the bicyclist’s average speed, in mph, over the time intervals [0, 1], [1, 2.5], and [2.5, 3.5]. 

Solution: Over the time interval [0, 1] the average speed is 

$$
\mathrm{avgspeed} = \frac {8 - 0}{1 - 0} = 8 \mathrm{mph},
$$

the average speed over the time interval [1, 2.5] is 

$$
\mathrm{avgspeed} = \frac {1 6 - 8}{2 . 5 - 1} = \frac {8}{(3 / 2)} = \frac {1 6}{3} \mathrm{mph},
$$

and the average speed over the time interval [2.5, 3.5] is 

$$
\mathrm{avgspeed} = \frac {2 0 - 1 6}{3 . 5 - 2 . 5} = 4 \mathrm{mph}.
$$

(b) Estimate the bicyclist’s instantaneous speed, in mph, at $t = \frac 1 2$ hr, $t = 2$ hr, and at $t = 3$ hr. 

Solution: The slope of the line tangent to the graph at $t = \frac 1 2$ appears to have slope $^ { 8 , }$ so we estimate the instantaneous speed to be 8 mph at $t = { \frac { 1 } { 2 } } .$ . The tangent line to the curve at $t = 2$ is horizontal which indicates that the instantaneous speed at $t = 2$ is 0 mph. Lastly, the tangent line to the curve at $t = 3$ looks like its slope is roughly 4, so we estimate the instantaneous speed at $t = 3$ to be 4 mph. 

(c) Estimate the bicyclist’s maximum speed and the specific time at which it occurs. 

Solution: The slope of the curve seems to be steepest at $t = 1$ . Here we estimate the slope of the line to be 16, which tells us the maximum speed is roughly 16 mph. 

15. The figure below shows the velocity $v = f ( t )$ of a particle moving on a horizontal coordinate line for the time interval $0 \leq t \leq 1 2$ seconds. In the coordinate line in which the particle moves, the positive direction is to the right. Distance is measured in meters. 

![image](https://cdn-mineru.openxlab.org.cn/result/2026-10-27/1eaeb0ab-7f73-4b78-bbe3-c094feb83019/c1fec17c9a83d611dddf39fff7dbbda0a63f21e2f59b305b2d20e411783c8868.jpg)


(a) When is the particle moving to the right? 

Solution: Since “right” is defined as the positive direction (see the problem statement), the particle is moving to the right when the velocity is positive: 

$$
\boxed {0 \leq t <   2 \text {and} 3 <   t <   6}
$$

(b) When is the particle stationary for more than an instant? 

Solution: The particle is stationary when its velocity is zero. This occurs on $2 \leq t \leq 3$ , at $t = 6$ and $t = 1 2$ , but the question is when the particle is stationary for “more than an instant”. $t = 6$ and t = 12 are instants in time, so they are not responsive to the question. The answer is: 

$$
\boxed {2 \leq t \leq 3}
$$

(c) When is the particle moving at its greatest speed? 

Solution: Speed is the absolute value of velocity, so the greatest speed is achieved when $v = - 4$ , which occurs on: 

$$
\boxed {8 \leq t \leq 1 0}
$$

(d) When is the particle’s acceleration negative? 

Solution: Acceleration is the derivative of velocity. The derivative gives the slope of a function, so acceleration is negative when the slope of the graph shown is negative, which occurs on: 

$$
\boxed {0 \leq t <   2 \text { and } 5 <   t <   8}
$$

If you’re wondering about how we treat the endpoints: Technically, v is diferentiable at $t = 0$ because, when a function’s domain is a closed interval $[ a , b ]$ , its derivative at an endpoint is equal to its one-sided derivative. As to the points t = 2, 5, and 8, note that v is not diferentiable at those points (they are corners) so the acceleration (the derivative of velocity) is undefined at those points; this is why they are excluded from the intervals of negative acceleration. 

(e) What is the particle’s exact acceleration at $t = 6 ?$ 

Solution: As noted above, acceleration is the derivative of velocity, so it is the slope of the function shown. At t = 6, the function is a straight line segment with a slope of −2 (choose any two points on the line segment, such as (5, 2) and (6, 0) and use the slope formula). Therefore, the acceleration is −2 . 

(f) What is the particle’s average acceleration on the interval $2 \leq t \leq 5 ?$ 

Solution: Acceleration is the rate of change of velocity. The derivative gives the instantaneous rate of change. The average rate of change of a function f over an interval $[ a , b ]$ is $\frac { f ( b ) - f ( a ) } { b - a }$ . Since the function shown is v(t), the average rate of change over the interval [2, 5] is 

Avg. rate of change of $v = { \frac { v ( 5 ) - v ( 2 ) } { 5 - 2 } }$ 

$$
= \frac {2 - 0}{5 - 2} = \boxed {\frac {2}{3}}
$$

Note that “acceleration” is a synonym for “rate of change in veloci $\mathrm { t y } ^ { \dag }$ . Therefore, “average rate of change of $v ^ { \mathfrak { s } }$ means “average acceleration.” 

16. The function $s = f ( t ) = t ^ { 3 } - \frac { 1 3 } { 2 } t ^ { 2 } + 1 2 t , 0 \leq t \leq 4$ , gives the position of an object moving along the s axis as a function of time t (in sec). Assume the motion is horizontal. Use s in parts $\mathrm { ( a ) \mathrm { - ( g ) } }$ 

(a) Compute v(t) and $a ( t )$ 

Solution: The velocity $v ( t )$ and the acceleration $a ( t )$ are found to be 

$$
v (t) = s ^ {\prime} (t) = 3 t ^ {2} - 1 3 t + 1 2 \mathrm{and} a (t) = v ^ {\prime} (t) = s ^ {\prime \prime} (t) = 6 t - 1 3.
$$

(b) Choose the correct graph of $s = f ( t ) , v ( t )$ , and $a ( t )$ below. The window for each graph is [0, 4] by [−12, 12]. 

Graph A 

Graph B 

Graph C 

![image](https://cdn-mineru.openxlab.org.cn/result/2026-10-27/1eaeb0ab-7f73-4b78-bbe3-c094feb83019/e586a15e48809e728e2e305754c9bfbe9026882a6195607b8b8b88cea7ce612d.jpg)


Graph D 

Solution: Graph B. 

(c) When is the object momentarily at rest? 

Solution: The object is momentarily at rest when $v ( t ) = 0$ . We can factor $v ( t ) =$ $3 t ^ { 2 } - 1 3 t + 1 2 = ( 3 t - 4 ) ( t - 3 )$ so the object is at rest when $\begin{array} { r } { t = \frac { 4 } { 3 } } \end{array}$ and $t = 3 .$ 

(d) When does the object move to the left? When does the object move to the right? 

Solution: The object will move to the left when the velocity is negative and will move to the right when the velocity is positive. From the factored expression $v ( t ) \ = \ ( 3 t - 4 ) ( t - 3 )$ , we conclude that the object is moving to the right on $[ 0 , \frac { 4 } { 3 } ) \cup ( 3 , 4 ]$ . The object is moving left on the interval   <sup>4</sup><sub>3</sub> , 3. 

(e) When does the object change direction? 

Solution: From part (d), the object changes from right to left at $\begin{array} { r } { t = \frac { 4 } { 3 } } \end{array}$ sec and then changes from left to right at t = 3 sec. 

(f) When does the object speed up and slow down? 

Solution: An object is speeding up when its velocity and acceleration are nonzero and have the same sign (and slowing down when the signs are opposite). We calculated v(t) and $a ( t )$ previously in part (a): 

$$
\begin{array}{l} v (t) = 3 t ^ {2} - 1 3 t + 1 2 = (3 t - 4) (t - 3) \\ a (t) = 6 t - 1 3 \end{array}
$$

We see that $v ( t )$ changes sign at $\begin{array} { r } { t = \frac { 4 } { 3 } } \end{array}$ and $t = 3 ,$ , while $a ( t )$ changes sign at $\begin{array} { r } { t = \frac { 1 3 } { 6 } } \end{array}$ Create a sign chart to compare the signs of $v ( t )$ and $a ( t )$ in each interval: 

![image](https://cdn-mineru.openxlab.org.cn/result/2026-10-27/1eaeb0ab-7f73-4b78-bbe3-c094feb83019/5c6c91af8ac4c02bfe38c5b95353afa452ecb294157babad9f995b6d553bdc3f.jpg)


The object is speeding up on $\textstyle { \left( { \frac { 4 } { 3 } } , { \frac { 1 3 } { 6 } } \right) }$ and (3, 4], and slowing down on $[ 0 , \frac { 4 } { 3 } )$ and $\textstyle { \bigl ( } { \frac { 1 3 } { 6 } } , 3 { \bigr ) }$ 

(g) When is the object moving fastest? What is its greatest speed? 

Solution: From part (f), we know the intervals where the object is speeding up and slowing down. The object can only be moving at fastest speed either at (i) the end of an interval where it is speeding up, or (ii) at the start of an interval where it is slowing down. 

That means the candidate times where the object is moving fastest has to be $t = 0$ $\begin{array} { r } { t = \frac { 1 3 } { 6 } } \end{array}$ , and $t = 4$ . Then we compare $| { \boldsymbol v } ( t ) |$ at each time: 

$$
| v (0) | = 1 2
$$

$$
| v (1 3 / 6) | = | (3 \cdot \frac {1 3}{6} - 4) (\frac {1 3}{6} - 3) | = \frac {2 5}{1 2}
$$

$$
| v (4) | = | (3 \cdot 4 - 4) (4 - 3) | = 8
$$

So it is moving fastest at $t = 0$ and its speed at $t = 0 { \mathrm { ~ i s ~ } } | v ( 0 ) | = 1 2$ 

17. Let f and g be diferentiable functions. Suppose the tangent line to the graph of $y = f ( x )$ at $x = 5 { \mathrm { ~ i s ~ } } y = 8 x + 7$ , and the tangent line to the graph of $y = g ( x )$ at $x = 3$ is $y = 4 x - 7$ Use this information in parts (a) and (b). 

(a) Let $h ( x ) = ( f \circ g ) ( x )$ . Find $h ^ { \prime } ( 3 )$ and an equation of the line tangent to the graph of $y = h ( x ) { \mathrm { ~ a t ~ } } x = 3 .$ 

Solution: Since $y = 8 x + 7$ is the line tangent to the graph of $y = f ( x ) \mathrm { a t } x = 5$ that must mean 

$$
f ^ {\prime} (5) = 8 \text {   and   } f (5) = 8 (5) + 7 = 4 7.
$$

Similarly, since $y = 4 x - 7$ is the line tangent to the graph of $y = g ( x )$ at $x = 3$ 更that must also mean

$$
g ^ {\prime} (3) = 4 \mathrm{and} g (3) = 5.
$$

Chain rule says ${ h ^ { \prime } ( x ) = f ^ { \prime } ( g ( x ) ) g ^ { \prime } ( x ) }$ , so at $x = 3 \colon$ 

$$
\begin{array}{r l} & h ^ {\prime} (3) = f ^ {\prime} (g (3)) g ^ {\prime} (3) \\ & \qquad = f ^ {\prime} (5) \cdot 4 \\ & \qquad = 8 \cdot 4 \\ & \qquad = 3 2. \end{array}
$$

For the equation of the tangent line, we also need the point of tangency, $( 3 , h ( 3 ) )$ We can calculate 

$$
h (3) = f (g (3)) = f (5) = 4 7.
$$

Hence the line tangent to the graph of $y = h ( x )$ at $x = 3$ has equation 

$$
y = 3 2 (x - 3) + 4 7.
$$

(b) Let $p ( x ) = 2 x \sin ( \pi f ( x ) )$ . Find $p ^ { \prime } ( 5 )$ and an equation of the line tangent to the graph of $y = p ( x )$ at $x = 5$ 

Solution: The product rule gives 

$$
p ^ {\prime} (x) = 2 \sin (\pi f (x)) + 2 x (\pi f ^ {\prime} (x) \cos (\pi f (x))).
$$

Then at $x = 5 { : }$ 

$$
p ^ {\prime} (5) = 2 \sin (4 7 \pi) + 2 (5) (8) \pi \cos (4 7 \pi) = - 8 0 \pi .
$$

For the equation of the tangent line, we also need the point of tangency, $( 5 , p ( 5 ) )$ . We can calculate 

$$
p (5) = 2 (5) \sin (4 7 \pi) = 0.
$$

So the line tangent to the graph of $y = p ( x )$ at $x = 5$ has equation 

$$
y = - 8 0 \pi (x - 5).
$$

18. Find f<sup>′</sup>(6) if $f ( g ( x ) ) = e ^ { x ^ { 2 } } , g ( 1 ) = 6$ , and $g ^ { \prime } ( 1 ) = 1 2$ 

Solution: We start by diferentiating both sides of the equation $f ( g ( x ) ) = e ^ { x ^ { 2 } }$ with respect to x: 

$$
\frac {d}{d x} [ f (g (x)) ] = \frac {d}{d x} \left[ e ^ {x ^ {2}} \right]
$$

$$
f ^ {\prime} (g (x)) g ^ {\prime} (x) = 2 x e ^ {x ^ {2}}
$$

Substituting $x = 1$ into the last equation will produce an equation that will allow us to solve for $f ^ { \prime } ( 6 )$ 

$$
f ^ {\prime} (g (1)) g ^ {\prime} (1) = 2 e \Longrightarrow f ^ {\prime} (6) \cdot 1 2 = 2 e \Longrightarrow f ^ {\prime} (6) = \frac {e}{6}.
$$

19. (a) Find $\frac { d y } { d x }$ where $8 x ^ { 2 } - 4 x y + y ^ { 2 } = 1 2 8$ 

Solution: Use implicit diferentiation: 

$$
8 x ^ {2} - 4 x y + y ^ {2} = 1 2 8
$$

$$
1 6 x - (4 x \frac {d y}{d x} + 4 y) + 2 y \frac {d y}{d x} = 0
$$

$$
1 6 x - 4 x \frac {d y}{d x} - 4 y + 2 y \frac {d y}{d x} = 0
$$

Diferentiate with respect to x. Note that xy is a product, so diferentiating xy requires the product rule. 

Distribute the minus sign 

$$
- 4 x \frac {d y}{d x} + 2 y \frac {d y}{d x} = 4 y - 1 6 x
$$

Put everything with a factor of ${ \frac { d y } { d x } } $ on one side of the equation, everything else on the other 

$$
{\frac {d y}{d x}} (2 y - 4 x) = 4 y - 1 6 x
$$

Factor out the $\textstyle { \frac { d y } { d x } }$ 

$$
\frac {d y}{d x} = \boxed {\frac {4 y - 1 6 x}{2 y - 4 x}}
$$

Divide through by 2y − 4x 

$$
\mathrm{OR} = \boxed {\frac {2 y - 8 x}{y - 2 x}}
$$

Optionally, you can multiply by $\textstyle { \frac { 1 { \dot { / } } 2 } { 1 / 2 } }$ to put in simpler form. But either boxed answer is correct. 

(b) Find the point(s) $( x , y )$ on the curve defined by $8 x ^ { 2 } - 4 x y + y ^ { 2 } = 1 2 8$ where the line tangent to the curve is horizontal. 

Solution: The tangent line is horizontal where $\begin{array} { r } { { \frac { d y } { d x } } = 0 } \end{array}$ , which — for the derivative found in part (a) — occurs where the numerator is 0. So: 

$$
2 y - 8 x = 0
$$

$$
2 y = 8 x
$$

$$
y = 4 x
$$

Then solve for x by substituting 4x for $y$ in the original equation: 

$$
8 x ^ {2} - 4 x y + y ^ {2} = 1 2 8
$$

$$
8 x ^ {2} - 4 x (4 x) + (4 x) ^ {2} = 1 2 8
$$

$$
8 x ^ {2} - 1 6 x ^ {2} + 1 6 x ^ {2} = 1 2 8
$$

$$
8 x ^ {2} = 1 2 8
$$

$$
x ^ {2} = 1 6
$$

$$
x = \pm 4
$$

Since we know that the horizontal tangents occur where $y = 4 x$ (see above), $y = 1 6$ when $x = 4 .$ , and $y = - 1 6$ when $x = - 4 .$ . Therefore, the points are: 

$$
\boxed {(4, 1 6) \text {and} (- 4, - 1 6)}
$$

20. Find the lines tangent and normal to the curve $x ^ { 3 } + y ^ { 3 } - 9 x y = 0$ at $( 2 , 4 )$ 

Solution: We first verify that $( 2 , 4 )$ is a point on the given curve: $2 ^ { 3 } + 4 ^ { 3 } - 9 ( 2 ) ( 4 ) = 0 .$ Next, find $\textstyle { \frac { d y } { d x } }$ at $( 2 , 4 )$ to determine the slope of the tangent line (and normal line) there. 

$$
{\frac {d}{d x}} \left(x ^ {3} + y ^ {3} - 9 x y\right) = 0
$$

$$
3 x ^ {2} + 3 y ^ {2} \frac {d y}{d x} - 9 y - 9 x \frac {d y}{d x} = 0
$$

This gives 

$$
{\frac {d y}{d x}} = {\frac {9 y - 3 x ^ {2}}{3 y ^ {2} - 9 x}}.
$$

At (2, 4), 

$$
\left. \frac {d y}{d x} \right| _ {(2, 4)} = \frac {9 \cdot 4 - 3 (2) ^ {2}}{3 (4) ^ {2} - 9 (2)} = \frac {4}{5}.
$$

The tangent line then has equation $\begin{array} { r } { y = \frac { 4 } { 5 } ( x - 2 ) + 4 . } \end{array}$ , while the normal line (which has negative reciprocal slope) has equation $\begin{array} { r } { y = - \frac { 5 } { 4 } ( x - 2 ) + 4 . } \end{array}$ 

21. Find equations of all lines tangent to the graph of $9 x ^ { 2 } - 1 8 x y + y ^ { 2 } = 7 2$ that are perpendicular to the line $x + 3 y = 1 0$ 

Solution: Lines that are perpendicular to the line $x + 3 y = 1 0$ must have slope 3 (since the line $x + 3 y = 1 0$ has $\mathrm { s l o p e - } 1 / 3 )$ . Since tangent lines have slope given by ${ \frac { d y } { d x } } .$ , we must have $\begin{array} { r } { \frac { d y } { d x } = 3 . } \end{array}$ . By implicit diferentiation, we compute the following expression for $\textstyle { \frac { d y } { d x } } ;$ 

$$
{\frac {d}{d x}} \left(9 x ^ {2} - 1 8 x y + y ^ {2}\right) = {\frac {d}{d x}} (7 2)
$$

$$
1 8 x - 1 8 y - 1 8 x \frac {d y}{d x} + 2 y \frac {d y}{d x} = 0
$$

$$
1 8 x - 1 8 y - 1 8 x (3) + 2 y (3) = 0
$$

$$
\left(\frac {d y}{d x} = 3\right)
$$

$$
y = - 3 x
$$

Substituting the condition $y = - 3 x$ back into the equation $9 x ^ { 2 } - 1 8 x y + y ^ { 2 } = 7 2$ for the curve yields 

$$
9 x ^ {2} + 5 4 x ^ {2} + 9 x ^ {2} = 7 2
$$

or $7 2 x ^ { 2 } = 7 2$ . This gives $x = - 1$ and $x = 1$ . The corresponding $( x , y )$ points are then $( - 1 , 3 )$ and $( 1 , - 3 )$ . The equations for the tangent lines are then 

$$
y = 3 (x + 1) + 3
$$

and 

$$
y = 3 (x - 1) - 3.
$$

22. Find each derivative. Use logarithmic diferentiation when appropriate, and give the derivative in terms of x only. 

(a) $\frac { d y } { d x }$ where $y = ( e ^ { x } + 2 ) ^ { \sin x }$ 

Solution: When the variable appears in both the base and the exponent of a function, the derivative has to be found by logarithmic diferentiation: 

$$
y = (e ^ {x} + 2) ^ {\sin x}
$$

ln $\begin{array} { r } { \mathfrak { i } y = \ln ( e ^ { x } + 2 ) ^ { \sin x } } \end{array}$ 

$$
\ln y = (\sin x) \ln (e ^ {x} + 2)
$$

$$
{\frac {y ^ {\prime}}{y}} = (\sin x) {\frac {d}{d x}} \left(\ln (e ^ {x} + 2)\right) + \ln (e ^ {x} + 2) {\frac {d}{d x}} (\sin x)
$$

$$
{\frac {y ^ {\prime}}{y}} = (\sin x) {\frac {e ^ {x}}{e ^ {x} + 2}} + \ln (e ^ {x} + 2) (\cos x)
$$

$$
y ^ {\prime} = y \left(\frac {e ^ {x} \sin x}{e ^ {x} + 2} + \ln (e ^ {x} + 2) (\cos x)\right)
$$

$$
y ^ {\prime} = \boxed {(e ^ {x} + 2) ^ {\sin x} \left(\frac {e ^ {x} \sin x}{e ^ {x} + 2} + \ln (e ^ {x} + 2) (\cos x)\right)}
$$

Take ln of both sides 

Apply law of logarithms: ln $\boldsymbol { a } ^ { b } = b \boldsymbol { 1 }$ ln a 

Diferentiate both sides, using chain rule on left and product rule on right. Note that y<sup>′</sup> is more convenient to write than $d y / d x ;$ in this question, either notation is fine. 

Evaluate derivatives. Note the use of the chain rule in finding the derivative of $\ln ( e ^ { x } + 2 )$ 

Move y to the right side of the equation 

Replace y with its original expression in x, since the question requires that the derivative be stated entirely in terms of x 

(b) $\frac { d y } { d x }$ where $y = { \frac { ( 5 x ^ { 2 } + 1 ) ^ { 2 } { \sqrt { x ^ { 6 } + 7 } } } { x ^ { 4 } + 3 } }$ 

Solution: This derivative could be found either by logarithmic diferentiation or by the quotient, product, and chain rules. By logarithmic diferentiation, the solution 

is: 

Take ln of both sides 

$$
\begin{array}{c} y = \frac {(5 x ^ {2} + 1) ^ {2} \sqrt {x ^ {6} + 7}}{x ^ {4} + 3} \\ \ln y = \ln \left(\frac {(5 x ^ {2} + 1) ^ {2} \sqrt {x ^ {6} + 7}}{x ^ {4} + 3}\right) \\ \ln y = 2 \ln (5 x ^ {2} + 1) + \frac {1}{2} \ln (x ^ {6} + 7) - \ln (x ^ {4} + 3) \\ \frac {y ^ {\prime}}{y} = \frac {2 \cdot 1 0 x}{5 x ^ {2} + 1} + \frac {1}{2} \cdot \frac {6 x ^ {5}}{x ^ {6} + 7} - \frac {4 x ^ {3}}{x ^ {4} + 3} \\ y ^ {\prime} = y \left(\frac {2 0 x}{5 x ^ {2} + 1} + \frac {3 x ^ {5}}{x ^ {6} + 7} - \frac {4 x ^ {3}}{x ^ {4} + 3}\right) \\ y ^ {\prime} = \boxed {\frac {(5 x ^ {2} + 1) ^ {2} \sqrt {x ^ {6} + 7}}{x ^ {4} + 3} \left(\frac {2 0 x}{5 x ^ {2} + 1} + \frac {3 x ^ {5}}{x ^ {6} + 7} - \frac {4 x ^ {3}}{x ^ {4} + 3}\right)} \end{array}
$$

Apply laws of logarithms to right side 

Diferentiate both sides. Don’t forget to use the chain rule as needed. 

Move y to right side of equation 

Replace y with its original expression in x 

The quotient, product, and chain rules would give the same answer in a diferent form: 

$$
\begin{array}{l} y ^ {\prime} = \frac {(x ^ {4} + 3) \cdot \frac {d}{d x} \left[ (5 x ^ {2} + 1) ^ {2} \sqrt {x ^ {6} + 7} \right] - (5 x ^ {2} + 1) ^ {2} \sqrt {x ^ {6} + 7} \cdot \frac {d}{d x} (x ^ {4} + 3)}{(x ^ {4} + 3) ^ {2}} \\ = \boxed {\frac {(x ^ {4} + 3) \left[ 2 (5 x ^ {2} + 1) (1 0 x) \sqrt {x ^ {6} + 7} + (5 x ^ {2} + 1) ^ {2} \frac {1}{2} (x ^ {6} + 7) ^ {- \frac {1}{2}} (6 x ^ {5}) \right] - (5 x ^ {2} + 1) ^ {2} \sqrt {x ^ {6} + 7} \cdot (4 x ^ {3})}{(x ^ {4} + 3) ^ {2}}} \end{array}
$$

(c) $\frac { d y } { d x }$ where $y = ( \ln x ) ^ { \cos ( 3 x ) }$ 

Solution: We will again use the technique of logarithmic diferentiation. When we apply the natural logarithm to both sides of the equation for y we have 

$$
\ln y = \cos (3 x) \ln (\ln x).
$$

Next we use implicit diferentiation with respect to x to obtain a formula for $\frac { d y } { d x }$ : 

$$
{\frac {d}{d x}} [ \ln y ] = {\frac {d}{d x}} [ \cos (3 x) \ln (\ln x) ]
$$

$$
{\frac {1}{y} \frac {d y}{d x}} = {- 3 \sin (3 x) \cdot \ln (\ln x) + \cos (3 x) \cdot \frac {(1 / x)}{\ln x}}
$$

$$
{\frac {d y}{d x}} = {\left[ - 3 \sin (3 x) \cdot \ln (\ln x) + \frac {\cos (3 x)}{x \ln x} \right] \cdot (\ln x) ^ {\cos (3 x)}.}
$$

23. Consider the curve with equation $x ^ { 1 9 y } = y ^ { 9 x }$ . Use this equation in parts (a) and (b). 

(a) Use implicit diferentiation to find ${ \frac { d y } { d x } } .$ 

Solution: We begin by taking the natural logarithm on both sides of the equation and applying the properties of the logarithm. This yields 

$$
\ln (x ^ {1 9 y}) = \ln (y ^ {9 x})
$$

$$
1 9 y \ln x = 9 x \ln y
$$

Now we are ready to use implicit diferentiation to find a formula for ${ \frac { d y } { d x } } .$ . We have 

$$
{\frac {d}{d x}} [ 1 9 y \ln x ] = {\frac {d}{d x}} [ 9 x \ln y ]
$$

$$
1 9 \frac {d y}{d x} \ln x + \frac {1 9 y}{x} = 9 \ln y + \frac {9 x}{y} \cdot \frac {d y}{d x}
$$

$$
\left(1 9 \ln x - \frac {9 x}{y}\right) \frac {d y}{d x} = 9 \ln y - \frac {1 9 y}{x}
$$

$$
\begin{array}{r c l} \frac {d y}{d x} & = & \frac {(9 \ln y - 1 9 y / x)}{(1 9 \ln x - 9 x / y)} \\ & = & \frac {(9 x \ln y - 1 9 y) y}{(1 9 y \ln x - 9 x) x}. \end{array}
$$

(b) Find an equation of the tangent line to the curve at the point (1, 1). 

Solution: The slope of the tangent to the curve at the point $( 1 , 1 )$ is 

$$
\left. \frac {d y}{d x} \right| _ {(1, 1)} = \frac {(9 (0) - 1 9 (1)) (1)}{(1 9 (0) - 9) (1)} = \frac {1 9}{9}.
$$

Thus the tangent line to the curve at the point (1, 1) is given by 

$$
y - 1 = \frac {1 9}{9} (x - 1) \mathrm{or} y = \frac {1 9}{9} x - \frac {1 0}{9}.
$$

24. Suppose that $f ( x )$ is a diferentiable function such that $f ( 0 ) = { \frac { 1 } { 2 } }$ and $f ^ { \prime } ( 0 ) = 3$ . Evaluate the following derivatives. (Hint: Start by applying the chain rule.) 

$$
\text {(a)} g ^ {\prime} (0) \text {if} g (x) = \cos (\sin^ {- 1} (f (x)))
$$

Solution: The derivative is 

$$
g ^ {\prime} (x) = - \sin \left(\sin^ {- 1} (f (x))\right) \cdot \frac {f ^ {\prime} (x)}{\sqrt {1 - [ f (x) ] ^ {2}}} = - \frac {f (x) f ^ {\prime} (x)}{\sqrt {1 - [ f (x) ] ^ {2}}}.
$$

Next we evaluate the derivative at $x = 0 \colon$ 

$$
\begin{array}{r l} g ^ {\prime} (0) & = - \frac {(1 / 2) (3)}{\sqrt {1 - 1 / 4}} \\ & = - \frac {3 / 2}{\sqrt {3} / 2} \\ & = - \frac {3}{\sqrt {3}} \\ & = \boxed {- \sqrt {3}}. \end{array}
$$

## (b) h<sup>′</sup>(0) if $h ( x ) = \sin { \big ( } \tan ^ { - 1 } ( f ( x ) ) { \big ) }$

Solution: The derivative is given by 

$$
h ^ {\prime} (x) = \cos \left(\tan^ {- 1} (f (x))\right) \cdot \frac {f ^ {\prime} (x)}{1 + [ f (x) ] ^ {2}}.
$$

Substituting $x = 0$ yields 

$$
h ^ {\prime} (0) = \cos \left(\tan^ {- 1} \left(\frac {1}{2}\right)\right) \cdot \frac {3}{1 + 1 / 4}.
$$

To evaluate cos $\left( \tan ^ { - 1 } ( 1 / 2 ) \right)$ , we can use a right triangle: tan<sup>−</sup> $^ { - 1 } ( 1 / 2 ) = \theta$ if and only if 

$$
\tan \theta = \frac {1}{2} \qquad \mathrm{and} \qquad - \frac {\pi}{2} <   \theta <   \frac {\pi}{2}.
$$

So this is an angle in the 1st quadrant and the right triangle is 

![image](https://cdn-mineru.openxlab.org.cn/result/2026-10-27/1eaeb0ab-7f73-4b78-bbe3-c094feb83019/33a07050d28aaa62b9c74952ab36dffb7d1ee1dafe00081482c26d401d349491.jpg)


We may now conclude that 

$$
\begin{array}{c} h ^ {\prime} (0) = \frac {2}{\sqrt {5}} \cdot \frac {3}{5 / 4} \\ = \boxed {\frac {2 4}{5 \sqrt {5}}} \end{array} .
$$

## (c) p<sup>′</sup>(0) if p(x) = cot sec<sup>−1</sup> p1 + f(x)

Solution: The derivative is given by 

$$
p ^ {\prime} (x) = - \csc^ {2} \left(\sec^ {- 1} \left(\sqrt {1 + f (x)}\right)\right) \cdot \frac {f ^ {\prime} (x)}{2 (1 + f (x)) \sqrt {f (x)}}.
$$

Evaluating the derivative at $x = 0$ 2 

$$
p ^ {\prime} (0) = - \csc^ {2} \left(\sec^ {- 1} \left(\sqrt {\frac {3}{2}}\right)\right) \cdot \frac {3}{2 (3 / 2) \sqrt {1 / 2}}.
$$

To evaluate $\csc ^ { 2 } \left( \sec ^ { - 1 } \left( { \sqrt { \frac { 3 } { 2 } } } \right) \right)$ , we can use a right triangle: $\sec ^ { - 1 } \left( { \sqrt { \frac { 3 } { 2 } } } \right) = \theta$ if and only if 

$$
\sec \theta = \sqrt {\frac {3}{2}} \qquad \text { and } \qquad 0 \leq \theta \leq \pi , \quad \theta \neq \frac {\pi}{2}.
$$

The angle must be in the 1st quadrant, so the right triangle is 

![image](https://cdn-mineru.openxlab.org.cn/result/2026-10-27/1eaeb0ab-7f73-4b78-bbe3-c094feb83019/6cc0dc143985a7be06c0707c45ca3cd9cc638875e5ef1bff27b42a100227cf2e.jpg)


Thus 

$$
\begin{array}{r l} p ^ {\prime} (0) & = - 3 \cdot \frac {3}{3 \sqrt {1 / 2}} \\ & = - \frac {3}{\sqrt {1 / 2}} \\ & = \boxed {- 3 \sqrt {2}}. \end{array}
$$

25. Find the value of b if 

(a) $f ( x ) = \cos ( 3 x ) b ^ { x } { \mathrm { ~ a n d ~ } } f ^ { \prime } ( 0 ) = 1 0 .$ 

Solution: We see that $f ^ { \prime } ( x )$ is given by 

$$
f ^ {\prime} (x) = - 3 \sin (3 x) b ^ {x} + (\ln b) \cos (3 x) b ^ {x}.
$$

Substituting $x = 0$ yields 

$$
1 0 = \ln b \Longrightarrow b = e ^ {1 0}.
$$

$$
\text {(b)} f (x) = \frac {\log_ {b} (x + 1)}{\cos (3 x)} \text { and } f ^ {\prime} (0) = 1 0.
$$

Solution: The first derivative is found to be 

$$
f ^ {\prime} (x) = \frac {(1 / \ln b) (1 / (x + 1)) \cos (3 x) - \log_ {b} (x + 1) (- 3 \sin (3 x))}{\cos^ {2} (3 x)}.
$$

Replacing x with 0 in the previous equation produces 

$$
1 0 = \frac {(1 / \ln b) (1) (1)}{1} \Longrightarrow 1 0 = \frac {1}{\ln b} \text { or } \ln b = \frac {1}{1 0} \Longrightarrow b = e ^ {1 / 1 0}.
$$

26. If $y = x ^ { 3 }$ and ${ \frac { d y } { d t } } = - 3$ , find $\frac { d x } { d t }$ when $x = 2$ 

Solution: Since $y = x ^ { 3 }$ , the derivative $\begin{array} { r } { \frac { d y } { d t } = 3 x ^ { 2 } \frac { d x } { d t } } \end{array}$ . There are various ways to understand why this is the derivative with respect to t. Here is one of them: 

$$
y = x ^ {3}
$$

$$
{\frac {d y}{d x}} = 3 x ^ {2}
$$

Find dy/dx 

$$
\frac {d y}{d x} \cdot \frac {d x}{d t} = 3 x ^ {2} \frac {d x}{d t}
$$

$$
{\frac {d y}{d t}} = 3 x ^ {2} {\frac {d x}{d t}}
$$

Multiply by dx/dt on both sides of the equation Cancel the dx’s on the left side of the equation 

Now, we need to find an expression for $\textstyle { \frac { d x } { d t } }$ in terms of x and $\frac { d y } { d t }$ , so we divide the last equation through by $3 x ^ { 2 }$ , giving 

$$
{\frac {d x}{d t}} = {\frac {1}{3 x ^ {2}}} \cdot {\frac {d y}{d t}}
$$

We now substitute in the given values of $x = 2$ and $\begin{array} { r } { \frac { d y } { d t } = - 3 . } \end{array}$ , giving $\textstyle { \frac { 1 } { 3 ( 2 ^ { 2 } ) } } \cdot ( - 3 )$ , or $\boxed { - 1 / 4 } .$ 

27. A closed rectangular box has a height of x meters (m). The box is shrinking in such a way that at any given time, its depth is 2 times its height and its width is 5 times its height, as shown. The surface area of the box is decreasing at a constant rate of 3 $\mathrm { m ^ { 2 } }$ per minute. At what rate is the volume of the box changing when the height of the box (x) is 2 m? (Hint: Start by writing formulas in terms of x for the surface area (A) and volume (V ) of the box.) 

![image](https://cdn-mineru.openxlab.org.cn/result/2026-10-27/1eaeb0ab-7f73-4b78-bbe3-c094feb83019/1e422574b597fd583cb9a30d7569b7fe88341e5166804d8441aa6690021073c7.jpg)


Solution: Start by writing the formulas for the surface area (A) and volume (V ) of the box. 

The volume of the box is $V = ( 5 x ) ( 2 x ) ( x ) = 1 0 x ^ { 3 }$ . The surface area of the box is the sum of the areas of all six of its sides: 

$$
{ \begin{array}{r l} & {A = 2 \times (x \cdot 2 x) + 2 \times (x \cdot 5 x) + 2 \times (2 x \cdot 5 x)} \\ & {\quad = 4 x ^ {2} + 1 0 x ^ {2} + 2 0 x ^ {2}} \\ & {\quad = 3 4 x ^ {2}} \end{array} }
$$

So $A = 3 4 x ^ { 2 }$ and $V = 1 0 x ^ { 3 } .$ 

The question is asking for $\textstyle { \frac { d V } { d t } }$ . From the equation for V above, we see that 

$$
\frac {d V}{d t} = 3 0 x ^ {2} \frac {d x}{d t}\tag{1}
$$

The problem doesn’t tell us what $\textstyle { \frac { d x } { d t } }$ is, but it does tell us that $\textstyle { \frac { d A } { d t } } = - 3$ (in other words, change in surface area (A) per change in time (t) is $- 3 \mathrm { \ m ^ { 2 } }$ per minute — negative because the surface area is decreasing). So we need to write $\textstyle { \frac { d x } { d t } }$ in terms of $\textstyle { \frac { d A } { d t } }$ : 

$$
A = 3 4 x ^ {2}
$$

$$
\frac {d A}{d t} = 6 8 x \frac {d x}{d t}
$$

$$
{\frac {d x}{d t}} = {\frac {1}{6 8 x}} \cdot {\frac {d A}{d t}}
$$

Divide both sides by 68x 

Now we substitute the equation for $\textstyle { \frac { d x } { d t } }$ into equation (1) from above: 

$$
\frac {d V}{d t} = 3 0 x ^ {2} \frac {d x}{d t}
$$

$$
\frac {d V}{d t} = 3 0 x ^ {2} \underbrace {\frac {1}{6 8 x} \cdot \frac {d A}{d t}} _ {d x / d t}\tag{1}
$$

$$
\frac {d V}{d t} = \frac {3 0 x}{6 8} \cdot \frac {d A}{d t}
$$

$$
\frac {d V}{d t} = \frac {1 5 x}{3 4} \cdot \frac {d A}{d t}
$$

The problem asks at what rate the volume is changing when the height of the box is 2 m, so we substitute $x = 2$ and $\textstyle { \frac { d A } { d t } } = - 3$ into the last equation, yielding: 

$$
\frac {d V}{d t} = \frac {1 5 \cdot 2}{3 4} \cdot (- 3) = - \frac {9 0}{3 4} = \boxed {- \frac {4 5}{1 7} \mathrm{m} ^ {3} / \mathrm{min}}
$$

Note that the answer is negative because the volume of the box is decreasing. 

28. A rope is attached to the bottom of a hot-air balloon that is floating above a flat field. If the angle of the rope to the ground remains $\frac { \pi } { 6 }$ radians and the rope is pulled in at 3 ft/sec, how quickly is the elevation of the balloon decreasing when the balloon is 27 ft above the ground? 

Be sure you define any variables used, draw an appropriate picture, use calculus to justify your answer, and report your answer in a sentence with appropriate units. 

Solution: The balloon, the rope, and the elevation of the balloon are sketched below. 

![image](https://cdn-mineru.openxlab.org.cn/result/2026-10-27/1eaeb0ab-7f73-4b78-bbe3-c094feb83019/20afdbf7446a11bbe698032cdf7c55515b47cce72b68894d3761a4f7327d7059.jpg)


The variables in the picture have the following meanings: z denotes the length of the rope that connects the balloon to the ground and $y$ is the elevation of the balloon. We are told that 

$$
{\frac {d z}{d t}} = - 3 {\mathrm{ft/sec.}}
$$

We are asked to find 

$$
\left. \frac {d y}{d t} \right| _ {y = 2 7 \mathrm{ft}}.
$$

Since the angle of the rope with the ground remains constant, we see that the following equation holds true as time varies: 

$$
\sin {\frac {\pi}{6}} = \frac {y}{z} \mathrm{or} \frac {1}{2} = \frac {y}{z} \mathrm{orevenbetter,} y = \frac {1}{2} z.
$$

Using implicit diferentiation with respect to t gives 

$$
{\frac {d y}{d t}} = {\frac {1}{2}} {\frac {d z}{d t}}.
$$

Thus we see 

$$
\left. \frac {d y}{d t} \right| _ {y = 2 7 \mathrm{ft}} = \frac {1}{2} (- 3 \mathrm{ft/sec}) = - \frac {3}{2} \mathrm{ft/sec}.
$$

We may conclude that the elevation of the balloon is decreasing at a rate of $\frac { 3 } { 2 } \mathrm { \ f t / s e c }$ when the balloon is 27 ft above the ground. 

29. A spherical iron ball 10 in. in diameter is coated with a layer of ice of uniform thickness. If the ice melts at a rate of 14 $\mathrm { i n ^ { 3 } } { } _ { / }$ /min, how fast is the thickness of the ice decreasing when it is 4 in thick? How fast is the outer surface area of the ice decreasing? 

Be sure you define any variables used, draw an appropriate picture, use calculus to justify your answer, and report your answer in a sentence with appropriate units. 

Solution: The sphere and the ice layer can be depicted as in the sketch below: 

![image](https://cdn-mineru.openxlab.org.cn/result/2026-10-27/1eaeb0ab-7f73-4b78-bbe3-c094feb83019/eba18779d58822f382f1931229bc2dbc15e554260a2622e2ada11a753fcbd416.jpg)


Let x represent the thickness of the ice, let V represent the volume of the ice, and let A represent the outer surface area of the ice. We are told that 

$$
\frac {d V}{d t} = - 1 4 \mathrm{in} ^ {3} / \mathrm{min},
$$

and we are tasked with finding $\left. { \frac { d x } { d t } } \right| _ { x = 4 { \mathrm { ~ i n } } } { \mathrm { ~ a n d ~ } } { \frac { d A } { d t } } { \bigg | } _ { x = 4 { \mathrm { ~ i n } } } .$ 

Notice that the volume of the ice is given by 

$$
V = \frac {4}{3} \pi (x + 5) ^ {3} - \frac {4}{3} \pi (5 ^ {3}).
$$

Thus 

$$
{\frac {d V}{d t}} = 4 \pi (x + 5) ^ {2} {\frac {d x}{d t}} \Longrightarrow {\frac {d x}{d t}} = {\frac {d V / d t}{4 \pi (x + 5) ^ {2}}}.
$$

We see that 

$$
\left. \frac {d x}{d t} \right| _ {x = 4 \mathrm{in}} = \frac {- 1 4 \mathrm{in} ^ {3} / \mathrm{min}}{4 \pi (9 \mathrm{in}) ^ {2}} = \frac {- 1 4}{4 \pi (9 ^ {2})} \mathrm{in/min}.
$$

The thickness of the ice is decreasing at a rate of ${ \frac { 7 } { 1 6 2 \pi } } ~ \mathrm { i n / }$ /min when the ice is 4 inches thick. 

Since the radius of the sphere + ice is $r = x + 5$ , the surface area A of the ice is computed by 

$$
A = 4 \pi (x + 5) ^ {2}.
$$

Hence $\frac { d A } { d t } = 8 \pi ( x + 5 ) \frac { d x } { d t }$ . Notice that 

$$
\left. \frac {d A}{d t} \right| _ {x = 4 \mathrm{in}} = (8 \pi (4 + 5) \mathrm{in}) \left(\frac {- 1 4}{4 \pi (9 ^ {2})} \mathrm{in/min}\right) = \frac {- 8 \pi (9) (1 4)}{4 \pi (9 ^ {2})} \mathrm {in^ {2} /min} = \frac {- 2 8}{9} \mathrm {in^ {2} /min}.
$$

The outer surface area of ice is decreasing at a rate of $\frac { 2 8 } { 9 } \mathrm { i n ^ { 2 } / m i n }$ when the ice is 4 inches thick. 

30. Approximate $\frac { 1 } { \sqrt { 1 0 } }$ by completing the steps $\mathrm { ( a ) - ( e ) }$ 

(a) What would be an appropriate function $f ( x )$ and center a for this linearization? 

Solution: An appropriate function to use is $f ( x ) = { \frac { 1 } { \sqrt { x } } }$ . With this choice for f, the best choice for a is $a = 9$ 

(b) Find $L ( x )$ for your choices from part (a). 

Solution: The linearization for f centered at $a = 9$ is 

$$
L (x) = f ^ {\prime} (9) (x - 9) + f (9).
$$

Notice that 

$$
f (9) = \frac {1}{3} \text { and } f ^ {\prime} (x) = - \frac {1}{2} x ^ {- 3 / 2} = - \frac {1}{2 x ^ {3 / 2}} \Rightarrow f ^ {\prime} (9) = - \frac {1}{5 4}.
$$

Hence the linearization is 

$$
L (x) = - \frac {1}{5 4} (x - 9) + \frac {1}{3}.
$$

(c) Find dx so that $f ( a + d x ) = { \frac { 1 } { \sqrt { 1 0 } } } .$ 

Solution: Since $a = 9 , 1 0 = 9 + d x \Rightarrow d x = 1$ 

(d) Find the standard linear approximation of $\frac { 1 } { \sqrt { 1 0 } }$ using your choices for f and a. 

Solution: The standard linear approximation of $\frac { 1 } { \sqrt { 1 0 } }$ is 

$$
{\frac {1}{\sqrt {1 0}}} = f (1 0) \approx L (1 0) = - {\frac {1}{5 4}} (1 0 - 9) + {\frac {1}{3}} = {\frac {1 7}{5 4}}.
$$

(e) Approximate the diference ${ \frac { 1 } { \sqrt { 1 0 } } } - { \frac { 1 } { 3 } } .$ 

Solution: The diference $\textstyle { \frac { 1 } { \sqrt { 1 0 } } } - { \frac { 1 } { 3 } } = f ( 1 0 ) - f ( 9 )$ . We can approximate this change in f via the diferential of f at $x = 9 \colon$ 

$$
f (1 0) - f (9) \approx d f = f ^ {\prime} (9) d x.
$$

Since $\begin{array} { r } { f ^ { \prime } ( 9 ) = - \frac { 1 } { 5 4 } \mathrm { ~ a n d ~ } d x = 1 , \mathrm { w e ~ g e t ~ } \frac { 1 } { \sqrt { 1 0 } } - \frac { 1 } { 3 } \approx - \frac { 1 } { 5 4 } \cdot 1 = - \frac { 1 } { 5 4 } . } \end{array}$ 

31. Suppose $f ( 2 ) = 5 , f ^ { \prime } ( 2 ) = - 3$ , and $g ( x ) = x ^ { 3 } f ( x )$ . You may assume both f and g are invertible. 

(a) Find an equation of the line tangent to $y = f ( x )$ at $x = 2 .$ 

Solution: The problem statement shows that the graph of $y = f ( x )$ has the point (2, 5) and its tangent line slope at that point is −3. Therefore, an equation (in point-slope form, which is the preferred way to answer such questions) is: 

$$
\boxed {y - 5 = - 3 (x - 2)}
$$

(b) Find an equation of the line tangent to $y = f ^ { - 1 } ( x )$ at $x = 5$ 

Solution: Since $y = f ( x )$ has point (2, 5) with a tangent slope of −3, the Derivative Rule for Inverses shows that $y = f ^ { - 1 } ( x )$ has point (5, 2) with a tangent slope of $- { \frac { 1 } { 3 } } .$ . (Switch the x and y coordinates, and use the reciprocal of the slope. See Theorem 3 and ${ \mathrm { F i g . } }$ 3.36 on page 174 of the textbook). Therefore, an equation for the tangent line is: 

$$
\boxed {y - 2 = - \frac {1}{3} (x - 5)}
$$

(c) Use a linear approximation (with center $x = 2 )$ to find an approximate value of $g ( 1 )$ 

Solution: The linearization of $g ( x )$ at center $x = 2$ is 

$$
L (x) = g (2) + g ^ {\prime} (2) (x - 2)
$$

$g ( 2 ) = 2 ^ { 3 } f ( 2 ) = 8 \cdot 5 = 4 0 .$ . Using the product rule, $g ^ { \prime } ( x ) = x ^ { 3 } f ^ { \prime } ( x ) + 3 x ^ { 2 } f ( x )$ , so 

$$
\begin{array}{r} g ^ {\prime} (2) = 2 ^ {3} f ^ {\prime} (2) + 3 \cdot 2 ^ {2} f (2) \\ = 8 (- 3) + 1 2 (5) \\ = - 2 4 + 6 0 = 3 6 \end{array}
$$

Therefore 

$$
L (x) = 4 0 + 3 6 (x - 2)
$$

Since $g ( 1 ) \approx L ( 1 )$ , an approximate value of $g ( 1 )$ is 

$$
L (1) = 4 0 + 3 6 (1 - 2) = 4 0 + 3 6 (- 1) = \boxed {4}
$$

(d) Find an equation of the line tangent to $y = g ^ { - 1 } ( x )$ at $x = g ( 2 )$ 

Solution: We determined in part (c) that $g ( 2 ) = 4 0$ and $g ^ { \prime } ( 2 ) = 3 6$ . Therefore, $y = g ( x )$ has point (2, 40) with tangent slope 36, so $y = g ^ { - 1 } ( x )$ has point $( 4 0 , 2 )$ with tangent slope $\textstyle { \frac { 1 } { 3 6 } }$ . Therefore, an equation of the line tangent to $y = g ^ { - 1 } ( x )$ at $x = g ( 2 ) = 4 0$ is 

$$
\boxed {y - 2 = \frac {1}{3 6} (x - 4 0)}
$$

32. Evaluate lim $\left( { \sqrt { 8 1 x ^ { 2 } + 3 3 x } } - { \sqrt { 8 1 x ^ { 2 } + 2 8 x } } \right)$ x→∞ 

$$
\begin{array}{r l r} & {\mathrm{Solution:}} \\ & {\quad \lim _ {x \to \infty} \left(\sqrt {8 1 x ^ {2} + 3 3 x} - \sqrt {8 1 x ^ {2} + 2 8 x}\right) \cdot \underbrace {\frac {\sqrt {8 1 x ^ {2} + 3 3 x} + \sqrt {8 1 x ^ {2} + 2 8 x}}{\sqrt {8 1 x ^ {2} + 3 3 x} + \sqrt {8 1 x ^ {2} + 2 8 x}}} _ {= 1} \quad \mathrm{Multiplybyconjugateoverconjugate.}} \\ & {\quad = \lim _ {x \to \infty} \frac {(8 1 x ^ {2} + 3 3 x) - (8 1 x ^ {2} + 2 8 x)}{\sqrt {8 1 x ^ {2} + 3 3 x} + \sqrt {8 1 x ^ {2} + 2 8 x}}} & {\mathrm{Simplify}} \\ & {\quad = \lim _ {x \to \infty} \frac {5 x}{\sqrt {8 1 x ^ {2} + 3 3 x} + \sqrt {8 1 x ^ {2} + 2 8 x}} \cdot \underbrace {\frac {1 / x}{\sqrt {1 / x ^ {2}}}} _ {= 1}} & {\mathrm{Simplifyfurther anddivideouttheghestpower}} \\ & {\quad = \lim _ {x \to \infty} \frac {5}{\sqrt {8 1 + \frac {3 3}{x}} + \sqrt {8 1 + \frac {2 8}{x}}}} & {\mathrm{Simplify}} \\ & {\quad = \frac {5}{\sqrt {8 1 + 0} + \sqrt {8 1 + 0}}} & {\mathrm{Evaluatethelimits}} \\ & {\quad = \frac {5}{2 \sqrt {8 1}} = \frac {5}{2 \cdot 9} = \boxed {\frac {5}{1 8}}} \end{array}
$$

33. Let $f ( x )$ be the function whose graph is shown in the drawing below, and let $g ( x ) = x ^ { 2 } -$ $7 x + 1 0$ . In the drawing below, you may assume $f ( x )$ crosses the x-axis at an integer value of x, and that the portion of the graph where $x > 3$ is a line. 

![image](https://cdn-mineru.openxlab.org.cn/result/2026-10-27/1eaeb0ab-7f73-4b78-bbe3-c094feb83019/35508580ad1ddf3a40711148f6683004302291d8ac5ba04119466e8c3965e1de.jpg)


Find each of the following. For each question that asks for a limit, if you can calculate its value, write that value. Otherwise write $+ \infty , - \infty ,$ or DNE. However, DNE will be treated as correct only if none of the other possible answers is correct. 

(a) $\operatorname* { l i m } _ { x \to 2 ^ { + } } { \frac { 1 } { g ( x ) } }$ 

Solution: Observe that $g ( x ) = x ^ { 2 } - 7 x + 1 0 = ( x - 2 ) ( x - 5 )$ . Note that $g ( x )$ is a continuous function (it’s quadratic), so $\operatorname* { l i m } _ { x \to c } { g ( x ) } = g ( c )$ for any value of $c .$ Therefore, 

$$
\lim _ {x \to 2 ^ {+}} \frac {1}{g (x)} = \frac {1}{(2 - 2) (2 - 5)} = \frac {1}{0}
$$

which is in the form $\frac { \mathrm { n o n z e r o } } { \mathrm { z e r o } }$ , so the limit is infinite. An infinite limit does not exist, but based on the instructions in the problem, we cannot just write DNE $\mathrm { i f } + \infty$ or $- \infty$ applies. The following sign chart shows that $g ( x )$ is positive on $( - \infty , 2 )$ and $( 5 , \infty )$ , but negative on the interval (2, 5): 

$$
\begin{array}{c c c c c c} & & \mid & & \\ \hline & & 2 & + & 5 & + \\ x - 2 & - & & + & & + \\ x - 5 & - & & - & & + \\ g (x) & + & & - & & + \end{array}
$$

Since $g ( x )$ is negative directly to the right of $x = 2 .$ , the answer is $\operatorname* { l i m } _ { x \to 2 ^ { + } } { \frac { 1 } { g ( x ) } } = \boxed { - \infty } .$ 

(b) $\operatorname* { l i m } _ { x \to 2 ^ { - } } { \frac { f ( x ) } { g ( x ) } }$ 

Solution: Based on the graph, $\operatorname* { l i m } _ { x \to 2 ^ { - } } f ( x ) = 1$ . Therefore, $\operatorname* { l i m } _ { x \to 2 ^ { - } } { \frac { f ( x ) } { g ( x ) } }$ simplifies to $\begin{array} { r } { \frac { 1 } { g ( 2 ) } = \frac { 1 } { 0 } } \end{array}$ , which means the limit is infinite. $f ( x )$ and $g ( x )$ are both positive to the left of $x = 2$ (see the graph of $f ( x )$ , and the sign chart for $g ( x )$ in the solution to the previous part), so $\textstyle { \frac { f ( x ) } { g ( x ) } }$ is also positive to the left of $x \ = \ 2$ . Therefore, $\operatorname* { l i m } _ { x \to 2 ^ { - } } { \frac { f ( x ) } { g ( x ) } } = \boxed { + \infty } .$ 

(c) lim $\frac { f ( x ) } { g ( x ) }$ x→2 

Solution: The graph shows that $\operatorname* { l i m } _ { x \to 2 ^ { + } } f ( x ) = - 1$ , so lim $\begin{array} { r } { \frac { f ( x ) } { g ( x ) } = \frac { - 1 } { g ( 2 ) } = \frac { - 1 } { 0 } } \end{array}$ , which x→2<sup>+</sup> is infinite. $f ( x )$ and $g ( x )$ are both negative to the right of $x = 2$ (see the graph of $f ( x )$ , and the sign chart for $g ( x ) )$ , so $\displaystyle \frac { \breve { f ( x ) } } { g ( x ) }$ is positive to the right of $x = 2$ . Therefore $\textstyle { \frac { f ( x ) } { g ( x ) } }$ approaches $+ \infty$ on both the left of $x = 2$ (see the solution to the last part) and on the right, so lim ${ \frac { f ( x ) } { g ( x ) } } = \boxed { + \infty } .$ x→2 

(d) $\operatorname* { l i m } _ { x \to 4 ^ { + } } { \frac { g ( x ) } { f ( x ) } }$ 

Solution: The graph shows that $\operatorname* { l i m } _ { x \to 4 ^ { + } } f ( x ) = 0 , { \mathrm { ~ s o ~ } } \operatorname* { l i m } _ { x \to 4 ^ { + } } { \frac { g ( x ) } { f ( x ) } }$ simplifies to $\begin{array} { r } { \frac { g ( 4 ) } { 0 } = } \end{array}$ $\frac { - 2 } { 0 }$ , which is infinite. To determine whether the limit is positive or negative, observe that the graph shows $f ( x )$ is positive to the right of $x = 4$ and the sign chart from the solution to part $\mathrm { ( a ) }$ shows that $g ( x )$ is negative to the right of $x = 4$ (it is negative on the entire interval $2 < x < 5 )$ . Therefore the quotient $\textstyle { \frac { g ( x ) } { f ( x ) } }$ is negative directly to the right of $x = 4 .$ , so $\operatorname* { l i m } _ { x \to 4 ^ { + } } { \frac { g ( x ) } { f ( x ) } } = \boxed { - \infty } .$ 

(e) $\operatorname* { l i m } _ { x \to 4 } { \frac { f ( x ) } { g ( x ) } }$ 

Solution: The graph shows that $\operatorname* { l i m } _ { x \to 4 } f ( x ) = 0 , \operatorname { s o } \operatorname* { l i m } _ { x \to 4 } { \frac { f ( x ) } { g ( x ) } } = { \frac { 0 } { g ( 4 ) } } = { \frac { 0 } { - 2 } } = { \boxed { 0 } } .$ 

(f) $\operatorname* { l i m } _ { x \to 1 } { \frac { f ( x ) } { g ( x ) } }$ 

Solution: The graph shows that $\operatorname* { l i m } _ { x \to 1 } f ( x ) = 2 , \operatorname { s o } \operatorname* { l i m } _ { x \to 1 } { \frac { f ( x ) } { g ( x ) } } = { \frac { 2 } { g ( 1 ) } } = { \frac { 2 } { 4 } } = { \Bigg [ } { \frac { 1 } { 2 } } { \Bigg ] } .$ 

(g) $\operatorname* { l i m } _ { x \to 5 ^ { - } } { \frac { f ( x ) } { g ( x ) } }$ 

Solution: The graph shows that $\operatorname* { l i m } _ { x \to 5 } f ( x ) = 2$ (approaching $x = 5$ from either side), so lim $\begin{array} { r } { \frac { f ( x ) } { g ( x ) } = \frac { 2 } { g ( 5 ) } = \frac { 2 } { 0 } . } \end{array}$ , which is infinite. The graph shows $f ( x )$ is positive x→5<sup>−</sup> to the left of $x = 5$ , and the sign chart in the solution to part (a) shows $g ( x )$ is negative to the left of $x = 5$ $\begin{array} { r } { \frac { \mathrm { p o s i t i v e } } { \mathrm { n e g a t i v e } } = \mathrm { n e g a t i v e } , } \end{array}$ , so $\operatorname* { l i m } _ { x \to 5 ^ { - } } { \frac { f ( x ) } { g ( x ) } } = \boxed { - \infty } .$ 

(h) $\operatorname* { l i m } _ { x \to 5 } { \frac { f ( x ) } { g ( x ) } }$ 

Solution: This limit simplifies to $\frac { 2 } { 0 }$ which is infinite. $f ( x )$ and $g ( x )$ are both positive to the right of $x = 5$ (see the graph of $f$ and the sign chart for $g )$ , so their quotient $\frac { f ( x ) } { g ( x ) }$ is also positive to the right of $x = 5$ . We found in the previous part that $\textstyle { \frac { f ( x ) } { g ( x ) } }$ is negative to the left of $x = 5$ . Since the limit in the question is $- \infty$ approaching $x = 5$ from the left and +∞ approaching from the right, the only statement we can make about this limit is that it does not exist. Answer: DNE 

(i) f<sup>′</sup>(5) 

Solution: Near $x = 5$ , the graph of $f$ is a line with slope 2. (Find this by applying the slope formula to any two points on the line.) The derivative of a linear function is its slope, so $f ^ { \prime } ( 5 ) = { \overline { { 2 } } } .$ 

![image](https://cdn-mineru.openxlab.org.cn/result/2026-10-27/1eaeb0ab-7f73-4b78-bbe3-c094feb83019/e140a3e8d6653c52a6550d5c7efb45a8a805a3505942e6418411da584ee4e3e0.jpg)


## Example Multiple-Choice Questions

These are some example multiple-choice questions intended to give you an idea of how a calculus question might be asked in a multiple-choice format. These are not the “real exam questions with diferent numbers.” For each question, choose the one correct answer and fill in the bubble next to that answer, unless otherwise stated. 

## 34. If

$$
f (x) = \left\{ \begin{array}{l l} \frac {4 x ^ {2} - 4}{x - 1}, & x \neq 1, \\ 4, & x = 1, \end{array} \right.
$$

which of the following statements is (are) true? Select all that apply. 

![image](https://cdn-mineru.openxlab.org.cn/result/2026-10-27/1eaeb0ab-7f73-4b78-bbe3-c094feb83019/48eb5ad44ed7b9b8e53f6bcc6119bcdba8091e2332e1ab5978eb721b1d1ede37.jpg)


$\operatorname* { l i m } _ { x \to 1 } f ( x )$ exists. 

f is continuous at $x = 1$ 

f is diferentiable at $x = 1 .$ 

None of the above statements are true 

Solution: Check that 

$$
\lim _ {x \to 1} f (x) = \lim _ {x \to 1} \frac {4 (x + 1) (x - 1)}{x - 1} = \lim _ {x \to 1} 4 (x + 1) = 8.
$$

Thus the limit exists. However, $f ( 1 ) = 4 \neq 8 ,$ so $f$ is not continuous at $x = 1$ . Since diferentiability implies continuity, f is not diferentiable there. Therefore, only the first statement is true. 

## 35. If

$$
f (x) = \left\{ \begin{array}{l l} 3 x, & x <   0, \\ x ^ {2} + 3 x, & 0 \leq x \leq 1, \\ 4 x + 1, & x > 1, \end{array} \right.
$$

which of the following statements is (are) true? Select all that apply. 

![image](https://cdn-mineru.openxlab.org.cn/result/2026-10-27/1eaeb0ab-7f73-4b78-bbe3-c094feb83019/24d83067434e74bc8a02a4bcc30729347cad08a6cd1a2fee28eaebe5973ff96e.jpg)


f is diferentiable at $x = 0 .$ 

f is continuous at $x = 1$ 

f is diferentiable at $x = 1$ 

None of the above statements are true 

## Solution:

At $x \ = \ 0$ , both formulas give 0, and the one-sided derivatives are both 3, so f is diferentiable at $x = 0$ . At $x = 1$ , the middle formula gives 4, whereas the right-hand formula approaches 5. Thus f is discontinuous, and therefore not diferentiable, at $x = 1$ So only the first statement is true. 

## 36. If

$$
f (x) = \left\{ \begin{array}{l l} A x + B, & x <   2, \\ x ^ {2} + x + A, & x \geq 2, \end{array} \right.
$$

which pair of constants A and B makes f diferentiable at $x = 2 ?$ 

O $A = 5 , B = 0$ 

A = 2, B = 4 

O $A = 0 , B = 6$ 

None of the above 

## Solution:

Diferentiability requires matching derivatives and continuity. The left-hand slope is A, while the right-hand derivative at $x = 2$ is $2 ( 2 ) + 1 = 5$ , so $A = 5$ . Continuity then requires 

$$
2 A + B = 2 ^ {2} + 2 + A,
$$

which gives $1 0 + B = 1 1$ , so $B = 1$ . Therefore, none of the listed pairs are correct, so none of the above is the correct answer. 

For Questions 37–39, f and g are diferentiable functions with the values shown below. 

<table><tr><td>x</td><td>f</td><td>f&#x27;</td><td>g</td><td>g&#x27;</td></tr><tr><td>0</td><td>2</td><td>1</td><td>5</td><td>-4</td></tr><tr><td>1</td><td>3</td><td>2</td><td>3</td><td>-3</td></tr><tr><td>2</td><td>5</td><td>3</td><td>1</td><td>-2</td></tr><tr><td>3</td><td>10</td><td>4</td><td>0</td><td>-1</td></tr></table>

37. If $H ( x ) = { \sqrt { f ( x ) } }$ , then $H ^ { \prime } ( 3 ) =$ 

$$
\frac {1}{2 \sqrt {1 0}}
$$

$$
\frac {2}{\sqrt {1 0}}
$$

$$
4 \sqrt {1 0}
$$

Solution: By the chain rule, 

$$
H ^ {\prime} (x) = \frac {f ^ {\prime} (x)}{2 \sqrt {f (x)}}.
$$

Therefore, 

$$
H ^ {\prime} (3) = \frac {4}{2 \sqrt {1 0}} = \frac {2}{\sqrt {1 0}}.
$$

38. If $M ( x ) = f { \bigl ( } ( g ( x ) ) ^ { 2 } { \bigr ) }$ , then $M ^ { \prime } ( 2 ) =$ 4 −6 −8 10 Cannot be determined from the information given 

Solution: By the chain rule, $M ^ { \prime } ( x ) = f ^ { \prime } { \big ( } ( g ( x ) ) ^ { 2 } { \big ) } 2 g ( x ) g ^ { \prime } ( x ) .$ Hence $M ^ { \prime } ( 2 ) = f ^ { \prime } ( 1 ^ { 2 } ) \cdot 2 \cdot 1 \cdot ( - 2 ) = 2 \cdot 2 \cdot 1 \cdot ( - 2 ) = - 8 .$ 

39. If $S ( x ) = f ^ { - 1 } ( x )$ , then $S ^ { \prime } ( 3 )$ 二O −2O <sup>1</sup><sub>2</sub>O <sup>1</sup><sub>4</sub>O 2O − 1

Solution: Since $f ( 1 ) = 3 ,$ we have $f ^ { - 1 } ( 3 ) = 1$ . Therefore, $S ^ { \prime } ( 3 ) = \frac { 1 } { f ^ { \prime } ( f ^ { - 1 } ( 3 ) ) } = \frac { 1 } { f ^ { \prime } ( 1 ) } = \frac { 1 } { 2 } .$ 

40. If $s = { \sqrt { r + 1 } }$ and ${ \frac { d b } { d r } } = - 5 .$ , find $\frac { d b } { d s }$ when $r = 8 .$ −1/30 O −6/5 O −5/6 O 1/6 −30 

Solution: Since 

$$
{\frac {d s}{d r}} = {\frac {1}{2 \sqrt {r + 1}}},
$$

we have 

$$
{\frac {d b}{d s}} = {\frac {d b / d r}{d s / d r}} = {\frac {- 5}{1 / (2 \sqrt {r + 1})}} = - 1 0 \sqrt {r + 1}.
$$

At $r = 8 ,$ this equals $- 1 0 { \sqrt { 9 } } = - 3 0 .$ 

![image](https://cdn-mineru.openxlab.org.cn/result/2026-10-27/1eaeb0ab-7f73-4b78-bbe3-c094feb83019/7259d2ca20e950bd30b5d6a93fb02785942c635bbc8d5791db15a2f34a998c3d.jpg)


41. The graph above shows a function $y = f ( x )$ . At which of the following points is f not diferentiable? Select all that apply. 

x = 1 x = 2 x = 4 None of the above 

Solution: The function is discontinuous at x = 1 and $x = 4 ,$ so it cannot be diferentiable at either point. It has a corner at $x = 2$ , where the left-hand slope is 2 and the right-hand slope is $- \frac 1 2$ . Therefore, it is not diferentiable at all three of the listed points. 