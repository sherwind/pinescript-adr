# pinescript-adr
Average Daily Range (ADR) Indicator for TradingView

This script is based on the "Best ADR Indicator for MT4" described at https://www.fxdayjob.com/best-adr-indicator-mt4.

## Inputs

- `ADR display limit`: Set the number of historical ADR to display. The default value is 7 calendar days. Non-trading days are not taken into account. A value of 7, for example, would display only 5 ADR for a 24x5 market.
- `AWR display limit`: Set the number of historical AWR to display. The default value is 0 calendar weeks.
- `AMR display limit`: Set the number of historical AMR to display. The default value is 0 calendar months.
- `AYR display limit`: Set the number of historical AYR to display. The default value is 0 calendar years.
- `ADR Length parameter`: Set the length parameter of ADR. The default value is 5.
- `WDR Length parameter`: Set the length parameter of AWR. The default value is 5.
- `MDR Length parameter`: Set the length parameter of AMR. The default value is 1.
- `YDR Length parameter`: Set the length parameter of AYR. The default value is 1.

## See also

- https://www.fxdayjob.com/best-adr-indicator-mt4
- http://pivotboss.com/2012/07/05/find-the-best-real-time-targets/
- https://www.jarrattdavis.com/average-daily-range-2/
