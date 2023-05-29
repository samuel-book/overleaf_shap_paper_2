# What is the narrative

* Focus on SHAP interactions

* Full SHAP includes unwanted interactions between patients and hospitals
* SHAP main effect misses interactions withing groups of intrerest
* SHAP interaction subsets maximise dissection of hospital vs patient
* SHAP interactions reveal more nuanced realtionshsips

# Jounral info 

Intelligence-Based Medicine (https://www.sciencedirect.com/journal/intelligence-based-medicine)

Instructions for authors: 
https://www.elsevier.com/journals/intelligence-based-medicine/2666-5212/guide-for-authors



# Inserting full size image

\lipsum[1-3]

\begin{figure*}[h]
  \centering
  \includegraphics[width=\textwidth]{example-image-a}
  \caption{This is a full page width figure.}
  \label{fig:full-width}
\end{figure*}

\lipsum[4-6]

Or in a column:

\begin{figure}[htbp]
  \centering
  \includegraphics[width=\linewidth]{example-image}
  \caption{Example figure}
  \label{fig:example}
\end{figure}

In this example, the figure environment is used to insert the image. The \includegraphics command is used to include the image, and the width option is set to \linewidth to make the image occupy the full width of one column. The htbp placement specifier is used to suggest the position of the figure (here, top, bottom, or on a separate page). However, you can adjust the placement specifier according to your preferences.