# My_Latex_Resume

```
%-------------------------
% Resume in Latex
% Author : Abdelrahman Gaber
% Based off of: https://github.com/sb2nov/resume
% License : MIT
%------------------------

\documentclass[letterpaper,11pt]{article}

\usepackage{latexsym}
\usepackage[empty]{fullpage}
\usepackage{titlesec}
\usepackage{marvosym}
\usepackage[usenames,dvipsnames]{color}
\usepackage{verbatim}
\usepackage{enumitem}
\usepackage[hidelinks]{hyperref}
\usepackage{fancyhdr}
\usepackage[english]{babel}
\usepackage{tabularx}
\input{glyphtounicode}

%----------FONT OPTIONS----------
% sans-serif
% \usepackage[sfdefault]{FiraSans}
% \usepackage[sfdefault]{roboto}
% \usepackage[sfdefault]{noto-sans}
% \usepackage[default]{sourcesanspro}

% serif
% \usepackage{CormorantGaramond}
% \usepackage{charter}

\pagestyle{fancy}
\fancyhf{} % clear all header and footer fields
\fancyfoot{}
\renewcommand{\headrulewidth}{0pt}
\renewcommand{\footrulewidth}{0pt}

% Adjust margins
\addtolength{\oddsidemargin}{-0.5in}
\addtolength{\evensidemargin}{-0.5in}
\addtolength{\textwidth}{1in}
\addtolength{\topmargin}{-.5in}
\addtolength{\textheight}{1.0in}

\urlstyle{same}

\raggedbottom
\raggedright
\setlength{\tabcolsep}{0in}

% Sections formatting
\titleformat{\section}{
  \vspace{-4pt}\scshape\raggedright\large
}{}{0em}{}[\color{black}\titlerule \vspace{-5pt}]

% Ensure that generated pdf is machine readable/ATS parsable
\pdfgentounicode=1

%-------------------------
% Custom commands
\newcommand{\resumeItem}[1]{
  \item\small{
    {#1 \vspace{-2pt}}
  }
}

\newcommand{\resumeSubheading}[4]{
  \vspace{-2pt}\item
    \begin{tabular*}{0.97\textwidth}[t]{l@{\extracolsep{\fill}}r}
      \textbf{#1} & #2 \\
      \textit{\small#3} & \textit{\small #4} \\
    \end{tabular*}\vspace{-7pt}
}

\newcommand{\resumeSubSubheading}[2]{
    \item
    \begin{tabular*}{0.97\textwidth}{l@{\extracolsep{\fill}}r}
      \textit{\small#1} & \textit{\small #2} \\
    \end{tabular*}\vspace{-7pt}
}

\newcommand{\resumeProjectHeading}[2]{
    \item
    \begin{tabular*}{0.97\textwidth}{l@{\extracolsep{\fill}}r}
      \small#1 & #2 \\
    \end{tabular*}\vspace{-7pt}
}

\newcommand{\resumeSubItem}[1]{\resumeItem{#1}\vspace{-4pt}}

\renewcommand\labelitemii{$\vcenter{\hbox{\tiny$\bullet$}}$}

\newcommand{\resumeSubHeadingListStart}{\begin{itemize}[leftmargin=0.15in, label={}]}
\newcommand{\resumeSubHeadingListEnd}{\end{itemize}}
\newcommand{\resumeItemListStart}{\begin{itemize}}
\newcommand{\resumeItemListEnd}{\end{itemize}\vspace{-5pt}}

%-------------------------------------------
%%%%%%  RESUME STARTS HERE  %%%%%%%%%%%%%%%%%%%%%%%%%%%%

\begin{document}

%----------HEADING----------
\begin{center}
    \textbf{\Huge \scshape Abdelrahman Gaber} \\ \vspace{1pt}
    \small Cairo, Egypt $|$ 01095151496 $|$ 
    \href{mailto:abdelrhaman.gaber.hamdy@gmail.com}{\underline{abdelrhaman.gaber.hamdy@gmail.com}} $|$ \\
    \href{https://www.linkedin.com/in/abdelrahman-gaber-937b6028b}{\underline{linkedin.com/in/abdelrahman-gaber-937b6028b}} $|$
    \href{https://abdelrahmangaberhamdy.netlify.app}{\underline{Portfolio}} $|$
    \href{https://github.com/AbdelrahmanGaber528}{\underline{GitHub}}
\end{center}

%-------Summary-----------------
\section{Summary}
  \begin{itemize}[leftmargin=0.15in, label={}]
    \small{\item{
      AI student in the third year of study, specializing in Machine Learning and Deep Learning, advancing in NLP. 
      Building and deploying models with a strong foundation in data processing, data structures, algorithms, and software engineering.\newline
      Solving Problmes +230 on Codeforces and Leetcode.
    }}
  \end{itemize}

%-----------EDUCATION-----------
\section{Education}
  \resumeSubHeadingListStart
    \resumeSubheading
      {Helwan University}{Cairo, Egypt}
      {B.Sc. Computer Science - Artificial Intelligence}{Oct. 2023 -- Present}
      \resumeItemListStart
        \resumeItem{AI major}
        \resumeItem{Current GPA: 3.38/4.0}
      \resumeItemListEnd
  \resumeSubHeadingListEnd

%-----------EXPERIENCE-----------
\section{Experience}
  \resumeSubHeadingListStart

    \resumeSubheading
      {Digital Egypt Pioneers Initiative (DEPI)}{June 2025 -- Present}
      {AI \& Machine Learning Trainee}{Alexandria, Egypt}
      \resumeItemListStart
        \resumeItem{Completed intensive training in Machine Learning, Deep Learning, NLP, CV and MLOps.}
        \resumeItem{Hands-on experience in data preprocessing, feature engineering, model evaluation, and deployment tools.}
      \resumeItemListEnd

  \resumeSubHeadingListEnd

%-----------PROJECTS-----------
\section{Projects}
  \resumeSubHeadingListStart

    \resumeProjectHeading
        {\textbf{Production Pipeline - Classification} $|$ \emph{Python, scikit-learn, MLOps, Streamlit}}{Aug. 2025 -- Sep. 2025}
        \resumeItemListStart
          \resumeItem{Built an end-to-end pipeline processing \textbf{50,000+ BMW vehicle records} with 10 features each.}
          \resumeItem{Achieved \textbf{98\% classification accuracy} on test data using ensemble models.}
          \resumeItem{ 4 core pipeline components.}
          \resumeItem{Implemented automated ETL and data validation to ensure consistency across all features.}
          \resumeItem{Developed a production-ready Streamlit app for real-time predictions and visualization.}
        \resumeItemListEnd

    \resumeProjectHeading
        {\textbf{Library Management System (LMS)} $|$ \emph{Java, JavaFX, Maven, OOP, File Storage}}{Nov. 2024 -- Jan. 2025}
        \resumeItemListStart
          \resumeItem{Developed a desktop application managing books, users, and borrowing operations.}
          \resumeItem{Implemented full CRUD operations with advanced search     and filtering capabilities.}
           \resumeItem{Applied OOP and SOLID principles with unit testing in    JUnit to ensure code reliability.}
          \resumeItem{Managed 1,000+ book records and 500+ user accounts in     file-based storage.}
          \resumeItem{Reduced book lookup time by 80–90\% using HashMap indexing over ArrayList linear search on 10,000+ test records}
        \resumeItemListEnd

  \resumeSubHeadingListEnd

%-----------SKILLS-----------
\section{Skills}
 \begin{itemize}[leftmargin=0.15in, label={}]
    \small{\item{
     \textbf{Programming Languages}{: Python, Java, C, C++, Js} \\

     \textbf{Principles}{: OOP, SOLID, Problem Solving Principles, Clean Architecture} \\

     \textbf{Databases}{: MySQL, Oracle} \\

     \textbf{Data}{: NumPy, Pandas, Seaborn, Matplotlib, Plotly} \\

     \textbf{Data Engineering}{: Feature Engineering, Dimensionality Reduction, Data Pipelines, ETL, Data Validation} \\

     \textbf{Machine Learning \& Deep Learning}{: Pytorch, Scikit-learn, Regression, Classification, CNN, RNN} \\

     \textbf{Natural Language Processing}{: Text Preprocessing, Tokenization, NER, Sentiment Analysis, Text Classification} \\

     \textbf{DevOps \& Systems}{: Git, GitHub, Streamlit, Linux (Void, Ubuntu, NixOS)} \\

     \textbf{Tools}{: Vim, VS Code, Colab, Jupyter, PyCharm}\\
    \textbf{Soft Skills}{: Teamwork, Communication, Adaptability, Critical Thinking, Attention to Details}
    }}
 \end{itemize}
 
%-----------CERTIFICATES-----------
\section{Certificates}
  \resumeSubHeadingListStart
    \resumeItem{N8N AI Automation: Agents, Voice and More – Mohamed Elshamy (Udemy) – Sept. 2025 -- Present}
  \resumeSubHeadingListEnd

%-----------LANGUAGES-----------
\section{Languages}
  \resumeSubHeadingListStart
    \resumeItem{Arabic (Native)}
    \resumeItem{English (Fluent)}
  \resumeSubHeadingListEnd

%-------------------------------------------
\end{document}


```
