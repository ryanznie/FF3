# FF3
> A recreation of Fama French Three Factor Model. FF3 is an extension of the Capital Asset Pricing Model (CAPM) and is a popular model used to explain stock returns.

## Importing Data
All data used are downloaded from Wharton Research Data Services (WRDS). See below for specific redirections in the database.

```sh
CEQ, ITCB, PSTK, TXDB from WRDS Compustat Daily Updates - Fundamentals Annual
CSHO, PRCC_F from WRDS Compustat Daily Updates - Fundamentals Annual
TRT1M from WRDS CRSP/Compustat Merged Database - Security Monthly
```

To find qualifying firms for any fiscal year t, there must be existing financial data for the firm from t-2 years. This project focuses on t = 2020.

## Contributing

Feel free to continue working on this project! You can also try to focus on a different fiscal year t. To gain access to WRDS, try contacting your university or institution.

## Resources
For more information, see below for research papers and resources.

1. https://wrds-www.wharton.upenn.edu/pages/support/applications/risk-factors-and-industry-benchmarks/fama-french-factors/#hml-1980-1989
2. https://wrds-www.wharton.upenn.edu/pages/support/applications/risk-and-valuation-measures/market-book-mb-ratio/
3. https://www.ivey.uwo.ca/cmsmedia/3775516/size_and_book-to-market_factors.pdf
4. https://www.youtube.com/watch?v=Iel_GRQNAxA
5. https://www.investopedia.com/terms/f/famaandfrenchthreefactormodel.asp
6. https://www.investopedia.com/terms/b/booktomarketratio.asp#:~:text=The%20book%2Dto%2Dmarket%20ratio%20compares%20a%20company's%20book%20value,the%20number%20of%20shares%20outstanding.
7. https://en.wikipedia.org/wiki/Fama%E2%80%93French_three-factor_model
