\documentclass[letterpaper,11pt]{article}

\usepackage{fontawesome5}
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
\usepackage{graphicx}
\usepackage{cite}
\usepackage{amsmath}
\usepackage{booktabs}
\usepackage{url}
\usepackage[default]{lato}
\input{glyphtounicode}
\pdfgentounicode=1

\pagestyle{fancy}
\fancyhf{}
\fancyfoot{}
\renewcommand{\headrulewidth}{0pt}
\renewcommand{\footrulewidth}{0pt}

\addtolength{\oddsidemargin}{-0.5in}
\addtolength{\evensidemargin}{-0.5in}
\addtolength{\textwidth}{1in}
\addtolength{\topmargin}{-.6in}
\addtolength{\textheight}{1.2in}

\urlstyle{same}
\raggedbottom
\raggedright
\setlength{\tabcolsep}{0in}
\titleformat{\section}{\vspace{-4pt}\scshape\raggedright\large}{}{0em}{}[\color{black}\titlerule\vspace{-5pt}]

\newcommand{\resumeItem}[1]{\item\small{{#1 \vspace{-2pt}}}}
\newcommand{\resumeSubheading}[4]{
  \vspace{-2pt}\item
    \begin{tabular*}{0.97\textwidth}[t]{l@{\extracolsep{\fill}}r}
      \textbf{#1} & #2 \\
      \textit{\small#3} & \textit{\small #4} \\
    \end{tabular*}\vspace{-7pt}
}
\newcommand{\resumeProjectHeading}[2]{\item
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
\definecolor{Black}{RGB}{0, 0, 0}
\newcommand{\seticon}[1]{\textcolor{Black}{\csname #1\endcsname}}

\begin{document}

\begin{center}
    \textbf{\Huge \scshape Jaiveer Bassi} \\ \vspace{4pt}
    {\small 707-656-6227 $|$ \href{mailto:jaiveerbassi@ymail.com}{\underline{jaiveerbassi@ymail.com}} $|$ \href{https://www.linkedin.com/in/jaiveer-bassi}{\underline{linkedin.com/in/jaiveer-bassi}} $|$ \href{https://github.com/imjbassi}{\underline{github.com/imjbassi}} $|$ \href{https://imjbassi.github.io}{\underline{imjbassi.github.io}}}
\end{center}

\section{Summary}
Full-stack software engineer with production experience building web applications, REST APIs, and data pipelines. Built and shipped applications at Kaiser Permanente and independently, including three deployed web platforms and a revenue-generating e-commerce system. Published AI/ML researcher with 3 papers. MS in Software Engineering.

\section{Experience}
\resumeSubHeadingListStart

\resumeSubheading
{Handshake}{Apr 2026 -- Present}
{AI Response Evaluator}{Remote}
\resumeItemListStart
    \resumeItem{Evaluate LLM-generated code and technical responses across AI/ML and software engineering domains (C\#/.NET, Python, ML systems), scoring on correctness, instruction following, and writing quality.}
\resumeItemListEnd

\resumeSubheading
{Kaiser Permanente Regional Laboratory}{Oct 2023 -- June 2024}
{Software Developer}{Berkeley, CA}
\resumeItemListStart
    \resumeItem{Developed full-stack web application using React, Express, RESTful APIs, and SQL for uploading, processing, and viewing clinical lab instrument data across multiple departments.}
    \resumeItem{Built secure data pipelines with input validation and error logging for laboratory information systems, consolidating a manual data entry process across 50+ instrument data columns into an automated upload workflow.}
    \resumeItem{Collaborated directly with lab technicians and clinical staff to gather requirements, conduct demos, and iterate on features based on end-user feedback.}
\resumeItemListEnd

\resumeSubHeadingListEnd

\section{Projects}
\resumeSubHeadingListStart
\resumeProjectHeading
{\textbf{\href{https://github.com/imjbassi/chess-reinforcement-learning}{Chess-RL Engine}} $|$ \emph{C++, PyTorch, Python, pybind11, PyGame}}{}
\resumeItemListStart
\resumeItem{Built AlphaZero-inspired chess engine with C++ bitboard backend and PyTorch neural network (policy/value heads, 18-channel board encoding) trained via self-play. Real-time PyGame GUI with move probability visualization.}
\resumeItemListEnd

\resumeProjectHeading
{\textbf{\href{https://castline.studio}{Castline Studio Order System}} $|$ \emph{Next.js 14, TypeScript, WebAssembly, Vercel, REST APIs}}{}
\resumeItemListStart
\resumeItem{Built order management web app with real-time STL file analysis via WebAssembly, Vercel Blob storage with client-token uploads, Etsy REST API (OAuth), Resend email automation, and EasyPost shipping. Powers a \$2K+/month e-commerce business.}
\resumeItemListEnd

\resumeProjectHeading
{\textbf{\href{https://medstract.net}{MedStract.net}} $|$ \emph{Python, Flask, PubMed API, NLP, JavaScript, Chart.js, Vercel}}{}
\resumeItemListStart
\resumeItem{Built biomedical research tool with Flask REST API querying PubMed's 36M+ articles. Custom NLP pipeline rewrites summaries for 4 audience levels. PDF export, 4-format citations, and trend charts.}
\resumeItemListEnd

\resumeSubHeadingListEnd

\section{Research Publications}
\resumeSubHeadingListStart
\resumeProjectHeading
{\textbf{Brain Tumor Classification with Pretrained CNNs in PyTorch} $|$ \emph{7,000+ MRI, ResNet-18} $|$ {\scriptsize\href{https://doi.org/10.13140/RG.2.2.21638.28484}{DOI}}}{}
\resumeItemListStart
\resumeItem{Built reproducible pipeline using transfer learning to classify brain tumors into four categories from 7,000+ MRI images using a fine-tuned ResNet-18 model.}
\resumeItemListEnd
\resumeProjectHeading
{\textbf{\href{https://github.com/imjbassi/Transferability-of-Adversarial-Attacks}{Transferability of Adversarial Attacks Across ML Models}} $|$ \emph{CIFAR-10, ResNet-18, VGG16, MobileNetV2} $|$ {\scriptsize\href{https://doi.org/10.13140/RG.2.2.16410.76489}{DOI}}}{}
\resumeItemListStart
\resumeItem{Evaluated adversarial attack transferability across ResNet-18, VGG16, and MobileNetV2 using FGSM, PGD, and Carlini-Wagner attacks on CIFAR-10, demonstrating 99\%+ cross-architecture attack success rates.}
\resumeItemListEnd
\resumeSubHeadingListEnd

\section{Technical Skills}
\textbf{Languages:} Python, TypeScript, JavaScript, SQL, C++, Java, HTML/CSS \\ 
\textbf{Frontend:} React, Next.js, Tailwind CSS, Bootstrap \\
\textbf{Backend:} Node.js, Express, Flask, RESTful APIs, Docker, Git, CI/CD \\
\textbf{AI/ML:} OpenAI API, LangChain, PyTorch, HuggingFace, RAG Pipelines \\
\textbf{Data \& Cloud:} PostgreSQL, MongoDB, Supabase, Vercel, AWS, Google Cloud, DICOM, HL7/FHIR \\
\textbf{Other:} WebAssembly, OAuth 2.0, Pandas, NumPy, OpenCV

\section{Education}
\resumeSubHeadingListStart
    \resumeSubheading
    {Grand Canyon University}{May 2024 -- Oct 2025}
    {MS in Computer Software Engineering}{Phoenix, AZ}
    \resumeSubheading
    {University of Silicon Valley}{May 2021 -- Aug 2023}
    {BS in Computer Science}{San Jose, CA}
\resumeSubHeadingListEnd

\section{Certifications}
\vspace{2pt}
\textbf{HackerRank Software Engineer Certificate} (2026) \hfill \textbf{Stanford AI/ML in Healthcare} (Jun 2025) \\ \vspace{4pt}
\textbf{IBM Artificial Intelligence} (Aug 2025) \hfill \textbf{Google Project Management} (Sep 2024) \\ \vspace{4pt}
\textbf{Cisco Network Support and Security} (Sep 2025)

\end{document}
