java c
Statistical Methods and Data Analytics 
MATH0099 
MSc Examination 
2022
Problem 1. 
(a)    [7   points]       Let    θ    ∈   R   and   let   X   be   a   random   variable   with   density   pθ (x).   The   corresponding   log-likelihood   is   lx   (θ)   := log   pθ (x).
The   ﬁrst   and   the   second   derivative   of the   log-likelihood   are

Compute   the   expectation   of   l and   l,      and   show   that   the   latter   is   equal   to
-Iθ , where

is   the   Fisher   information.
Note:    you   may   assume   that   the    operation   of   changing   the   order   of   di      eren-   tiation   and   integration   is   valid.
(b)    [12   points]       Let X =   (X1, . . . ,   Xn   )   and   assume   that   the   Xi    are   iid   copies   of the   random   variable   X   from   (a).    Let   lx (θ)   denote   the   log-likelihood   based
on   the   full   sample X and   θ(ˆ)   the   corresponding   maximum   likelihood   estimator
(MLE)   .
(i)   Write   down   a   ﬁrst-order   Taylor   series   expansion   for   lx,   (θ(ˆ))   at   θ   and   use
it   to   obtain   an   approximation   for   θ(ˆ).
(ii)   Using   the   central   limit   theorem   and   the   strong   law   of   large   numbers,   show   that   in   large   samples   the   MLE   is   approximately   normally   dis-   tributed.   Speciﬁcally,

Note:      The   notation ~ means ‘approximately distributed’.
Note:       You    may    assume    that    the      assumptions      underlying    the      central    limit   theorem   and   the   law   of large   numbers    are   met.
(c)    [6   points]       In   the   setting   of   (b)   with   X   ~ N(θ,   σ2   )   and   σ   known,   compute
the   MLE   θ(ˆ)   and ﬁnd its   approximate   distribution.
Problem 2. (a)    [8 points]    Studies have   shown   that   1/3   of twin   births   are   identical twins   and   2/3   are   fraternal   twins.    A   mathematician   ﬁnds   out   that   she   will   have   twin girls   and   would   like   to   know   the   probability   that   the   girls   are   identical   twins.Using   the   information   above   write   down   a   suitable   prior   distribution   and   a suitable   family   of   (discrete)   probability   densities   to   answer   the   mathemati-   cian’s   question.   What   is   the   probability   that   the   twins   are   identical?
Note:      you   may   assume   that   the    chance    of fraternal   twins   having   the   same   sex   is   1/2   .
(b)    [10 points]    Let   the   random   variable   X   represent   the   number   of claims   made   in   a single year by an   insurance   policy   holder.    Assume that X   ~   Poisson(θ),   that   is

and   that   g(θ)   is   a   prior   for   θ   .
Find a formula forθ(ˆ), the Bayes estimator for θ, only involving x   and   f   , where
f   is the   marginal   density   of   X   .
(c)    [7 points]    In 代 写MATH0099 Statistical Methods and Data Analytics MSc Examination 2022
代做程序编程语言  the   setting   of   (b),let   X1   , . . . ,   Xn      be   iid   copies   of   X, so   that   now there   are   n   policy   holders.      Explain   how   you   would   estimate   the   marginal density   f   and   hence   write   down   an   empirical   version   of   the   formula   for   θ(ˆ), which   you   obtained   in   (b).Problem 3. Let X =   (X1, . . . ,   Xn   )   and   assume   that   the   Xi         are   iid   copies   of a   random   variable   X      ~   Bernoulli(p).    Deﬁne   T      := Σ Xi   , the   total   number   of successes in the   sample.
(a)   [8 points]    Show that T   is a sufficient   and   complete   statistic.
(b)   [12 points]    Let q   := 1 -   p.   Find δ, the UMVU estimator for pq.
(c)   [5 points]    Given   the variance of the estimator   δ   you   found   in   (b),

show that the estimator is consistent.
Problem 4. 
(a)    [6 points]    For each statement below decide whether   it   is true   or   false.    Justify   your   answer.
(i)   The   p-value   of   a   test   is   the   probability   of   a   type   I   error.
(ii)   The   type   II   error   of   a   testis   one   minus   the   probability   of   falsely   rejecting the   null   hypothesis.
(iii)   The   p-value   of   a   test   has   a   Uniform   distribution   on   (0, 1).
(b)    [8   points]      Let   X   be   a   random   variable   with   probability   mass   function   pθ =   pθ (x).    The   null   hypothesis   is   θ    =   θ0   ,   the   alternative   is   θ   =   θ   1   .    Under   the   null   hypothesis   and   the   alternative, pθ is   speciﬁed   as   follows:x                  1                  2                  3                  4                  5                  6                  7pθ0                         .01            .01            .01            .01            .01            .01            .94pθ1                         .06            .05            .04            .03            .02            .01            .79
(i)    Use   the   Neyman-Pearson   Lemma   to   ﬁnd   the   most   powerful   test   ϕ   of
the   null   hypothesis   against   the   alternative   such   that   Eθ0   (ϕ) =   .04.
(ii)    Compute   the   probability   of   a   Type   II   error   for   the   above   test.
(c)    [11   points]       Let X =   (X1, . . . ,   Xn   )   and   assume   that   the   Xi    are   iid   copies   of   a   random   variable   X   ~ N(θ,   σ2   ),   with   σ   2    known.    The   null   hypothesis   and the   alternative   are
H0      :   θ   ≤   0,            and          H1      :   θ   >   0.
Consider   the   family   of   tests   given   by

where X denotes the   sample   mean   of X and   c   ∈ R   parameterises the   family.
Compute   β(θ)   :=   Eθ [ϕ],   the   power   function   of   the   family   of   tests   and   con- struct   a   test   with   signiﬁcance   level   Q.





         
加QQ：99515681  WX：codinghelp  Email: 99515681@qq.com
