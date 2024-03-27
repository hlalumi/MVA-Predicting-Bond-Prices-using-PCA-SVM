# MVA-Predicting-Bond-Prices-using-PCA-SVM

The project looks at predicting bond prices using principal component analysis (PCA), kernel principal component analysis (kPCA) and Supply Vector Machines (SVM) . 

The data series studied in this paper are daily-frequency observations from bond market data; the data is daily sampled closing price data and runs from 1994 to 2017. This data was purchased from INET-BFA for academic use . The data consists of bonds with different maturities and types namely ALBI, 1 to 3 years bonds, 3 to 7 years, 7 to 12 years, over 12 years and GOVI.

The data has the following variables 

Variable | Type | Dependent/Independent |Description
----------|------------|---------|---------
Closing Prices | Continuous| Dependent|Last price at which a security traded during the regular trading day on a stock exchange
Duration | Continuous|Independent| Sensitivity of the bond price to changes in interest rates
Convexity | Continuous|Independent| Sensitivity of a bond's duration to changes in interest rates
Interest Yield | Continuous|Independent| Interest earned from holding the bond 
Total Return Index (TRI) | Continuous|Independent| Capital gains as well as any cash distributions, such as dividends or interest, attributed to bond at a specific point in time
Total Return Index YtD (Year-to-date) | Continuous|Independent| Capital gains as well as any cash distributions, such as dividends or interest, earned on the bond over the past year.
TRI Average Yield | Continuous)|Independent|Average capital gains as well as any cash distributions, such as dividends or interest, earned on the bond over the past year.
