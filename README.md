# Infodemiology

The Final Report (which can be viewed in its entirety here: https://nbviewer.jupyter.org/github/akong4110/Infodemiology/blob/main/Final%20Report.ipynb) is a record of the process from September 2020 to December 2020 of US sentiment towards self-induced abortion over the course of the past year [11/01/19 - 11/01/20]. The goal is to conduct trends analysis on future data in the beginning of 2021 to understand the interest trends of self-induced abortion related terminology and the potential trend influences of the covid pandemic.

The RSI_RSV_ACQUISITION (the Google Trends API key is intentionally excluded for legal reasons) contains the procedure taken to extract terms (and their relative search volume for top queries & relative search indexes for follow-up queries) from the Google Trends & Health Trends API. The algorithm's purpose is to document each query level for a given initial search term, ensuring to remove duplicates by updating the running log of acquired queries accordingly.

The Graphviz Tree Graphs demonstrates the creation of tree graphs for each term search's relative search indexes. Highlighted nodes were noted for either importance: relevancy to self-induced abortion or lack of follow-up terms.

Over The Counter Pill presentation demonstrates a high level overview of the updated search process for the term "over the counter pill" during October 2020.

## 2021 Update

RSI_RSV_ACQUISITION-2021_UPDATE:  

The process to get 30 iterations for the 'over the counter pill' search took: 3min. 2sec. 95 ms.

The process to get 1 iteration for the 'over the counter pill' search took: 3min. 27sec. 34ms.

If we were to have done 30 iterations using the old method it would have taken: 1.725 hours.

With this procedure I have improved our search algorithm, it now takes 2.93% of the original time it would have to conduct a 30 iteration sample of a search for a given query.

