% 
% Sophia Shokuri
% Assignment 2, Tilburg University



Introduction
================

Generational Economics Question 1
================

- Question 1: The "golden rule" is the level at which steady-state consumption is at a maximum, given the parameters of the model. Steady state consumption is?

--------------------------------------------------------------
Answer question 1
----------


	$$c^* = (1-s^*)\cdot f[k^*(s^*)] = f[k^*(s^*)]  - s^*f[k^*(s^*)]$$
    Where, $$ 0<s^*<1$$

---------------------------------------------------------
	We also have that, at the steady state where capital is constant
	$$s^*f[k^*(s^*)] = \delta k^*(s^*)$$

--------------------------------------------------------------------
	By substituting the optimal saving rate into the optimal consumption rate we get,
	$$\frac {\partial c^*}{\partial s^*} = f'[k^*(s^*)]\cdot \frac {{\rm d}k^*}{{\rm d}s^*} - \delta \frac {{\rm d}k^*}{{\rm d}s^*} =0$$
	$$ f'[k^*(s^*)]\ - \delta \big)\frac {{\rm d}k^*}{{\rm d}s^*} =0 \implies f'[k^*(s^*)] = \delta$$


-----------------------------------------------------------------------

Golden Rule: illustriation 
===============

-The figure shows the "Golden Rule" where consumption is maximized.

-------------------------------------------------------------
![](http://www.lidderdale.com/econ/311/gifs/Fig3-9.gif)
 
-----------------------------------------------------------------

Environmental Economics
=================

Emissions and Damages to the environment
-------------------------------------------------------------------

-We consider 2 emission sources $M_1$ and $M_2$ along with  three receptors $Q_1,Q_2,Q_3$ where the emissions are deposited and damage is generated. We also include $a_{ji}$, the fraction of emssion transfered from source $i$ to receptor $j$.  This is represented in vector matrix notation as $Q=AM$.

----------------------------------------------------------------------

 \newline Let $A = \begin{bmatrix} a_{11}, a_{12} \\[0.3em] a_{21},a_{22} \\[0.3em] a_{31},a_{32} \end{bmatrix} = \begin{bmatrix} \sqrt0.08, \sqrt0.08 \\[0.3em] 0.1,0.2 \\[0.3em] \sqrt0.285,0 \end{bmatrix}$. \newline
Let $B(M_i) = 6M_i-0.5M_{i}^2$,$D(Q_j)=0.5Q_{j}^2$ be Benefits of emissions and damage of depositions. Total damage is given by $TD = \sum_{j=1}^{3} D(Q_j)$.      
\subsection*{a)}Marginal benefits of $M_1$: $MB(M_1)=B'(M_1)=6-M_1$ \newline 
Total Marginal damage of emissions $M_1$: 

----------------------------------------------------------------------

\begin{equation} 
\begin{split} TD & =\sum_{j=1}^{3} 0.5Q_{j}^2  \\ & = \sum_{j=1}^{3} 0.5(a_{j1}M_1 + a{j2}M_2)^2 \\ &= 0.5(\sqrt0.08M_1 + \sqrt0.08M_2)^2 + 0.5(0.1M_1 + 0.2M_2)^2 + 0.5(\sqrt0.285M_1)^2 
\end{split}
\end{equation}
We take the partial derivative of $D(Q_j)$ for $j = 1,2,3$ with repect to $M_1$ by the application of the chain rule: \\'

-----------------------------------------------------------
\begin{equation}
\begin{split}
& \frac{\partial D(Q_1)}{\partial M_1} = 0.08M_1 + 0.08M_2
\\& \frac{\partial D(Q_2)}{\partial M_1} = 0.01M_1 + 0.02M_2
\\& \frac{\partial D(Q_3)}{\partial M_1} = 0.285M_1
\end{split}
\end{equation}

------------------------------------------------------------------
The final Answer
-----------------------------------------------------------------------
Total marginal damage is simply the sum of the above, so we have total marginal damage of $M_1$: $0.375M_1 + 0.1M_2$.

-------------------------------------------------


![](http://1.bp.blogspot.com/-RDo5BL14ptI/TwbF_pKLFDI/AAAAAAAAAjU/5EUPvgGaL-k/s1600/Pollution+in+China+smog.jpg)


