---
language: latex
contributors:
    - ["Piotr Migdał", "http://migdal.wikidot.com"]
filename: learnLaTeX.tex
---

LaTeX [pronounced *lay-tek* or *lah-tek*]
is a document preparation system and document markup language.

It is commonly used in academia, especially in technical fields


```latex


\documentclass[12pt]{article}


% then load some packages
\usepackage[utf8]{inputenc}


% defining 
\newcommand{\braket}[2]{\langle #1 | \rangle}


% and another papameters



% And last not least, starting a document:
\begin{document}

% You may wish to make a title heading:
\maketitle



\section{Sections}

Sections work as above.

\subsection{A subsection}

\subsubsection{A subsubsection}


\section{Formatting}


You can have \textbf{bold face}, \bextit{itallics}
or \bextit{\textbf{both}}.

If you want to break line --- use\\
so you are in the next line!

Remember that and empty line creates a new paragraph.
If you want to avoid it,
%
%
it is not a problem, though.

You need to escape some special characters like \{, \} or \%,
and some other ones need a special command e.g. \textbackslash.

A non-breaking space is as here, Mr.~Freeman.


\section{Diacritics and symbols}


If you want to use non-latin characters, here is how it goes:

Żółć is Polish for bile.


\section{Lists}

List with bullets:

\begin{itemize}
  \item First element.
  \item Second element.
\end{itemize}

Enumerated list:

\begin{enumerate}
  \item Stuff.
  \item Another stuff.
\end{enumerate}


\section{Mathematical formulae}

One of things at which LaTeX shine is mathematical formulae.

For example, you may want to use $y = \sqrt{x}$.

Assuming that $x \geq 0$ and $a \in A$


\begin{align}
\frac{dx}{dt} &= x y\\
\frac{dy}{dt} &= x^2 + y^2
\end{align}




\section{General}

%\being{env}
%  ...
%\end{end}

{percent signs serve as comment.

A typical \commad[optional arguments]{arg1}{arg2}


\section{Floats, figures and tables}



\section{Labels, references and citations}

In scientific papers it common to reference to 





\end{document}
% and here document ended
```


# References and resources

* http://en.wikibooks.org/wiki/LaTeX
* http://tex.stackexchange.com/
* https://www.writelatex.com/ -> start a new document
* texample.net/tikz/examples/
* [The comprehensive LaTeX symbol list](http://osl.ugr.es/CTAN/info/symbols/comprehensive/symbols-a4.pdf)
* http://www.latextemplates.com/
