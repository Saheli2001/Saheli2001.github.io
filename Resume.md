\documentclass[10pt,article]{article}
\usepackage[letterpaper,margin=0.3in]{geometry}
\usepackage{graphicx}
\usepackage{booktabs}
\usepackage{url}
\usepackage{enumitem}
\usepackage{palatino}
\usepackage{tabularx}
\fontfamily{SansSerif}
\selectfont

\usepackage[T1]{fontenc}
\usepackage
%[ansinew]
[utf8]
{inputenc}

\usepackage{color}
\definecolor{mygrey}{gray}{0.82}
\textheight=9.75in
\raggedbottom

\setlength{\tabcolsep}{0in}
\newcommand{\isep}{-2 pt}
\newcommand{\lsep}{-0.5cm}
\newcommand{\psep}{-0.6cm}
\renewcommand{\labelitemii}{$\circ$}

\pagestyle{empty}
%-----------------------------------------------------------
%Custom commands
\newcommand{\resitem}[1]{\item #1 \vspace{-2pt}}
\newcommand{\resheading}[1]{{\small \colorbox{mygrey} { \begin{minipage}{0.99\textwidth}\centering{\textbf{#1 \vphantom{p\^{E}}}}\end{minipage}}}}
\newcommand{\ressubheading}[3]{
\begin{tabular*}{6.62in}{l @{\extracolsep{\fill}} r}
	\textsc{{\textbf{#1}}} & \rightline\textsc{\textit{[#2]}} \\
\end{tabular*}\vspace{-8pt}}
%-----------------------------------------------------------

\begin{document}
\begin{table}
    \begin{minipage}{0\linewidth}
        \centering
        \includegraphics[height =1in]{Logo.png}
    \end{minipage}
    \begin{minipage}{0.9\linewidth}
        %\centering
        \setlength{\tabcolsep}{70pt}
        \def\arraystretch{1.1}
        \begin{tabular}{ll}
            \textbf{\Large{Saheli Datta}}  &  {Mob. +91 9830976309} \\
            \textbf{Persuing Master of Statistics} &    Address: Kolkata, West Bengal \\
            {Indian Statistical Institute, Delhi} &    Email: {sahelidatta320@gmail.com} \\
            {} & LinkedIn: \href{linkedin.com/in/saheli-datta-301024211}\\
            {} & Github: \href{https://github.com/Saheli2001}
        \end{tabular}
    \end{minipage}\hfill
\end{table}

\setlength{\tabcolsep}{32pt}
\begin{table}
\centering
\begin{tabular}{lllll}
\toprule
\toprule
\textbf{Course}    & \textbf{College/University}     & \textbf{Year}     & \textbf{\%} \\ 
\toprule
Master of Statistics  & Indian Statistical Institute  & 2022-24   & -\\ 
Bachelor of Statistics  & St. Xavier's College (Autonomous), Kolkata  &  2019-22 & 85.4\\ 
10+2 Level    & Jadavpur Vidyapith & 2019 & 93.6  \\ 
Secondary Level      & Jodhpur Park Girls' High School & 2017 & 91.1   \\ 
\bottomrule
\bottomrule \\[-0.9cm]
\end{tabular}
\end{table}
% \fi

\noindent
\resheading{\textbf{SCHOLASTIC ACHIEVEMENTS}}\\[-0.5cm]
\begin{itemize}
\setlength\itemsep{-0.45em}
\item Secured \textbf{76 rank} in IIT JAM MS  \hfill {[2022]}
\\[-0.6cm]
\end{itemize}


\noindent
\resheading{\textbf{INTERNSHIPS}}\\[-0.45cm]
\begin{itemize}
\setlength\itemsep{-0.2em}
\item \textbf{Fixed-Term Research Analyst | University of California, Berkeley, Haas School of Business}\hfill {[Jun’22-Jun’22]}
\begin{itemize}[noitemsep,nolistsep]
    \item Worked on Data Analysis, Data Visualization with Excel on Bihar census data.
 \item Tools Required: Excel, PowerPoint
 \item Worked in a Team of 6
 \end{itemize}
\item \textbf{Research Intern | On Analysing clustered Misreported Count Data | St. Xavier's College (Autonomous), Kolkata}\hfill {[May’22-Present]} 
\begin{itemize}[noitemsep,nolistsep]
    \item A research internship under research guide Dr. Surupa Chakraborty, Associate professor, St. Xavier's College (Autonomous), Kolkata.
    \item Application of Logistic Regression.
 \item A team work of two members
 \end{itemize}
\end{itemize}



\noindent
\resheading{\textbf{SKILLS \& INTERESTS}}\\[-0.5cm]
 \begin{itemize}
  \item \textbf{Programming Languages}: R, Python (Basics)\\[-0.7cm]
  \item \textbf{Tools \& Libraries}: Matplotlib, Seaborn, Numpy, Pandas, ggplot2 , \textbf{\LaTeX} \\[-0.7cm]
  \item \textbf{Communication Skills}: Bengali, Hindi, English \\[-0.7cm]
\item \textbf{Interests}: Data Analysis, Statistical Modelling, Machine Learning \\[-0.5cm]
  \end{itemize}


\noindent
\resheading{\textbf{PROJECTS} }\\[-0.5cm]
\begin{itemize}
\setlength\itemsep{-0.5em}


\item \textbf{R Package : Missplot | CRAN}\hfill {[Apr'22]} 
\begin{itemize}[noitemsep,nolistsep]
    \item A team project of two members
      \item Analysis of Randomised Block Design and Latin Square Design with one missing observation
        \item Functions: RBD.miss, LSD.miss
 \end{itemize}
\end{itemize}

\noindent
\resheading{\textbf{COURSE PROJECTS} }\\[-0.5cm]
\begin{itemize}
\setlength\itemsep{-0.5em}
\item \textbf{House Price Prediction Using Linear Regression | Prof. Deepayan Sarkar | Sem 1 }\hfill {[Oct'22]} 
\begin{itemize}[noitemsep,nolistsep]
    \item Regression Technique coursework
 
      \item Imputation, Transformation of variables,PCA used for dimensionality reduction and removal of multicollinearity
      \item Linear Regression and Lasso Regression was performed in the whole dataset.
      \item Using various diagnostics checks we conclude that Lasso performs better.
        \item Tools Required: R Programming
 \end{itemize}

 \item \textbf{Two Sample Location Problem: Mann-Whitney Test | Prof. Isha Dewan | Sem 2 }\hfill {[Apr'23]} 
\begin{itemize}[noitemsep,nolistsep]
    \item Non Parametric Coursework
      \item Simulations based on Mann-Whitney Test Statistic
        \item Tools Required: R Programming
 \end{itemize}

  \item \textbf{Cereal Data Analysis | Prof. Swagata Nandi | Sem 2 }\hfill {[Apr'23]} 
\begin{itemize}[noitemsep,nolistsep]
    \item Multivariate Analysis Coursework
      \item Basic EDA was performed
      \item Application of Multivariate Test Procedures, Diagnostic Tests, PCA, Discriminant Analysis, Factor Analysis
        \item Tools Required: R Programming
 \end{itemize}
\end{itemize}



\noindent
\resheading{\textbf{RELEVANT COURSES}}\\[-0.2cm]
 % \textbf{Econometrics | Statistics | Mathematical Methods | Microeconomics | Macroeconomics}\hfill {[ISI-D]}\\[-0.1cm]\\
\begin{itemize}[noitemsep,nolistsep]
  \item \textbf{Regression Techniques | Inference | Probability Theory }\hfill {[ISI-D, Sem 1]}\\[-0.4cm]\\
  
  
  \item \textbf{Non Parametric Inferece | Large Sample Statistical Methods | Multivariate Analysis | Sample Survey | Design of Experiments}\hfill {[ISI-D, Sem 2]}\\[-0.4cm]\\
  

\end{itemize}

\noindent

\end{document}
