# Hello there...

This file serves as a reference page for certain LaTeX features in case you forget, which you most likely will.

## Inserting Code Snippets

To insert code snippets, you first need to type the following: `\usepackage{listings}`. Then you can use the `\begin{lstlisting}` and `\end{lstlisting}`. You can also do `\begin{lstlisting}[language=Python]` to add some code highlighting (only boldface) for the Python language (can change this to any language).

# Creating Lists

Here is a self-explanatory example of how to create a list:

```
\begin{itemize}
    \item Descriptive Statistics - seeks to summarize and display data in a meaningful way
    \item Inferential Statistics - makes predicitions about large collections of data using various methods
\end{itemize}
```
