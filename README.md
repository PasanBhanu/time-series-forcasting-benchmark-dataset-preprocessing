# Data Pre Processor for Time Series Forcasting

This is a data preprocessing algorithm for widely used data sets provided by ["The Internet Traffic Archive"](https://ita.ee.lbl.gov).

The supported datasets are,
- WorldCup98 Dataset - [View](https://ita.ee.lbl.gov/html/contrib/WorldCup.html)

  1,352,804,107 web requests recorded at servers for the 1998 World Cup.
- NASA HTTP Logs Dataset - [View](https://ita.ee.lbl.gov/html/contrib/NASA-HTTP.html)

  3,461,612  HTTP logs from a busy WWW server for two months.

This algorithm process the both data sets and create CSV for time series analysis. CSV file format is given below.

| minute | count |
|--------|-------|
|1995-07-01 00:00:00| 42    |
|1995-07-01 00:01:00| 61    |
|1995-07-01 00:02:00| 57    |

### Features of Algorithm

- WorldCup98 dataset automatic FTP download
- WorldCup98 dataset cross validation with original file for record count
- Visualize the processed data
- Timeseries ready csv output
- Shrink the dataset size for easier processing

### Preprocessed Files

If you are interested in preprocessed files, check `processeddata` folder for CSV files.
