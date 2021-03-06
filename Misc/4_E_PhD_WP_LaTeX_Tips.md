# Writing Paper - LaTeX Tips

## Introduction

1. Clearly list the contributions (Ideally on the first page).

   Example

   ```LaTeX
    \noindgras{Contributions:}
    \begin{itemize}
      \item we design a X platform for Y devices;
      \item we demonstrate its relative performance gain compared to Z;
      \item we demonstrate the practicality of the approach by building an XX;
      \item finally, we propose an open-source implementation of the work presented in this paper.
    \end{itemize}
   ```

2. Provide the structure of the paper (Ideally on the first page)

   Example

   ```LaTeX
   The remainder of this paper is organised as follows: \autoref{sec:background} provides a technical background.
   \autoref{sec:implementation} describes the implementation of system.
   \autoref{sec:evaluation} provides an evaluation by comparing its X, Y, Z with an alternative.
   \autoref{sec:usecase} demonstrates XX by applying it to a real use case.
   \autoref{sec:related_work} performs a comparison of current system to XX and discusses related work in the fields of YY, ZZ.
   ```

## Diagrams

1. Legends in the graph can be inside the figure to save spaces. (Assuming, your diagrams are made in PGFPlot).

## Bibliography

1. Probably, Bibliography should only contain journal, conference papers, technical reports; it should not contain much URLs. URLs should be in the footnotes. However, this differs from supervisors to supervisors. Kindly ask your supervisor whether they would like URLs in the footnote or in the Bibliography.

## LaTeX redefinitions

- Re-define Figure to Fig, and section to $

  ```LaTeX
  %%  
  \newcommand{\noindgras}[1]{{\noindent \textbf{#1}}}
  %%
  \renewcommand{\figureautorefname}{Fig.}
  \newcommand{\subfigureautorefname}{Fig.}
  \renewcommand{\tableautorefname}{Table}
  \renewcommand{\sectionautorefname}{\S}
  \renewcommand{\subsectionautorefname}{\S}
  \renewcommand{\subsubsectionautorefname}{\S}
  \providecommand*{\lstlistingautorefname}{Listing}
  ```

- Sometimes, the paper is not meeting the length of the conference paper limit, in that case, we can do the below:

  ```LaTeX
  \renewcommand{\baselinestretch}{0.925}
  ```
