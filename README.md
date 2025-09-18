\documentclass[a4paper]{article}
    \usepackage{fullpage}
    \usepackage{amsmath}
    \usepackage{amssymb}
    \usepackage{textcomp}
    \usepackage[utf8]{inputenc}
    \usepackage[T1]{fontenc}
    \textheight=10in
    \pagestyle{empty}
    \raggedright
    \usepackage[left=0.8in,right=0.8in,bottom=0.8in,top=0.8in]{geometry}

    %\renewcommand{\encodingdefault}{cg}
%\renewcommand{\rmdefault}{lgrcmr}

\def\bull{\vrule height 0.8ex width .7ex depth -.1ex }

% DEFINITIONS FOR RESUME %%%%%%%%%%%%%%%%%%%%%%%

\newcommand{\area} [2] {
    \vspace*{-9pt}
    \begin{verse}
        \textbf{#1}   #2
    \end{verse}
}

\newcommand{\lineunder} {
    \vspace*{-8pt} \\
    \hspace*{-18pt} \hrulefill \\
}

\newcommand{\header} [1] {
    {\hspace*{-18pt}\vspace*{6pt} \textsc{#1}}
    \vspace*{-6pt} \lineunder
}

\newcommand{\employer} [3] {
    { \textbf{#1} (#2)\\ \underline{\textbf{\emph{#3}}}\\  }
}

\newcommand{\contact} [3] {
    \vspace*{-10pt}
    \begin{center}
        {\Huge \scshape {#1}}\\
        #2 \\ #3
    \end{center}
    \vspace*{-8pt}
}

\newenvironment{achievements}{
    \begin{list}
        {$\bullet$}{\topsep 0pt \itemsep -2pt}}{\vspace*{4pt}
    \end{list}
}

\newcommand{\schoolwithcourses} [4] {
    \textbf{#1} #2 $\bullet$ #3\\
    #4 \\
    \vspace*{5pt}
}

\newcommand{\school} [4] {
    \textbf{#1} #2 $\bullet$ #3\\
    #4 \\
}
% END RESUME DEFINITIONS %%%%%%%%%%%%%%%%%%%%%%%

    \begin{document}
\vspace*{-40pt}

    

%==== Profile ====%
\vspace*{-10pt}
\begin{center}
	{\Huge \scshape {Ruby Engelhart}}\\
	Albany, NY $\cdot$ engelhartrueben@gmail.com $\cdot$ 605.569.6198 $\cdot$ github.com/engelhartrueben\\
\end{center}

%==== Experience ====%
\header{Experience}
\vspace{1mm}

\textbf{University at Albany} \hfill Albany, NY\\
\textit{Supplemental Instructor} \hfill Aug 2025 - Present\\
\vspace{-1mm}
\begin{itemize} \itemsep 1pt
	\item Instruct 20+ college students in Calclus 1 and 2, preparing extensive lesson plans to support and improve the educational outcome of the class as a whole.
\end{itemize}
\textbf{State Voices} \hfill Remote\\
\textit{Software Engineer} \hfill June 2023 - December 2024\\
\vspace{-1mm}
\begin{itemize} \itemsep 1pt
	\item •Collaborated in the development and maintenance of Spoke, a React web application, to improve user experience and performance.
	\item •Lead and developed a cross platform opt-in and opt-out service, crucial to FEC compliance, with 100\% test coverage using Jest.
	\item •Played a pivotal role in upgrading Spoke from NodeV16 to NodeV20 and integrating new technologies to enhance application performance and capability.
	\item •Designed and executed a front-end prototype of a web application, showcasing rebranding efforts before full implementation.
\end{itemize}
\textbf{United Today, Stronger Tomorrow} \hfill Spearfish, SD\\
\textit{Organizer} \hfill October 2021 - December 2022\\
\vspace{-1mm}
\begin{itemize} \itemsep 1pt
	\item United Today, Stronger Tomorrow engages in advocacy efforts aimed at fostering equitable solutions and enhancing civic participation among local citizens.
	\item Analyzed data trends to refine campaign strategies, resulting in a 50\% increase in engagement and retention rates.
	\item Designed interactive dashboards to visualize data trends, allowing for real-time decision making and improved campaign targeting, lending to the success of several on the ground campaigns.
\end{itemize}

\header{Projects}
{\textbf{Cerebral}}\hfill https://github.com/CerebralLabs/cerebral\\
A Roblox Player State Management. Simplifies the handling of player data, from the database, to in-game, and back, with the goal of making the development of Roblox games more accessible.\\
\vspace*{2mm}
{\textbf{Mangle}}\hfill https://github.com/CerebralLabs/mangle\\
Inspired by Python\textquotesingle{}s name mangler, making variables private by naming convention. Designed to manage the complexity of large projects in Luau.\\
\vspace*{2mm}
{\textbf{Pantheon}}\hfill https://github.com/coal-rock/Pantheon\\
A Command and Control Adversary Emulation Framework written in Rust. Working with a small team, this tool helps organize security testing.\\
\vspace*{2mm}

\header{Skills}
\begin{tabular}{ l l }
	Java, JavaScript, TypeScript, Python, Rust, SQL, Lua, Node, pm2, React JS, Docker, Linux: &   \\
\end{tabular}
\vspace{2mm}

\header{Awards}
\textbf{IEEE U Albany Hackathon \textbar{} 2nd Place}\\
•In a 24 hour hackathon, my team and I built a web application called \textquotedbl{}LaTeX TuTor\textquotedbl{} that helps users learn LaTeX, a typesetting system. \hfill February 2025\\
\vspace*{2mm}

%==== Education ====%
\header{Education}
\textbf{Black Hills State University}\hfill Spearfish, SD\\
BS Political Science \textit{GPA: 3.8} \hfill 2018 - 2022\\
\vspace{2mm}
\textbf{University at Albany}\hfill Albany, NY\\
BS Computer Science \hfill 2024 - Projected Fall 2026\\
\vspace{2mm}

\ 
\end{document}