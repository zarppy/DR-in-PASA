PASA Author Template (CUP Journals)
------------------------------------------

The following files are available in pasa.zip archive:

pasa.cls			- This is the LaTeX2e class file for PASA template
aas_macros.sty      - LaTeX package (contain abbreviations of various journal names)
pasa-auguide.pdf	- This is PDF of Author Guide for PASA template
pasa-sample.pdf		- This is PDF file of sample LaTeX document for PASA template
pasa-sample.tex		- This is file of sample LaTeX document for PASA template
apj.bst				- This is bibliography style file
pasa-mnras.bst      - This is bibliography style file
1r_lamboo_notes.bib - Sample BIB file (Bibliography Database File)
fpo.eps				- Graphics file used in sample EPS format
fpo.pdf				- Graphics file used in sample PDF format


Happy TeXing!!!
Aptara

%\begin{table*}
%\setlength\tabcolsep{4pt}
%\caption{Maximum and average demand profiles in Victoria between 2013 and 2018.}
%\begin{tabularx}{\textwidth}{@{} Y Y Y *{3}{>{\hsize=0.95\hsize}x} >{\hsize=1.35\hsize}x @{}}
%\toprule
% & \textbf{Winter max demand} & \textbf{Summer max demand} & \textbf{Annual average demand} \\
%\midrule
%2013 & 7,898 & 9,760 & 5,272 \\
%2014 & 7,648 & 10,308 & 5,321 \\
%2015 & 7,923 & 8,635 & 5,193 \\
%2016 & 7,767 & 9,523 & 5,079 \\
%2017 & 7,472 & 8,730 & 4,953 \\
%2018 & 7,874 & 9,159 & 4,948 \\
%\bottomrule
%\end{tabularx}
%\label{tab:tableX}
%\end{table*}

%\begin{table}[!h]
%\setlength\tabcolsep{4pt}
%\caption{Maximum and average demand profiles in Victoria between 2013 and 2018.}
%\begin{tabularx}{\textwidth}{*{4}{Z}}
%\toprule
%\multicolumn{4}{c}{\thead{Electricity Demand in Victoria}}   \\
%\midrule
%\thead{Year} & \thead{Winter max demand}  & \thead{Summer max demand} & \thead{Annual average demand}  \\%
%\midrule
%2013 & 7,898 & 9,760 & 5,272 \\
%2014 & 7,648 & 10,308 & 5,321 \\
%2015 & 7,923 & 8,635 & 5,193 \\
%2016 & 7,767 & 9,523 & 5,079 \\
%2017 & 7,472 & 8,730 & 4,953 \\
%2018 & 7,874 & 9,159 & 4,948 \\
% \bottomrule
%\end{tabularx}
%\label{tab:table1}
%\end{table}

\begin{table}
\caption{This is an example of table caption.}
\begin{center}
\begin{tabular}{@{}cc@{}}
\hline\hline
Dimension & Classification accuracy \\
\hline%
 1  & 0.6232 \\
 2  & 0.9635 \\ 
 3  & 0.9724 \\ 
 4  & 0.9690 \\ 
 5  & 0.9840 \\ 
 6  & 0.9842 \\ 
 7  & 0.9873 \\ 
 8  & 0.9884 \\
 9  & 0.9873 \\ 
 10 & 0.9898 \\ 
 11 & 0.9914 \\
\hline\hline
\end{tabular}
\end{center}
\label{tab1}
\end{table}

\begin{table}[]
\caption{Maximum and average demand profiles in Victoria between 2013 and 2018.}
\label{tab:table1}
\begin{tabular}{p{0.7cm} ccc}
%\begin{tabular}{p{0.5cm} p{2cm}p{2cm}p{1.5cm}}
\cline{1-4}
 & \multicolumn{3}{c}{\textbf{Electricity Demand in Victoria}} \\ \cline{1-4}
 & \begin{tabular}[c]{@{}c@{}}Winter peak \\ demand\\ (MW)\end{tabular} & \begin{tabular}[c]{@{}c@{}}Summer peak \\ demand\\  (MW)\end{tabular} & \begin{tabular}[c]{@{}c@{}}Average annual \\ demand \\ (MW)\end{tabular} \\ \cline{1-4}  
2013 & 7,898 & 9,760 & 5,272 \\
2014 & 7,648 & 10,308 & 5,321 \\
2015 & 7,923 & 8,635 & 5,193 \\
2016 & 7,767 & 9,523 & 5,079 \\
2017 & 7,472 & 8,730 & 4,953 \\  
2018 & 7,874 & 9,159 & 4,948 \\ \cline
\end{tabular}
\end{table}
