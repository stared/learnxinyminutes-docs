---
language: latex
contributors:
    - ["Piotr Migdał", "http://migdal.wikidot.com"]
filename: learnlatex.tex
---



# Installing


# Document structure

```latex
\documentclass{article}

\begin{document}
  ...
\end{document}
```



# Section

    \section{}
    \subsection{}
    \subsubsection{}


# Formatting

    You can have \textbf{bold face}, \bextit{itallics}
    or \bextit{\textbf{both}}.

    If you want to break line --- use\\
    so you are in the next line!

    You need to escape some special characters like \{, \} or \%,
    and some other ones need a special command e.g. \textbackslash.

    Mr.~Freeman, 

If you need more break between lines
...


If you want to use non-latin characters,
   Żółć is Polish word for bile. is /ż/Ł

# Lists

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


# Mathematical formulae

One of things at which LaTeX shine is mathematical formulae.



    Assuming that $x \geq 0$ and $a \in A$


    \begin{align}
    \frac{dx}{dt} &= x y\\
    \frac{dy}{dt} &= x^2 + y^2
    \end{align}


# General

    \being{env}
      ...
    \end{end}

    % percent signs serve as comments

A typical \commad[optional arguments]{arg1}{arg2}


# Floats, figures and tables

# Labels, references and citations





# Comments, packages


# References

* http://en.wikibooks.org/wiki/LaTeX
* http://tex.stackexchange.com/
* https://www.writelatex.com/ -> start a new document
* texample.net/tikz/examples/
* [The comprehensive LaTeX symbol list](http://osl.ugr.es/CTAN/info/symbols/comprehensive/symbols-a4.pdf)
