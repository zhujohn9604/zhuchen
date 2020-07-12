---
layout: post
title:  "The Dirichlet distribution"
date:   2020-07-12 14:36:24 +0900
category: PRML
---
This blog is going to recap and fresh some essential concepts of the Dirichlet distribution. The Dirichlet distribution has been widely used in text mining, for example, topic modeling. Its form comes from by considering the conjugate prior of the multinomial distribution.
\begin{equation}
p(\mathbb{\mu}|\alpha) = \prod_{k=1}^{K} \mu_{k}^{\alpha_k -1}
\end{equation}