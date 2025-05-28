\documentclass{article}
\usepackage{graphicx}
\usepackage{hyperref}
\usepackage{listings}
\usepackage{amsmath}
\usepackage{geometry}
\usepackage{enumitem}
\geometry{margin=1in}
\title{Fengyun-2F Eccentricity Analysis}
\author{}
\date{}

\begin{document}

\maketitle

\section*{Project Overview}

This project presents a time series analysis of the \textbf{eccentricity values} for the \textbf{Fengyun-2F satellite} using statistical forecasting techniques. The objective is to model the orbital eccentricity over time and detect anomalies that may indicate satellite maneuvers or irregular orbital behavior.

\section*{Key Objectives}

\begin{itemize}[itemsep=0.5em]
    \item Load and preprocess TLE-derived orbital element data
    \item Apply ARIMA modeling to forecast eccentricity
    \item Visualize and compare predicted vs. actual eccentricity
    \item Detect anomalies based on residuals and statistical thresholds
\end{itemize}

\section*{Methodologies}

The analysis employs:

\begin{itemize}[itemsep=0.5em]
    \item \textbf{ARIMA} (AutoRegressive Integrated Moving Average) modeling
    \item Residual-based anomaly detection
    \item Visualization with Matplotlib and Seaborn
    \item Time series diagnostics and error analysis
\end{itemize}

\section*{Repository Structure}

\begin{verbatim}
Fengyun2FEccentricity/
├── Fengyun2FEccentricity.ipynb   % Main Jupyter notebook
├── data/                         % Directory for input TLE data (not included)
├── models/                       % Directory for saving models (optional)
├── plots/                        % Folder for visual outputs (optional)
└── README.md                     % Markdown version of this document
\end{verbatim}

\section*{Installation Requirements}

Install the required Python packages using:

\begin{lstlisting}[language=bash]
pip install numpy pandas matplotlib seaborn statsmodels
\end{lstlisting}

\section*{Sample Output}

\begin{itemize}[itemsep=0.5em]
    \item Time series plot showing predicted and actual eccentricity
    \item Residual plots for model diagnostics
    \item Highlighted anomalies based on deviations
\end{itemize}

\section*{Future Enhancements}

\begin{itemize}[itemsep=0.5em]
    \item Implement SARIMA or LSTM models for improved forecasting
    \item Extend anomaly detection to other orbital parameters
    \item Incorporate historical maneuver metadata
\end{itemize}

\section*{References}

\begin{itemize}[itemsep=0.5em]
    \item TLE data for Fengyun-2F satellite
    \item ARIMA and time series modeling principles from statistical learning resources
\end{itemize}
