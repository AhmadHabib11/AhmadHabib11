\documentclass{resume} % Use the custom resume.cls style

\usepackage[left=0.4in,top=0.4in,right=0.4in,bottom=0.4in]{geometry} % Document margins
\usepackage{hyperref} % to handle clickable links
\hypersetup{
    colorlinks=true,   % enable colored links
    linkcolor=black,   % internal links
    urlcolor=black,    % URLs
    citecolor=black    % citations
}

\newcommand{\tab}[1]{\hspace{.2667\textwidth}\rlap{#1}} 
\newcommand{\itab}[1]{\hspace{0em}\rlap{#1}}
\name{Ahmad Habib} 
\address{+923319666507 \\ Islamabad, Pakistan} 
\address{\href{mailto:ahmadd.habibb11@gmail.com}{ahmadd.habibb11@gmail.com} \\ 
\href{https://www.linkedin.com/in/ahmad-habib-044579347}{LinkedIn} \\ 
\href{https://github.com/AhmadHabib11}{GitHub}} 

\begin{document}

%----------------------------------------------------------------------------------------
%	OBJECTIVE
%----------------------------------------------------------------------------------------
\begin{rSection}{OBJECTIVE}
Computer Science undergraduate with strong foundations in Machine Learning and Deep Learning, currently pursuing the Neural Networks \& Deep Learning specialization by (DeepLearning.AI). Seeking AI/ML internship opportunities to apply hands-on model development and optimization skills.
\end{rSection}

%----------------------------------------------------------------------------------------
%	EDUCATION
%----------------------------------------------------------------------------------------
\begin{rSection}{Education}

{\bf Bachelor of Computer Science}, FAST - NUCES \hfill {Expected 2027}\\

{\bf A-Level Pre-Engineering}, Beaconhouse College Programme \hfill {Aug 2021 - Jul 2023}\\
Grades: 2As, 1B

{\bf O-Level Computer Science}, Beaconhouse School System \hfill {Aug 2021 - Jul 2023}\\
Grades: 8A*s

\end{rSection}

%----------------------------------------------------------------------------------------
%	TECHNICAL SKILLS
%----------------------------------------------------------------------------------------
\begin{rSection}{Skills}

\begin{tabular}{ @{} >{\bfseries}l @{\hspace{6ex}} l }
Technical Skills & Python, NumPy, Pandas, REST APIs, Data Analysis, Neural Networks, Logistic Regression\\
 & Gradient Descent, Vectorization \\
\\
Soft Skills & Leadership, Teamwork, Strong Communication skills, Community Engagement\\
\end{tabular}

\end{rSection}

%----------------------------------------------------------------------------------------
%	EXPERIENCE
%----------------------------------------------------------------------------------------
\begin{rSection}{Experience} 

\begin{itemize}
    \item {\bf AI Engineer} at \href{https://primeinnovators.org/}{Prime Innovators} \hfill {Jan 2026 - Present}
    \begin{itemize}
        \item Developed a \textbf{Python script} to analyze a user's GitHub profile by fetching their top 5 repositories and aggregating programming languages to build a "Skill Graph" (e.g., Python: 60\%, JavaScript: 40\%), returning a JSON summary of language usage per user.
        \item Currently researching and designing an \textbf{AI-based system to analyze and classify GitHub commits} (e.g., useful vs low-impact contributions) using repository metadata and commit patterns.
        \item Contributing to the planning of a platform aimed at \textbf{encouraging meaningful open-source contributions} by identifying high-quality commits and rewarding developers with a point-based recognition system.
    \end{itemize}
\end{itemize}

\end{rSection}

%----------------------------------------------------------------------------------------
%	PROJECTS
%----------------------------------------------------------------------------------------
\begin{rSection}{Projects}

\begin{itemize}
    \item \textbf{\href{https://github.com/AhmadHabib11/Gaussian_NN_Model}{Gaussian Neural Network Model}}: Designed and implemented a \textbf{multi-layer neural network from scratch using NumPy} for a \textbf{non-linear binary classification} problem. Achieved \textbf{~94\% accuracy} with a \textbf{4-layer network} using \textbf{tanh} hidden activations and \textbf{sigmoid} output, trained via \textbf{vectorized gradient descent} over \textbf{10,000 iterations}.
    \item \textbf{\href{https://github.com/AhmadHabib11/Seatbelt_Detection_Model}{Seatbelt Detection Model}}: Built a binary image classification model (\textbf{seatbelt vs no-seatbelt}) using \textbf{logistic regression implemented from scratch with NumPy}. Implemented manual \textbf{forward/backward propagation}, \textbf{vectorized gradient descent}, and image preprocessing. Achieved \textbf{~93\% training accuracy} and \textbf{~85\% test accuracy}.
    \item \textbf{\href{https://github.com/AhmadHabib11/SmartWeatherBot}{SmartWeatherBot}}: Developed a \textbf{weather chatbot} in \textbf{Python, Pandas, Matplotlib} to analyze \textbf{historical weather data (2006–2016)} and respond to \textbf{natural language queries} on temperature, humidity, and rainy days by month.
\end{itemize}

\end{rSection}

%----------------------------------------------------------------------------------------
%	EXTRA-CURRICULAR ACTIVITIES
%----------------------------------------------------------------------------------------
\begin{rSection}{Extra-Curricular Activities} 
\begin{itemize}
    \item Graphics Department Vice Head, FAST Culinary Club: Designed official logo and social media content to promote club activities.
\end{itemize}
\end{rSection}

\end{document}
