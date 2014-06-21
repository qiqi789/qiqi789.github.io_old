---
title: mathjax displays latex on web page
description: mathjax, pandoc, and hakyll
tags: latex, math
---

[MathJax] is one of the tools for math writing for web pages.

[MathJax]: http://www.mathjax.org/docs/1.1/start.html#putting-mathematics-in-a-web-page

An example is below:

When $a \ne 0$, there are two solutions to $ax^2 + bx + c = 0$ and they are
$x = {-b \pm \sqrt{b^2-4ac} \over 2a }$.

    $\alpha, \beta, \phi, \Phi, \delta, \Delta \sum{\mathcal{A}_{i}}$

$\alpha, \beta, \phi, \Phi, \delta, \Delta \sum{\mathcal{A}_{i}}$

$$\alpha$$

$ \\alpha $

$\begin{aligned}
\dot{x} & = \sigma(y-x) \\
\dot{y} & = \rho x - y - xz \\
\dot{z} & = -\beta z + xy
\end{aligned}$

\newcommand{\abs}[1]{\lvert#1\rvert}
$\begin{equation}
\label{eq:jointGaussian} 
P(\mathcal{X}_{\mathcal{V}}=\mathrm{x}_{\mathcal{V}})=\frac{1}{(2\pi)^{n/2}\abs{\Sigma_{\mathcal{VV}}}^{1/2}} e^{-\frac{1}{2}(\mathrm{x}_{\mathcal{V}}-\mu_{\mathcal{V}})^{T}\Sigma_{\mathcal{VV}}^{-1}(\mathrm{x}_{\mathcal{V}}-\mu_{\mathcal{V}})}
\end{equation}$

+-----+-----+
|a    |b    |
+-----+-----+
|c    |d    |
+-----+-----+




<table>
    <tr>
        <td>*one*</td>
        <td>[a link](http://google.com)</td>
    </tr>
</table>

~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ {.haskell .numberLines}
qsort []     = []
qsort (x:xs) = qsort (filter (< x) xs) ++ [x] ++
               qsort (filter (>= x) xs) 
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
