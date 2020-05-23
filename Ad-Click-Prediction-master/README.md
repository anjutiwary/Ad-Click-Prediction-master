# Ad-Click-Prediction

A key technology behind search advertising is to predict the click-through rate (pCTR) of ads, as the economic model behind search advertising requires pCTR values to rank ads and to price clicks. Given the training instances derived from session logs of the Tencent proprietary search engine, soso.com, participants are expected to accurately predict the pCTR of ads in the testing instances.
Data Type
csv files
Both text and integer values
Training Data 
QueryId_tokensid.txt (id query_toks1|query_toks2|query_toks3|...)
PurchaseId_tokensid.txt (id Purchase_toks1|Purchase_toks2|...)
TitleId_tokensid.txt (id Title_toks1|Title_toks2|Title_toks3|...)
DescriptionId_tokensid.txt (id Description_toks1|Description_toks2|...)
UserId_tokensid.txt (UserId, gender{0,1,2}, age)
Test data set The testing dataset shares the same format as the training dataset, except for the counts of ad impressions and ad clicks that are needed for computing the empirical CTR.
Data Size: 700 MB
