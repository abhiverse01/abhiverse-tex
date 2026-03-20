\documentclass{resume}

\usepackage[left=0.4in,top=0.4in,right=0.4in,bottom=0.4in]{geometry}
\usepackage[T1]{fontenc}
\usepackage{microtype}         % Tighter, more refined text rendering
\usepackage{charter}           % Clean, professional serif — far more distinctive than default CM
\usepackage{hyperref}
\hypersetup{
    colorlinks=true,
    urlcolor=blue,
    linkcolor=black
}

\newcommand{\tab}[1]{\hspace{.2667\textwidth}\rlap{#1}}
\newcommand{\itab}[1]{\hspace{0em}\rlap{#1}}

\name{Er.Abhishek Shah}

\address{+977(981) 587-3277 \\ Kathmandu, Nepal}
\address{
    \href{mailto:abhishek.aimarine@gmail.com}{abhishek.aimarine@gmail.com} \\ 
    \href{https://linkedin.com/in/theabhishekshah}{linkedin.com/in/theabhishekshah} \\
    \href{https://abhishekshah.vercel.app}{abhishekshah.vercel.app} \\
    \href{https://github.com/abhiverse01}{github.com/abhiverse01}
}

\begin{document}

%----------------------------------------------------------------------------------------
%   PROFESSIONAL SUMMARY
%----------------------------------------------------------------------------------------
\begin{rSection}{PROFESSIONAL SUMMARY}
AI/ML Engineer and Technical Project Manager with \textbf{4+ years of experience} building production systems in Machine Learning, LLMs, Recommender Systems, and cloud-native AI infrastructure. Former AI Team Lead at Inflancer Technology; currently building independently across AI, tooling, and open-source. Ranked \textbf{\#61 among Nepal's top open-source contributors} on GitHub. Actively seeking \textbf{ML Engineer} or \textbf{Technical Project Manager} roles.
\end{rSection}

%----------------------------------------------------------------------------------------
%   SKILLS
%----------------------------------------------------------------------------------------
\begin{rSection}{SKILLS}
\begin{tabular}{ @{} >{\bfseries}l @{\hspace{4ex}} p{13.5cm} }
AI Engineering:   & LLMs, RAG Pipelines, Agentic AI, Fine-Tuning (LoRA/PEFT), \\
                  & Embedding-Based Search, Vector Databases, Knowledge Graphs, Prompt Engineering \\[0.5ex]
ML \& Data Science: & Deep Learning, NLP, Recommender Systems, Computer Vision, MLOps \\[0.5ex]
Languages \& Stack: & Python, JavaScript, Flask, ReactJS, SQL \\[0.5ex]
Infrastructure:   & Docker, Kubernetes, Kafka, Microservices, System Design, Cloud Deployment \\[0.5ex]
Databases:        & MongoDB, PostgreSQL, Chroma / Qdrant \\[0.5ex]
Soft Skills:      & AI Team Leadership, Agile Project Management, Technical Writing, Stakeholder Communication \\
\end{tabular}
\end{rSection}

%----------------------------------------------------------------------------------------
%   EXPERIENCE
%----------------------------------------------------------------------------------------
\begin{rSection}{EXPERIENCE}

\textbf{AI Engineer \& AI Team Lead} \hfill \textbf{April 2024 – December 2025} \\
\textbf{Inflancer Technology} \hfill \textit{Kathmandu, Nepal}
\begin{itemize} \itemsep -3pt {}
    \item Architected and deployed production \textbf{Recommender Systems} on Docker and Kubernetes, directly improving content personalisation and user engagement at scale.
    \item Built NLP \textbf{embedding-based semantic search} to replace keyword lookups with contextually relevant, intent-aware content discovery.
    \item Designed scalable AI microservices integrating \textbf{Kafka} for real-time data pipelines and event-driven processing on cloud infrastructure.
    \item Led cross-functional AI collaboration across product, engineering, and business teams — translating model capabilities into measurable outcomes.
\end{itemize}

\textbf{Project Manager} \hfill \textbf{October 2024 – December 2025} \\
\textbf{Inflancer Technology} \hfill \textit{Kathmandu, Nepal}
\begin{itemize} \itemsep -3pt {}
    \item Drove end-to-end delivery of AI and product initiatives using \textbf{Agile methodologies}, owning sprint planning, risk mitigation, and stakeholder alignment.
    \item Coordinated cross-functional teams to maintain on-time, high-quality releases with clear communication up to leadership.
\end{itemize}

\textbf{ML Engineer \& Research Contributor} \hfill \textbf{January 2019 – 2024} \\
\textbf{Freelance / ResearchGrad} \hfill \textit{Nepal}
\begin{itemize} \itemsep -3pt {}
    \item Fine-tuned a \textbf{Llama-2 7B} model on a custom code-description dataset, shipping a fully functional Python code generator.
    \item Built a real-time hand gesture recognition system with \textbf{CNNs and OpenCV}, deployed live via Vercel.
    \item Contributed to ML research on \textbf{Nepali Music Genre Classification} and \href{https://github.com/abhiverse01/hatespeech-multimodal-detection}{\textbf{Multi-modal Hate Speech Detection}}, supporting a mentor's M.Sc.\ thesis.
\end{itemize}

\textbf{ML Intern} \hfill \textbf{October – November 2023} \\
\textbf{Codsoft} \hfill \textit{Bangalore, India}
\begin{itemize} \itemsep -3pt {}
    \item Built credit card fraud detection and customer churn prediction models; achieved \textbf{86.55\% accuracy} with Random Forest, SMOTE, and hyperparameter tuning. \href{https://github.com/abhiverse01/CODSOFT-INTERN}{(GitHub)}
    \item Delivered an SVM spam classifier at \textbf{98\% accuracy} and an NLP movie genre classifier with a production-ready interface.
\end{itemize}

\textbf{ML Mentor} \hfill \textbf{February 2024} \\
\textbf{ACES Bootcamp} \hfill \textit{Dharan, Nepal}
\begin{itemize} \itemsep -3pt {}
    \item Mentored students through ML fundamentals, live debugging, and model improvement during a week-long intensive training camp.
\end{itemize}

\end{rSection}

%----------------------------------------------------------------------------------------
%   PROJECTS
%----------------------------------------------------------------------------------------
\begin{rSection}{PROJECTS}
\vspace{-1.25em}
\item \textbf{TitanML} \href{https://abhiverse01.github.io/titanML/}{(GitHub)}: Zero-dependency, physics-powered \textbf{AI knowledge graph engine} with interactive bubble-graph visualization — lets users explore AI concept relationships dynamically, with no external libraries required.

\item \textbf{Test Maker Engine} \href{https://abhiverse01.github.io/test-maker/}{(Live)}: A completely free, zero-backend \textbf{quiz engine} built with pure HTML, CSS, JS, and JSON — no login, no database, no server. Supports 50 randomised questions per session, keyboard navigation, dark/light mode, session resume, and a rich results breakdown. Built for educators; fully open-source.

\item \textbf{CodeBeing} \href{https://projectcodebeing.vercel.app/}{(Live)}: Natural language-to-Python code generator powered by a fine-tuned \textbf{Llama-2 7B} model, built with ReactJS and deployed on Vercel.

\item \textbf{Sentiment Analyzer} \href{https://github.com/abhiverse01/SentimentAnalysis-DistilBERT}{(GitHub)}: NLP sentiment classification using \textbf{DistilBERT}, achieving 89\% accuracy.

\item \textbf{Hand Gesture Recognizer} \href{https://github.com/abhiverse01/hand-gesture-recognizer}{(GitHub)}: CNN + OpenCV pipeline for real-time gesture-to-sign-language translation built for accessibility.

\item \textbf{Flappy Bird: God Mode Edition}\href{https://abhiverse01.github.io/Flappy-Bird/}{(GitHub)}: AI-augmented variant with adaptive difficulty and enhanced game mechanics — built to explore algorithmic game logic and agent-driven behaviour.

\end{rSection}

%----------------------------------------------------------------------------------------
%   EDUCATION
%----------------------------------------------------------------------------------------
\begin{rSection}{EDUCATION}
{\bf Bachelor of Computer Engineering} – IOE, ERC, Tribhuvan University \hfill \textbf{Class of 2019} \\
\textit{Relevant Coursework}: Data Mining, Object-Oriented Programming \& Design, Artificial Intelligence, Theory of Computation.
\end{rSection}

%----------------------------------------------------------------------------------------
%   COMMUNITY & LEADERSHIP
%----------------------------------------------------------------------------------------
\begin{rSection}{COMMUNITY \& LEADERSHIP}
\begin{itemize} \itemsep -3pt {}
    \item \textbf{\#61 in Nepal – Top GitHub Committers}: Ranked among Nepal's most active open-source contributors on the global top.committers leaderboard.
    \item \textbf{Tech Writer – Medium}: Weekly articles on LLMs, AI engineering, and software tools — reaching \textbf{1K+ readers/week}. \href{https://medium.com/@abhiverse01}{(Profile)}
    \item \textbf{Industry Case Studies}: Independently researching how AI-driven companies (Spotify, Netflix, Airbnb) architect and monetize their ML systems — insights applied to engineering and product decisions.
    \item \textbf{Open-Source Education}: Maintains \href{https://github.com/abhiverse01/the-coders-handbook}{The Coder's Handbook}, \href{https://github.com/abhiverse01/how-I-learned-python}{how-I-learned-python}, and \href{https://github.com/abhiverse01/how-I-learned-ml-repo}{how-I-learned-ml} as structured beginner guides for Python, ML, and deep learning.
    \item \textbf{Deltathon Organizer}: Managed logistics and coordination for the ACES major hackathon; later competed as part of Team ZAV.
\end{itemize}
\end{rSection}

\end{document}
