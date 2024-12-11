java c
Department of Mechanical and Industrial Engineering 
MIE1620: Linear Programming and Network Flows 
(Fall 2012) 
Quiz 2 
December   5,   2013
1.    (17   points)   Consider   the   uncapacitated   network   ﬂow   problem   shown   in   Figure   1.    The   label   next   to   each   arc   (in   boxes)   is   its   cost.    The   bold   numbers   beside   the   arrows   are   the   supplies/demands.      Consider the   spanning tree   indicated by the   dashed   arcs   in   the   ﬁgure   and   the   associated   basic   solution.
(a)    (4   points)   Determine   the   values   of the   arc   ﬂows   corresponding   to   this   basic   solu-   tion.   Is   the   solution   feasible?   Nondegenerate?
(b)    (3   points)   For   the   basic   solution   from   part   (a),   ﬁnd   the   reduced   cost   of   each   arc   in   the   network.
(c)    (4   points)   Determine   an   optimal   solution   to   the   network   ﬂow   problem.
(d)    (3 points)   By how much   can   we   decrease   c45      and   still   have   the   same   optimal   basic   feasible   solution?
(e)    (3   points)   If   we   increase   the   supply   at   node    1   and   the   demand   at   node   5   by   a   small   positive   amount   δ,   what   is   the   change   in   the   optimal   cost?

Figure   1:   Network   for   Problem   1
2.    (10   points)   Consider   two   nonempty   polyhedra   P   =   {x ∈   ℜn       | Ax ≤ b}   and   Q   =   {x ∈   ℜn         | Dx ≤ d}.      We   are   interested   in   ﬁnding   out   whether   the   two   polyhedra   have   a   point   in   common.(a)    (2   points)    Formulate   an   LP   problem   with   the   following   properties:    if   P   ∩   Q    is   nonempty, the LP returns   a   point   in   P   ∩   Q;   if P   ∩   Q   is   empty,   the   LP   is   infeasible.
(b)    (3   points)   Form   the   dual   of the   LP   from   part   (a).
(c)    (5   points)   Suppose   that   P   ∩   Q   empty.    Use   the   dual   from   part    (b)   to   show   that   there   exists   a   vector c such   that c′x < c′ y for   all x ∈   P   and y ∈   Q.
3.    (6   points;   3   points   each)   Consider   a   linear   program代 写MIE1620: Linear Programming and Network Flows (Fall 2012) Quiz 2Web
代做程序编程语言ming   problem   of the   form.

(a)    Form   the   dual   of the   problem.(b)    Explain   how   Dantzig-Wolfe   decomposition   can   be   applied   to   the   dual.   It   is   suﬃ-   cient to provide a few sentences to identify the coupling   constraint   and to   describe   the   constraints   of the   subproblems   solved   during   a   typical   iteration   is   suﬃcient.
4.    (9    points)    Consider      a   transportation      problem   with   two      source      nodes    s1   ,    s2   ,    and    n   demand   nodes   1, . . . ,   n.    All   arcs   of   the   form   (si   ,   j),   i   =   1, 2;   j   =   1, . . .   ,   n   are   assumed to be present and to   have   inﬁnite   capacity.    Let   D   =Σ di    be the total   demand.    Let   the   supply   at   each   source   node   be   equal   to   D/2.   Assume   that   di    > 0   for   all   i.
(a)    (3 points) Draw a ﬁgure representing the   network   ﬂow   problem.    Include all nodes,   arcs,   supply   and   demand   arrows,   etc.
(b)    (2   points)   How   many   basic   variables   are   there   in   a   basic   feasible   solution   for   this   network?
(c)    (4   points)   Show   that   there   exists   a   degenerate   basic   feasible   solution   if   and   only   if   there   exists   some   set   S   ⊂   {1, . . . ,   n}   such   that Σi∈S   di      = D/2.
5.    (8   points)   Consider   the   following   LP
Supposex(ˆ) is a feasible solution to formulation   (1).    Now consider an inverse formulation   to   formulation   (1),   which   we   assume   to   be   feasible:

We   wish   to   understand   the   structure   of optimal   solutions   to   formulation   (2).
(a)    (2   points)   Prove   that   formulation   (2)   has   an   optimal   solution.
(b)    (3   points)   Determine   if p = 0 can   be   a   part   of   any   feasible   solution    (c, p,   ϵ)   to   formulation   (2).
(c)    (3   points)   If   at   an   optimal   solution   (c*   , p*   ,   ϵ*   ),   the   constraint A(x(ˆ) − ϵ* e)   ≥ b is
satisﬁed,   show   that   there   must   exist   some   i   such   that ai(′)(x(ˆ) − ϵ* e) − bi    = 0.

         
加QQ：99515681  WX：codinghelp  Email: 99515681@qq.com
