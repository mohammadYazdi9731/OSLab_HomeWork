create file project in www.overleaf.com

Add required packages:

\documentclass{article}
\usepackage[utf8]{inputenc}
\usepackage{graphicx}
\usepackage{listings}
\usepackage{setspace}
\usepackage{amsmath}

Title:

\title{OSLab HomeWork}

Text:

\section{Text}
\text{This is HomeWork 9}

Image:

\section{Image}
\begin{center}

    \includegraphics[scale=0.8]{latex.jpg}
\end{center}
    

Table:

\section{Table}

    \begin{tabular}{|c|c|c|}
    
    \hline
         first name & last name & id \\
    \hline
        Mohammad & Yazdi & 97440225 \\
    \hline     
        
    \end{tabular}

Formulas:

\section{Formulas}

\begin{left}

 \log xy = \log x + \log y
 
\end{left}

Code:

\section{Code}

\lstset{language = c++}
\begin{lstlisting}
#include<iostream>
using namespace std;

int main()
{
cout<<"Mohammad Yazdi";
system("pause>A");
}






