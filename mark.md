### 6.1
#### (3) 
$ e^{-t}[u(t)-u(t-2)] $
$ =e^{-t}u(t)-e^{-2}[e^{-(t-2)}u(t-2)] $ 
$ \rightarrow  {1 \over s+1} + {e^{-2-2s} \over s+1 } $
#### (5)
$ (1+2t)e^{-t}u(t) $
$ =e^{-t}u(t)+2te^{-t}u(t) $
$ \rightarrow {1 \over s+1} -2{d \over ds}({1 \over s+1}) $
$ ={1 \over s+1}+2{1 \over (s+1)^2} $
#### (9)
$ (t-1)[u(t-1)-u(t-2)] $
$ =(t-1)u(t-1)-(t-2)u(t-2)-u(t-2) $
$ \rightarrow {1 \over s^2}e^{-s} - {1 \over s^2}e^{-2s} - {1 \over s}e^{-2s} $ 
#### (10)
$ e^{-t}sin2t \cdot u(t) $
$ \rightarrow {2 \over {(s+1)}^2+4} $
#### (14)
$ t^2u(t-1) $
$ = (t-1)^2u(t-1)+2(t-1)u(t-1)+u(t-1) $
$ \rightarrow  {2e^{-s} \over s^3} + {e^{-s} \over s^2} +{e^{-s} \over s}$
#### (16)
$ e^{-(t+a)}cos(wt)u(t) $
$ \rightarrow e^{-a} \cdot {s+1 \over (s+1)^2+w^2} $
#### (21)
$ \delta^{\prime}(t) $
$ \rightarrow sF(s)-\delta(0) $
$ = s-\delta(0) $
$ t \delta^{\prime}(t) $
$ \rightarrow {d \over ds}[s-\delta(0)] $
$ = 1 $
### 6.2
$ e^{-at}f({t \over a}) $
$ =e^{-a^2 \cdot {t \over a}} f({t \over a}) $ 
$ \rightarrow aF(as+a^2) $
### 6.4
#### (2)
$ cos(w_0t)={ e^{jw_0t}+e^{-iw_0t} \over 2} $
$ f(t) \cdot cos(w_0t) $
$ = {F(s -jw_0)+F(s+jw_0) \over 2} $
$ = {1 \over 2} [{1 \over (s-jw_0)^2+2(s-jw_0)+5} + {1 \over (s+jw_0)^2+2(s+jw_0)+5}] $
#### (3)
$ f[2(t-2)] $
$ \rightarrow {1 \over 2}F({s \over 2})e^{-2s} $
$ = {2 \over s^2+4s+20} \cdot e^{-2s} $