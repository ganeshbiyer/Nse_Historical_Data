# Nse_Historical_Data
1 Min Historical data for Nifty 500 Stocks.
Contains data from 2018 until 31st Dec 2025.
Hence forth data will be provided in a seperate repo, to avoid Github space restrictions.

Henceforth data will be provided in year wise repo.


The files are in **.parquet** format.

Includes 1 min data for Nifty, BankNifty, FinNifty and MidcapNifty indexes.

They can be read using Pandas as shown below.

  **df = pandas.read_parquet(<filename.parquet>)**

Requires:
    pandas 
    parquet 
    pyarrow

Can be installed using pip.


