# HedgeFundML
Hedge Fund testing harness for managing portfolios utilizing Machine Learning for security selection (where appropriate).

Features:
- start fund on 1/1/2020 with $1B seed capital
- +$1B additional seed capital injections on 1/1/2021 & 1/1/2022
- tradable securities selected from Dow 30, Nasdaq 100 & S&P 500 (528 unique; less 8 partial)
- maintain portfolio with 50-100 "best" stocks
- maintain diversification with 5-10 different industry sectors
- generate Buy-and-Hold P/L % statistics for EOY 2020, 2021 & YTD 2022 for all 520 securities (long-only)
- generate "opportunity" (measured move) P/L statistics using fractal-based reversal pivot points for all 520 securities (long-only)
- generate ML stock selection targests based on daily/weekly/monthly % gain statistics (long-only)
- maintain 1%-5% minimum monthly profit (stop at second consecutive losing month or if drawdown exceeds 10%)
- features/strategies based on CCI, DC, KR, LRBO, RSI, VWAP, Half/SuperTrend, Volume, Velocity/Momentum, etc.
- 0% commissions assumed (though can/should be accounted for at some point)
- whole share purchases-only (no fractional; round quantities down to nearest 100?)
- generate portfolio scenarios that rebalance daily, weekly, monthly and quarterly
- split-handling?
- dividend income inclusion?
- simulate fills based on iceberg orders?
