# Hello there...

This file serves as a reference page for certain LaTeX features in case you forget, which you most likely will.

## Inserting Code Snippets

To insert code snippets, you first need to type the following: `\usepackage{listings}`. Then you can use the `\begin{lstlisting}` and `\end{lstlisting}`. You can also do `\begin{lstlisting}[language=Python]` to add some code highlighting (only boldface) for the Python language (can change this to any language).

## Inserting Images

Here is a self-explanatory example of how to insert an image into a LaTeX document:

```
\documentclass{article}
\usepackage{graphicx}
\graphicspath{ {PATH} }

\begin{document}
The universe is immense and it seems to be homogeneous,
in a large scale, everywhere we look at.

\begin{figure}
\includegraphics{universe}
\centering
\end{figure}

There's a picture of a galaxy above
\end{document}
```

# Creating Lists

Here is a self-explanatory example of how to create a list:

```
\begin{itemize}
    \item Descriptive Statistics - seeks to summarize and display data in a meaningful way
    \item Inferential Statistics - makes predicitions about large collections of data using various methods
\end{itemize}
```
