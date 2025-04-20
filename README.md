\documentclass[11pt,a4paper]{article}
\usepackage[utf8]{inputenc}
\usepackage[margin=1in]{geometry}
\usepackage{graphicx}
\usepackage{xcolor}
\usepackage{hyperref}
\usepackage{listings}
\usepackage{tabularx}
\usepackage{booktabs}
\usepackage{minted}
\usepackage{fontawesome5}

% Colors
\definecolor{primary}{RGB}{41,128,185}
\definecolor{secondary}{RGB}{142,68,173}
\definecolor{accent}{RGB}{39,174,96}

\title{\color{primary}\textbf{FocusLearn}\\ 
\large{\color{secondary}Your All-in-One Learning Productivity Platform}
\author{Aman Shahi \\ \small{\texttt{am.amanshahi@example.com}}}
\date{\today}

\begin{document}

\maketitle

\begin{center}
    \includegraphics[width=0.8\textwidth]{placeholder-hero.png} % Replace with actual image
    \vspace{1em}
    
    \textit{"Read, Watch, Reflect, and Grow – All in One Space."}
\end{center}

\section*{\color{primary}\faIcon{star} Why FocusLearn?}
Modern learners face \textbf{fragmentation}:
\begin{itemize}
    \item \faIcon{book} PDFs scattered across devices
    \item \faIcon{youtube} Tutorial playlists lost in browser history
    \item \faIcon{sticky-note} Notes trapped in different apps
    \item \faIcon{clock} No progress tracking
    \item \faIcon{headphones} Focus tools running separately
\end{itemize}

FocusLearn provides:
\begin{table}[h]
    \centering
    \begin{tabularx}{\textwidth}{lX}
        \toprule
        \textbf{Solution} & \textbf{Benefit} \\
        \midrule
        Unified Platform & Single workspace for all learning resources \\
        Timeline Notes & Contextual annotations synchronized with content \\
        Progress Analytics & Visual tracking of learning journey \\
        Focus Environment & Built-in productivity tools \\
        Secure Cloud Sync & Access your library anywhere \\
        \bottomrule
    \end{tabularx}
\end{table}

\section*{\color{primary}\faIcon{rocket} Key Features}
\subsection*{\faIcon{book-open} Unified Learning Hub}
\begin{minipage}{0.6\textwidth}
    \begin{itemize}
        \item PDF reader with pagination
        \item YouTube tutorial integration
        \item Seamless media switching
    \end{itemize}
\end{minipage}
\begin{minipage}{0.4\textwidth}
    \includegraphics[width=\linewidth]{placeholder-pdf.png}
\end{minipage}

\subsection*{\faIcon{pencil-alt} Smart Annotation}
\begin{itemize}
    \item Time/page-specific notes
    \item Tagging and search
    \item Markdown formatting support
\end{itemize}

\section*{\color{primary}\faIcon{cogs} Technology Stack}
\begin{table}[h]
    \centering
    \begin{tabularx}{\textwidth}{lXl}
        \toprule
        \textbf{Layer} & \textbf{Technologies} & \textbf{Purpose} \\
        \midrule
        Frontend & Angular 16+, PrimeNG, RxJS & Responsive UI \\
        Backend & .NET 7, MongoDB & Business logic \& data \\
        DevOps & Docker, GitHub Actions & CI/CD pipeline \\
        \bottomrule
    \end{tabularx}
\end{table}

\section*{\color{primary}\faIcon{download} Installation}
\subsection*{Prerequisites}
\begin{lstlisting}[language=bash]
# Required tools
sudo apt install -y nodejs dotnet-sdk-7.0 mongodb-org
npm install -g @angular/cli
\end{lstlisting}

\subsection*{Setup Steps}
\begin{enumerate}
    \item Clone repository:
    \begin{minted}{bash}
    git clone https://github.com/AmanSDE/FocusLearn.git
    cd FocusLearn
    \end{minted}
    
    \item Configure backend:
    \begin{minted}{bash}
    cd server-api
    echo "MONGODB_URI=mongodb://localhost:27017/focuslearn" > .env
    dotnet restore
    dotnet run
    \end{minted}
    
    \item Run frontend:
    \begin{minted}{bash}
    cd ../client-app
    npm install
    ng serve
    \end{minted}
\end{enumerate}

\section*{\color{primary}\faIcon{code} Development}
\subsection*{Project Structure}
\begin{minted}{text}
FocusLearn/
├── client-app/          # Angular frontend
│   ├── src/app/
│   │   ├── auth/       # Authentication flows
│   │   ├── core/       # Services
│   │   └── viewer/     # PDF/Video player
├── server-api/         # .NET backend
│   ├── Controllers/
│   ├── Models/
│   └── Repositories/
\end{minted}

\subsection*{Common Commands}
\begin{tabularx}{\textwidth}{lX}
    \toprule
    Command & Purpose \\
    \midrule
    \texttt{ng generate component} & Create new Angular component \\
    \texttt{dotnet watch run} & Hot-reload backend \\
    \texttt{docker-compose up} & Run with containers \\
    \bottomrule
\end{tabularx}

\section*{\color{primary}\faIcon{road} Roadmap}
\begin{itemize}
    \item \faIcon{robot} AI-powered note summarization (Q2 2024)
    \item \faIcon{users} Collaborative annotation (Q3 2024)
    \item \faIcon{mobile} Mobile app (Q4 2024)
\end{itemize}

\section*{\color{primary}\faIcon{hands-helping} Contributing}
\begin{itemize}
    \item Fork the repository
    \item Create feature branches (\texttt{feat/your-feature})
    \item Follow Angular/.NET style guides
    \item Submit pull requests with tests
\end{itemize}

\section*{\color{primary}\faIcon{balance-scale} License}
MIT License - See \href{LICENSE}{LICENSE} file.

\section*{\color{primary}\faIcon{envelope} Contact}
\begin{itemize}
    \item \faIcon{github} \href{https://github.com/AmanSDE}{github.com/AmanSDE}
    \item \faIcon{twitter} \href{https://twitter.com/yourhandle}{@yourhandle}
    \item \faIcon{envelope} \texttt{am.amanshahi@example.com}
\end{itemize}

\begin{center}
    \colorbox{primary!10}{
        \parbox{0.8\textwidth}{
            \centering
            \color{primary}\textbf{\faIcon{star} Star us on GitHub if you find this project useful!}\\
            Support open-source development
        }
    }
\end{center}

\end{document}
