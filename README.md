# Little-o

In addition to the big-O, big-$\Omega$, and big-$\Theta$ notation that
we covered at the beginning of this class, a few other notations are sometimes
used in asymptotic analysis.  For example, "little-$o$" notation.

Prove (i.e.\ give a formal mathematical proof) that $f(n)\in o(g(n))$ implies
that $f(n)\in O(g(n))$.

Hint: The proof will be *very* short and *very* easy. You can start by
identifying the differences between the definitions of O and o.

I have started with the formal definition of $o$ below. Add your answer to this
markdown file. [This
page](https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/writing-mathematical-expressions)
might help with the notation for mathematical expressions.

$f(n)\in o(g(n)) \iff \forall c>0, \exists n_0, \forall n\ge n_0: f(n) < c g(n)$


Definitions:

$f(n)\in o(g(n)) \iff \forall c>0, \exists n_0, \forall n\ge n_0: f(n) < c g(n)$
$f(n)\in O(g(n)) \iff \exists c,n_0 > 0, \forall n\ge n_0: f(n) \le c g(n)$

The differences between the two definitions is that within big-O there is a constant "c" meaning that only one constant needs to pre present in order for the f(n) to be within big-O. Whereas in little-o it is all constants "c" there is not the acception that big-O has. The notation in Little-O it is $\forall c>0$, whereas in Big-O it only uses $\exists c>0$. Another difference is the inequalities involved in the two notations. Little-O's inequality indicates that $g(n)$ will grow faster than $f(n)$. Big-O's inequality implies that $f(n)$ will grow, at most, as fast as $g(n)$. The difference in the inequaity shows that little o is more strict than big O so therefore $f(n)\in o(g(n))$ implies that $f(n)\in O(g(n))$.

Needed Google for the definitions adn references geeksforgeeks on Big-O and little-o behavior.
https://www.geeksforgeeks.org/analysis-algorithms-big-o-analysis/#definition-of-bigo-notation
https://www.geeksforgeeks.org/analysis-of-algorithems-little-o-and-little-omega-notations/

I certify that I have listed all sources used to complete this exercise, including the use
of any Large Language Models. All of the work is my own, except where stated
otherwise. I am aware that plagiarism carries severe penalties and that if plagiarism is
suspected, charges may be filed against me without prior notice.
