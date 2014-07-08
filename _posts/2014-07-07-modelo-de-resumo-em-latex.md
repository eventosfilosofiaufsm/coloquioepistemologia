---
layout: post
title: "Modelo de resumo em Latex"
modified: 2014-07-07 21:30:00 -0300
category: []
tags: []
image:
  feature: 
  credit: 
  creditlink: 
comments: 
share: 
---


{% highlight latex %}
{% raw %}
\documentclass[12pt,a4paper]{article}
\usepackage[T1]{fontenc}
\usepackage[a4paper]{geometry}
\usepackage[portuges,brazilian]{babel}
\usepackage[utf8]{inputenc}
\usepackage{setspace}
\usepackage{libertine}


\title{Título do resumo}
\author{Fulano de Tal\thanks{email@servidor.com. Universidade Federal de Santa Maria - UFSM. Área específica.}}


\begin{document}
\maketitle
\pagenumbering{gobble}
\singlespacing

Início do texto...




\begin{thebibliography}{BIBLIOGRAFIA}

\bibitem{1} KANT, Immanuel. \textbf{Crítica da Razão Pura}. Tradução de Manuela Pinto dos Santos e Alexandre Fradique Morujão. 7. ed. Lisboa: Fundação Calouste Gulbenkian, 2010.

\end{thebibliography}

\end{document}
{% endraw %}
{% endhighlight %}
