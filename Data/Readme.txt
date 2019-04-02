Paper Title: "A Bayesian Semiparametric Approach for Trend-Seasonal Interactions: an Application to Migration Forecasts"
Authors: Alice Milivinti and Giacomo Benini
Contacts: a.lice.milivinti@gmail.com
Author's Website: https://aliceindataland.rbind.io/

DATA SETS DESCRIPTION

1. Immigration time series.csv contains the Swiss immigration time series from January 1981 to December 2014 on a monthly frequency.
The variables included are: 
  a. Year: the year of the observation;
  b. Date: the day/month/year date of the observation;
  c. Month: the month of the observation; 
  d. x: the number of immigrats arriving in Switzerland at the correspondent date;
  e. xlog: the log-transformed number of immigrats arriving in Switzerland at the correspondent date;
  f. t: the total number of time periods, t=1,...,T;
  g. trend: the time trend obtained by t/T, where T is the total number of periods;

2. All Age time series.csv contains the the Swiss immigration time series from January 1981 to December 2014 on a monthly frequency for different ages (0-100). The variables included are: 
  a. Date: the day/month/year date of the observation.
  b. Age: the age of the observations;
  c. Year: the year of the observation;
  d. Month: the month of the observation; 
  e. x: the number of immigrats arriving in Switzerland at the correspondent date of the corresponging age;	
  f. xlog: the log-transformed number of immigrats arriving in Switzerland at the correspondent date of the corresponging age;
  g. t: the total number of time periods, t=1,...,T;
  h. trend: the time trend obtained by t/T, where T is the total number of periods;

3. Prediction time series.csv: contains the Swiss immigration time series from January 1981 to December 2050 on a monthly frequency.
The variables included are: 
  a. Year: the year of the observation;
  b. Date: the day/month/year date of the observation;
  c. Month: the month of the observation; 
  d. x: the number of immigrats arriving in Switzerland at the correspondent date;
  f. t: the total number of time periods, t=1,...,T;
  g. trend: the time trend obtained by t/T, where T is the total number of periods;

4. Prediction Age Time Series.csv: contains the Swiss immigration time series from January 1981 to December 2050 on a monthly frequency for different ages (0-100). The variables included are: 
  a. Date: the day/month/year date of the observation;
  b. Age: the age of the observations;
  c. Year: the year of the observation;
  d. x: the number of immigrats arriving in Switzerland at the correspondent date of the corresponging age;	
  e. xlog: the log-transformed number of immigrats arriving in Switzerland at the correspondent date of the corresponging age;
  f. t: the total number of time periods, t=1,...,T;
  g. trend: the time trend obtained by t/T, where T is the total number of periods;

PROGRAMS USED

All the computations have been performed using the R statistical software.
The source codes have been created using Sweave (files with extension .Rnw) and knitr, which enables the embedding of R code within LaTeX documents. All the pieces of code are included using R chunks and are displayed within the following symbols:

<<>>=
@

HOW TO REPRODUCE THE RESULTS

In order to reproduce the results an updated version of R should be installed. Make sure all the required packages are installed and loaded using the command "library()". The path/to/file should be specify for each dataset leaded after the command "read.csv()".





