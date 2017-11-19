# pinescript-adr
Average Daily Range (ADR) Indicator for TradingView

This script is based on the "Best ADR Indicator for MT4" described at https://www.fxdayjob.com/best-adr-indicator-mt4.

## Inputs

- `Number of ADR Back`:  Set the number of calendar days back to plot historical ADR. The default value is 7.  Non-trading days are not taken into account.  A value of 7, for example, would display only 5 ADR for a 24x5 market.
- `Number of AWR Back`: Set the number of calendar weeks back to plot historical AWR. The default value is 0.
- `Number of AMR Back`: Set the number of calendar months back to plot historical AMR. The default value is 0.
- `Number of AYR Back`: Set the number of calendar years back to plot historical AYR. The default value is 0.
- `ADR Length parameter`: Set the length parameter of ADR. The default value is 1.
- `WDR Length parameter`: Set the length parameter of AWR. The default value is 1.
- `MDR Length parameter`: Set the length parameter of AMR. The default value is 1.
- `YDR Length parameter`: Set the length parameter of AYR. The default value is 1.

## See also

- https://www.fxdayjob.com/best-adr-indicator-mt4
- http://pivotboss.com/2012/07/05/find-the-best-real-time-targets/
- https://www.jarrattdavis.com/average-daily-range-2/
