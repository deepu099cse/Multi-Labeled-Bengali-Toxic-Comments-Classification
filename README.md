#  Multi_labeled_toxic_comments

There are one multi-label abusive comment dataset: Bangla-Abusive-Comment-Dataset https://github.com/aimansnigdha/Bangla-Abusive-Comment-Dataset and two multi-class hate speech and cyberbullying datasets: Bengali Hate Speech Dataset https://github.com/rezacsedu/Bengali-Hate-Speech-Dataset, Bangla Online Comments Dataset https://data.mendeley.com/datasets/9xjx8twk8p/1 publicly available.
We have collected the text samples from these three datasets and categorize them manually in six classes: vulgar, hate, religious, threat, troll, insult where each sample text can be in multiple labels. For annotation purpose, we took help from three expert annotators and on the annotator's individual judgments for each class, we use the majority vote. There are in total 16,073 instances in the dataset. Among them 7,585 instances are \textit{Non-toxic} and 8,488 instances are \textit{Toxic}.

\begin{table}[htbp]
\centering
\caption{Statistics of the toxic comments for multi-label classification}
\label{tab:dataset}
\begin{tabular}{|c|c|}
\hline
\textbf{Class} & \textbf{\begin{tabular}[c]{@{}c@{}}No. of \\ instances\end{tabular}} \\ \hline
vulgar         & 2504                                                                 \\ \hline
hate           & 1894                                                                 \\ \hline
religious      & 1418                                                                 \\ \hline
threat         & 1419                                                                 \\ \hline
troll          & 1643                                                                 \\ \hline
insult         & 2719                                                                 \\ \hline
\end{tabular}
\end{table}
