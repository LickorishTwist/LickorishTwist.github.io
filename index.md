---
layout: default  # Uses your default layout (includes navbar)
title: Home      # Page title
mathjax: true    # Enable MathJax for LaTeX
---

# Welcome to My Website!

This is hosted on GitHub Pages. 🚀  

Here’s some stuff from my honours thesis:  

# Conjecture
The polynomial \\(H_{g,n}^{bt}(\mu_1,\dots,\mu_2)\\) interlaces each of the \\(n\\) polynomials
\\[H_{g,n}^{bt}(\mu_1+1\dots,\mu_2),\dots, H_{g,n}^{bt}(\mu_1,\dots,\mu_n+1)\\]

Where the polynomials \\(H_{g,n}^{bt}(\mu_1,\dots,\mu_2)\\) are defined by the following recursion with the base case \\(H_{0,1}^{bt}(1)=1\\). 
<div class="math-container">

\begin{aligned}
\mu_1 H_{g,n}^{tb}(\mu) &= (1+b)\sum_{i=2}^n(\mu_1+\mu_i,\mu_{S\setminus\{i\}})\\
&\quad +\sum_{\alpha+\beta = \mu_1}\alpha\beta\left[ H_{g-1,n+1}^{bt}(\alpha,\beta,\mu_S)+\sum_{\substack{g_1+g_2 = g \\ I_1\sqcup I_2 = S}} H_{g_1,|I_1|+1}^{bt}(\alpha,\mu_{I_1})H_{g_2,|I_2|+1}^{bt}(\beta,\mu_{I_2})\right]\\
&\quad + b\mu_1(\mu_1) H_{g-1/2,n}^{bt}(\mu_1,\mu_S)\\
&\quad +(t-1)(\mu_1-1) H_{g,n}^{bt}(\mu_1-1,\mu_S)
\end{aligned}
</div>
Where \\(S = \{2,\dots,n\}\\) and \\(g_1,g_2,g\in\frac{1}{2}\mathbb{Z}\\). 

We know this to be true for \\(b = 0, t = 1, g = 0, n =1\\) as this recursion recovers a known recursion for the sequence of Narayana polynomials, which are known to be interlacing. 


[About Me](about)  <!-- Jekyll automatically handles links -->
