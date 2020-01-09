## Analysis of Differences in TD Causes and TD Payment-Related Practices from Software Architects

### This analysis is part of the [InsighTD Project](http://td-survey.com/).

This analysis was carry out using data gathered from a survey execution in four countries: Brazil, Chile, Colombia and the United States. 

**Goal**

The goal of this repository is shared the data generated and the Notebooks used to characterize the causes leading to TD occurrence and the practices related to TD payment from software architects. Results from sofware architects were compared to answers from Engineers and Manager.

Files shared here were lead by the following research questions:

- RQ1: From software architects' point of view, what causes lead software development teams to incur TD?
- RQ2: From software architects' point of view, what are the main practices related to TD payment by software development teams?
- RQ3: Is it possible to establish an association between main causes leading to TD occurrence and main practices related to TD payment by software development teams?}

**Credits**  

RBO implementation used in this project was taken from ÚČNK/David Lukeš: "A small Python module for calculating rank-biased overlap, a measure of similarity between ragged, possibly infinite ranked lists which may or may not contain the same items (up to the actually evaluated depth or at all). See "A similarity measure for indefinite rankings" by W. Webber, A. Moffat and J. Zobel (2011), http://dx.doi.org/10.1145/1852102.1852106."

- [RBO Implementation](https://github.com/dlukes/rbo)

**Folder's Content**

- AnalysisFiles: This folder contains consolidated data extracted from survey results regarding the research questions. Source data was stored in a Excel file and then processed using Jupyter Notebooks.
- Notebooks: This folder store the Jupyter Notebooks used in this project to get the relevant information, and also to generate informative charts. Radar chart was used to present the distribution of practices related to TD repayment among software architects, engineers and managers. Heatmap was used to present the association between main causes leading to TD ocurrence and the practices used on TD payment.
