# EbayAuction
This report discusses the use of the decision tree classification algorithm offered by
Scikit Learn to classify eBay auctions as competitive or not. Auction competitiveness is
determined by the number of bids. If an auction has more than one bid, it is considered
as a competitive auction. The first step involved exploring the available data by
generating a series of count plots. The categorical data was transformed into sets of
dummy variables which created a binary variable representing each of the possible
categorical data point (for example, the Currency variable had three options, USD, EUR,
and GBP, each of which became its own column after the transformation). After the
data was explored, preprocessed, and split between training and testing sets using a
60%-40% proportion, it was used to fit two decision tree classification models.
