---
header-includes:
  - \usepackage[ruled,vlined,linesnumbered]{algorithm2e}
  - \usepackage{todonotes}
  - \usepackage{siunitx}
  - \usepackage[acronym]{glossaries}
---
\newacronym{hello}{HELLO}{Hi, how are you?}
# Acceptance test
This document exists to test that everything is installed, and compiles


## Todonotes
\todo[inline]{It is possible to write a todo note}

## Algorithm2e
\begin{algorithm}[H]
\DontPrintSemicolon
\SetAlgoLined
\KwResult{Write here the result}
\SetKwInOut{Input}{Input}\SetKwInOut{Output}{Output}
\Input{Write here the input}
\Output{Write here the output}
\BlankLine
\While{While condition}{
    instructions\;
    \eIf{condition}{
        instructions1\;
        instructions2\;
    }{
        instructions3\;
    }
}
\caption{While loop with If/Else condition}
\end{algorithm} 

## SI Unit X

\SI{123}{km/h}


## Glossaries
\acrfull{hello}
