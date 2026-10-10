# DataScienceSecondCapstone
Data Science second capstone

Per discussion with Daniel at our last mentor call, he had proposed simplifying my capstone by pursuing a minimum viable product (MVP) model for the Aristocrats.  As such, I plan to have my model predict the 1-year forward total return for an arbitrary Aristocrat given a small subset of fundamental and technical features.  The subset of features is viable considering the mature, stable companies that comprise the Aristocrats list.

Please note that I have subscribed to the API service of financialmodelingprep.com (FMP) for the purposes of acquiring fundamentals, prices, dividends, and splits data for my Aristocrats.  Since the API key is private, the physical execution of the Jupyter notebooks in the zip file will not actively fetch any of the FMP data.  In light of this, I am hereby including all relevant CSV files that were created during the course of the notebooks' construction.

The Aristocrats_EDA_Redux.zip file contains 14 CSV files and 3 notebooks.  The notebooks are intended to flow in the following sequence:  FMP_script -> FMP_features -> FMP_EDA.



