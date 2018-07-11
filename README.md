%-------------------------
% Resume in Latex
% Author : Amit Mohanty
%------------------------

\documentclass[letterpaper,11pt]{article}

\usepackage{latexsym}
\usepackage[empty]{fullpage}
\usepackage{titlesec}
\usepackage{marvosym}
\usepackage[usenames,dvipsnames]{color}
\usepackage{verbatim}
\usepackage{enumitem}
\usepackage{hyperref}
\usepackage{fancyhdr,multicol}
%\usepackage{fontspec,xltxtra,xunicode}
%\setmainfont{Georgia Pro}
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

%\urlstyle{same}
\hypersetup{
    bookmarks=true,         % show bookmarks bar?
    unicode=false,          % non-Latin characters in Acrobat’s bookmarks
    pdftoolbar=true,        % show Acrobat’s toolbar?
    pdfmenubar=true,        % show Acrobat’s menu?
    pdffitwindow=false,     % window fit to page when opened
    pdfstartview={FitH},    % fits the width of the page to the window
    pdftitle={Resume - Amit Mohanty - 2018},    % title
    pdfauthor={Amit Mohanty},     % author
    pdfsubject={Subject},   % subject of the document
    pdfcreator={Creator},   % creator of the document
    pdfproducer={Producer}, % producer of the document
    pdfkeywords={keyword1, key2, key3}, % list of keywords
    pdfnewwindow=true,      % links in new PDF window
    colorlinks=true,       % false: boxed links; true: colored links
    linkcolor=red,          % color of internal links (change box color with linkbordercolor)
    citecolor=green,        % color of links to bibliography
    filecolor=magenta,      % color of file links
    urlcolor=magenta          % color of external links
}


\raggedbottom
\raggedright
\setlength{\tabcolsep}{0in}

% Sections formatting
\titleformat{\section}{
  \vspace{-4pt}\scshape\raggedright\large
}{}{0em}{}[\color{black}\titlerule \vspace{-5pt}]

%-------------------------
% Custom commands
\newcommand{\resumeItem}[2]{
  \item\small{
    \textbf{#1}{: #2 \vspace{-2pt}}
  }
}

\newcommand{\resumeSubheading}[4]{
  \vspace{-1pt}\item
    \begin{tabular*}{0.97\textwidth}{l@{\extracolsep{\fill}}r}
      \textbf{#1} & #2 \\
      \textit{\small#3} & \textit{\small #4} \\
    \end{tabular*}\vspace{-5pt}
}

\newcommand{\resumeSubItem}[2]{\resumeItem{#1}{#2}\vspace{-4pt}}

\renewcommand{\labelitemii}{$\circ$}

\newcommand{\resumeSubHeadingListStart}{\begin{itemize}[leftmargin=*]}
\newcommand{\resumeSubHeadingListEnd}{\end{itemize}}
\newcommand{\resumeItemListStart}{\begin{itemize}}
\newcommand{\resumeItemListEnd}{\end{itemize}\vspace{-5pt}}

%-------------------------------------------
%%%%%%  CV STARTS HERE  %%%%%%%%%%%%%%%%%%%%%%%%%%%%


\begin{document}

%----------HEADING-----------------
\begin{tabular*}{\textwidth}{l@{\extracolsep{\fill}}l}
  \textbf{\huge Amit Mohanty} & Email : \href{mailto:mohanty.1936@gmail.com}{mohanty.1936@gmail.com}\\
 {1388 Tannytown Road, Canton, MI 48188} & Mobile : +1~765~461~3636 \\
 \emph{US Permanent Resident} &  \\
\end{tabular*}

%-----------EDUCATION-----------------
%{\fontspec{Segoe UI}\section{Summary}}
{\section{Summary}}
\begin{itemize}[leftmargin=.2in]
 \setlength{\itemsep}{0pt}
 \item Top-level technology leader with over 8 years of proven experience specializing in digital transformation, lean business incubation and product management through relentless pursuit of innovation through data mining, machine learning, software engineering, and agile methods
 \item Six years of extensive experience at both Fortune 100 companies and technology start-ups engaging with billionaire investors (Vinod Khosla/EcoMotors) and C-level executives (CEO, CTO/EcoMotors, Chief Data and Analytics Officer/Ford, VP - Manufacturing/Ford)
 \item Create a strategic IT vision by
building upon the inputs from sales, marketing, operations, general management and financial teams. Extensive qualifications in the
following competencies:

\begin{multicols}{3}
$-$~Machine Learning\\
$-$~Artificial Intelligence\\
$-$~R/Python/Scala, Spark/Hadoop\\
$-$~Data Engineering\\
$-$~DevOps/Agile Methods\\
$-$~Software Development\\
$-$~IT operation\\
$-$~Product Management\\
$-$~Strategy Development\\
\end{multicols}

\end{itemize}
%-----------EXPERIENCE-----------------
%{\fontspec{Segoe UI}\section{Experience}}
{\section{Experience}}
\textbf{Ford Motor Company}
      \\
       \emph{\textbf{Manager}, Connectivity Analytics}\hfill {2016 - Present}\\
       \emph{\textbf{Team Lead}, Driver Behavior \& Prognostics}\hfill {2015 - 2016}\\[1mm]
       Globally responsible for all connected vehicle data, analytics, and machine learning required to provide customers with the best experience in the industry through products and services related to connectivity, and mobility solutions for Ford's post-future vehicles \\[2mm]
\begin{itemize}[leftmargin=.2in]
 \setlength{\itemsep}{0pt}
 \setlength\itemsep{1mm}
 \item Lead a global (Dearborn/USA, Aachen/Germany, Chennai/India) cross-functional team of 15 connectivity engineers, machine learning researchers, data scientists \& business analysts in connectivity \& smart mobility 
\item Delivered insights across the entire portfolio of Ford's vehicle connectivity platforms - \emph{vehicle feature usage}, \emph{future product design}, \emph{EV-hypothesis validation}. Directly effected reduction in battery warranty cost by 38M+ USD per year, 100+ internal users of dashboard users.
\item Designed and delivered 4 data-driven software products - \textbf{(a)} Usage-Based Insurance (20+ internal users of dashboard; effected 30M+ enterprise investment; 68.4M USD additional revenue), \textbf{(b)} Driver Behavior, \textbf{(c)} Prognostics (100M+ USD saving \& new revenue), \textbf{(d)} Diesel Particulate Filter regen (7.5M USD).
\item Provided thought leadership and strategic vision for \textbf{(a)} data driven product planning for next-gen Ford vehicular data and analytics infrastructure to support Ford's vision of  100\% connectivity by 2020, and \textbf{(b)} telematics data monetization.
\item Provided data and analytics-driven insights into labor absenteeism problem at Ford assembly plants in NA to enable office of VP - Manufacturing to conduct a fact-based negotiation with United Auto Workers (UAW) union.
 \end{itemize}


      \textbf{EcoMotors Inc. - A Bill Gates/Vinod Khosla start-up}\hfill {2013 - 2015}
      \\
       \emph{\textbf{Founding Engineer}, The Controls, Algorithm \& Software Group}\\
\begin{itemize}[leftmargin=.2in]
 \setlength{\itemsep}{0pt}
 \setlength\itemsep{1mm}
\item Defined and operationalized product road map for algorithmic delivery and optimization for {the controls system and software configuration management for the opposed-piston opposed-cylinder (\textbf{opoc}) engine}; Coordinated and led the recruitment for the team (5 PhDs, 5 Masters, 2 technicians); Provided subject matter expertise in Model-based Control, Signal Processing, Data Analysis, and Embedded System. 
\item Reduced cost of operation by 5M USD through staff augmentation and restructuring, and in-housing end-to-end software development and delivery. Improved software delivery efficiency by reducing developmental lead time over 45\%.
\end{itemize}

 
      \textbf{Department of Energy}, Idaho Falls, ID\hfill {2010 - 2013}
      \\
       \emph{Staff Scientist}\\[2mm]
 My broad research was focused on
discovering novel ways in which energy should be produced, distributed
and utilized to alleviate potential {\em energy scramble} without
increasing our carbon footprint.\\
\begin{itemize}[leftmargin=.2in]
 \setlength{\itemsep}{0pt}
 \setlength\itemsep{1mm}
  \vspace*{-1mm}
 \item Principal technical contributor, \textit{Hybrid Systems Process
 Integration and Dynamic Studies}, Laboratory Directed
 Research \& Development Program (Research Budget: \$ 687,165
 (FY'12),~\$400,000 (FY'13));
 \item Conducted economic analysis using developed cost functional of
a nuclear hybrid energy system. Developed predictive data analytics and machine learning algorithm for battery health monitoring. Designed and implemented load following control of water level in the steam generator of
a nuclear reactor.
\end{itemize}
 

%-----------EDUCATION-----------------
%{\fontspec{Segoe UI}\section{Education}}
{\section{Education}}
\begin{itemize}%
 \setlength{\itemsep}{0pt}
 \item Post Doctoral, Electrical Engineering \& Computer Science, University of California, Berkeley, CA, USA
\item Doctor of Philosophy, Mechanical Engineering, Purdue University, IN, USA
\item Master of Science, Mechanical Engineering, Southern Illinois University, Carbondale, IL, USA
\item Bachelor of Technology, Indian Institute of Technology, Kharagpur, INDIA

\end{itemize}

%-----------PROJECTS-----------------
    %{\fontspec{Segoe UI}\section{Publication}}
    {\section{Publications and Inventions}}
    \begin{itemize}%
 \setlength{\itemsep}{0pt}
 \item 15 peer reviewed journal and conference papers, dissertation; 300+ international citations; Full publication list available at \url{https://scholar.google.com/citations?user=-Lm-1_MAAAAJ&hl=en}
 \item 2 patent applications and multiple invention disclosures; 
 
\end{itemize}


%-----------PROJECTS-----------------
%{\fontspec{Segoe UI}\section{Awards and Recognitions}}
{\section{Awards and Recognitions}}

\begin{itemize}\setlength{\itemsep}{0pt}
\item Featured on Ford's international career webpage. The profile and the video are available at:
\url{https://corporate.ford.com/careers/profiles/amit-mohanty.html}
\item Recipient of the  \emph{Magoon Award for Teaching Excellence},
Purdue University, 2008.
\item Recipient of the prestigious \emph{Shanti Gupta Trophy for
Academic Excellence}, Azad Hall of Residence, Indian Institute of
Technology, Kharagpur, INDIA.
\item Placed among top 5 (out of 87) students of 2003 graduating batch
of the  Department of Mechanical Engineering, IIT Kharagpur INDIA.
\item Ranked 4$^{th}$ among approximately 100,000 student (top 0.004\%
 in ORISSA-JEE, INDIA 1999).
\item Placed among top 0.09\% of approximately 450,000 students who
appeared in IIT-JEE, INDIA 1999.
\end{itemize}


%
%--------PROGRAMMING SKILLS------------
%\section{Programming Skills}
%  \resumeSubHeadingListStart
%    \item{
%      \textbf{Languages}{: Scala, Python, Javascript, C++, SQL, Java}
%      \hfill
%      \textbf{Technologies}{: AWS, Play, React, Kafka, GCE}
%    }
%  \resumeSubHeadingListEnd


%-------------------------------------------
\end{document}
