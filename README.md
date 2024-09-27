java c
Problem set 4 
Advanced   Microeconomics, 
Ec   992,   Spring   2024 
Extensive form games and subgame perfection II 
[and Nash bargaining (optional)] 
1.    Exercise   9.B.11   of the   MWG   textbook.
2.   Exercise   9.B.13   of   the   MWG   textbook.    (Note:   you   should   try   to   find   /   charac-   terize   at   least   one   subgame   perfect   Nash   equilibrium.)
3.    Consider   the   following   variation   of   the   infinite   horizon   alternating   offers   bar-   gaining   game   discussed   in the   lecture.    Suppose   δ   =   1.   In   any   period,   if an   offer   is rejected, the game terminates with probability   α   ∈   (0, 1).    For Player   i   =   1,   2,   let   ui   (xi   )   denote   the   Bernoulli   utility   from   payoff   xi      and   let   bi      ∈   [ui   (0),   ui   (1)]   denote   the   Bernoulli   utility   in   the   event   of   a   termination.    Assume   that   ui       is   strictly   increasing   and   concave   in   xi.   Let   (ˆ(x)1   ,   ˆ(x)2   )   and   (ˆ(y)1   ,   yˆ2   )   satisfy
u1   (ˆ(y)1   ) = αb1    + (1 − α)u1   (ˆ(x)1   )
u2   (ˆ(x)2   ) = αb2    + (1 − α)u2   (ˆ(y)2   )
where   bi ≤ ui   (ˆ(x)i   )   and   bi ≤ ui   (ˆ(y)i   ),   i   =   1,   2.      Does   the   strategy   profile   (σ1(*),σ2(*))   below   constitute   a   subgame   perfect   equilibrium?   Explain   your   answer.
● σ 1(*):   Player   1   always   offers   (ˆ(x)1   ,   ˆ(x)2   )   and   accepts   an   offer   (y1   ,   y2   )   if   and   only if   y1 ≥ ˆ(y)1   .
● σ2(*):    Player   2   always   offers   (ˆ(y)1   , yˆ2   )   and   accepts   an   offer   (y1   ,   y2   )   if   and   only if   y2 ≥ ˆ(x)2   .
4.    Exercise   12.D.1   of the   MWG   textbook.
(Erratum: “...the market ceases to exist with probability 1 − γ.”) 
5. Exercise 12.D.3 of the MWG textbook. 
(Erratum: “...with q ∈ [4b/a−c, 3b/a−c) are sustainable... ...δ(q) is a decreasing, differentiable function of q...) 
6.    Exercise   12.D.5   of the   MWG   textbook.
7.   Table   1   depicts   the   payoff   matrix   with   payoff   parameter   y   >   0   of   a   two-player   game   where   Player   1   chooses   the   row   A   or   B   and   Player   2   chooses   the   column   A or   B   .    Suppose this   is   a   stage game which   is repeated   infinitely.    Let   δ   ∈   (0, 1)   denote   the   common   discount   factor   for   the   players.    For   what   values   of   δ      can   the   action   profile   (A,   A)   be   sustained   in   a   subgame   perfect   Nash   equilibrium   of   the   infinitely   repeated   game   with   a   strategy   profile   that   calls   for   (A,   A)   to   be played   in   period   1   and   thereafter   if   neither   player   has   yet   deviated   and   for   a   stage-game   Nash   equilibrium   to   be   played   otherwise?   Explain.

A 
B 
A 
1 1 
−1, 1 + y 
B 
1 + y, −1 
0, 0 
Table   1:   Stage   game.   Payoff parameter   y   > 0.
8.    Consider   the   following   infinite-horizon   game   between   one    (long-lived)    player   labeled F who is present in   every   period   and   a   sequence   of   (short-lived)   players,   each   of whom   lives   for   one   period   only.    Periods   and   the   short-lived   players   are   both   indexed   by   t =   1,   2, ....Within   each   period,   the   short-lived   player   first   chooses   between   actions   e   and   ne.    Player   F   observes   the   choice   of   action   by   the   short-lived   player   and   then   chooses   an   action   w    ∈    R+   .      If   the   short-lived   player   chooses   e   and   player   F   chooses   w,   then   the   payoff   to   the   short-lived   player   is   w   − c,   where   c   >   0   and   the   payoff   to   F   is   y   − w,   where   y   >   c   >   0.    If the   short-lived   player   choose   ne   and   player   F   chooses   w   then   the   payoff   to   the   short-lived   player   is   w   and   the   payoff   to   F   is   −w.In   the   infinite-horizon   problem,   at   the   beginning   of   each   period   t,   the   history of   the   game   through   to   period   t − 1   is   observed   by   the   short-lived   player   who   plays   in   period   t   and   by   F.   Let   the   disco代 写Ec 992 Spring 2024 Advanced Microeconomics Problem set 4
代做程序编程语言unt   factor   of   F   be   δ   ∈   (0, 1).
(a)    Consider the game within each period between F and the short-lived player   of   that   period.       What      is      the   subgame-perfect   equilibrium   of   this      (one-   period)   game?   Explain.
(b)    Consider   the   infinite-horizon   problem.       For   what   values   of   δ    does   there   exist   a   sub-game   perfect   equilibrium   of   the   infinite-horizon   game   where   the   short-lived   player   in   each   period   chooses   e?   Explain.
9.    Consider   the   following   two-player   repeated   game   with   periods   indexed   by   t   =   1, 2, 3, . . .   and   a   common   discount   factor   δ   ∈   (0,   1).    The   stage   game   action   set   Ai    is   finite   for   each   player   i   =   1,   2   and   for   any   action   profile   a   =   (a1   ,   a2   ),   ui   (a)   denotes   player   i’s   payoff   in   the   stage   game.    For   player   i   =    1,   2,   let ui       denote   the   (stage   game)   minmax payoff,   which   is   defined   as   follows   with j  i.ui      = a i j         [a(m)i i   ui   (a)]                                                                                                                        (1)Denote   by   ˆ(a)j      the   action   of   player   j   which   solves   the   minimisation   problem   in (1),   i.e.      the   action   that   holds   player   i   down   to   their   minmax   payoff ui.      Letˆ(a)   =      (ˆ(a)1   ,   ˆ(a)2   )   denote   the   punishment   action   profile.      Note   that   ui   (ˆ(a))   need   not   be   equal   to   ˆ(u)i.   Additionally,   let   ¯(u)i    denote   the   highest   payoff that   player   i   can   obtain   in   the   stage   game.
Let   a*    =   (a1(*),   a2(*))   be   such   that   ui   (a*   )   > ui      for   all   i   =   1,   2.
Consider   the   strategy   profile   s   =   (s1   , s2   )   in   the   repeated   game   which   is   com-   prised   as   follows.   Let   K   ≥   1.Player i chooses ai(*)   in t   =   1 and   every   period thereafter   if the   outcome   of t − 1   is   a*   ; otherwise   player   i   chooses   ˆ(a)i.    If   the   outcome   in   each   of   t−1,   t − 2, . . . ,   t−K   is   ˆ(a)   then   player   i   chooses   ai(*)   in   t.      If   the   outcome   in   t − 1   is    (ˆ(a)i   ,aj   ),   where   aj  ˆ(a)j   ,   then   player   i   chooses   ˆ(a)i      for   K   periods.
(a)    Suppose   t   =   1   or   the   outcome   of   t − 1   is   a*   .      Provide   an   expression   (in-   equality) involving δ, ui   (a*   ),   ¯(u)i   ,   ui   (ˆ(a)),K   such   that   it   is   optimal   for   player   i to   follow   the   strategy   si.
(b)    Suppose   the   outcome   of   each   of   t   − ℓ   is   ˆ(a),   where    1    ≤   ℓ    ≤   K.      Provide an   expression      (inequality)   involving   δ,   ui   (a*   ), ui   ,   ui   (ˆ(a)),K      such   that   it   is optimal   for   player   i to   follow   si.
(c)    Given    the    expressions    obtained    above,    does    there    exist    a    value δ < 1 such that for any δ > δ the   strategy   profile   s   is   a   subgame   perfect   Nash   equilibrium   of   the   repeated   game   for   some   value   of   K?       Explain    your   answer.
10.    (Optional exercise on Nash   Bargaining)   Formulate   the   following   as   a   Nash   Bar-   gaining   problem   and   characterize   the   symmetric   Nash   Bargaining   solution.    A   union   V   representing   L   >   0   workers   bargains   with   a   firm   F.    Each   worker   can   obtain   w0    ≥ 0   if not   employed   by   the   firm.    If the   firm   hires   ℓ   ∈   [0,   L]   workers,   it   produces   output   f(ℓ),   where   f′ >   0,   f′′ < 0 with f(0) = 0 and f(ℓ) ≥ ℓw0 for   some   ℓ   ∈   [0,   L].    An   agreement   is   a   wage   employment   pair   (w,ℓ)   such   that   w0       ≤   w    ≤    f(ℓ)/ℓ   with   utility   to   F   given   by   f(ℓ)   − ℓw   and   to   V   given   by ℓw + (L −   ℓ)w0   . Disagreement   means that   F   gets   0   and   U   gets   Lw0   .    Note that   Pareto   efficiency   requires   that   the   choice   of   ℓ   maximizes   the   sum   of   the   firm   and   union   utilities. 






         
加QQ：99515681  WX：codinghelp
