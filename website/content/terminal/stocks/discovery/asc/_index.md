```
usage: asc [-n NUM] [--export {csv,json,xlsx}] [-h]
```

Print up to 25 small cap stocks with earnings growth rates better than 25%. [Source: [Yahoo Finance](https://finance.yahoo.com/screener/predefined/aggressive_small_caps)]

```
optional arguments:
  -l LIMIT, --limit LIMIT
                        Limit of stocks to display. (default: 5)
  -h, --help            show this help message (default: False)
  --export {csv,json,xlsx}
                        Export raw data into csv, json, xlsx (default: )
```

Example:
```
2022 Feb 16, 03:51 (✨) /stocks/disc/ $ asc -l 25
                                                                 High Growth Small Caps
┏━━━━━━━━┳━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━┳━━━━━━━━━━━━━━━━━━┳━━━━━━━━┳━━━━━━━━━━┳━━━━━━━━┳━━━━━━━━━━━━━━━━━━━┳━━━━━━━━━━━━┳━━━━━━━━━━━━━━━━┓
┃ Symbol ┃ Name                                      ┃ Price (Intraday) ┃ Change ┃ % Change ┃ Volume ┃ Avg Vol (3 month) ┃ Market Cap ┃ PE Ratio (TTM) ┃
┡━━━━━━━━╇━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━╇━━━━━━━━━━━━━━━━━━╇━━━━━━━━╇━━━━━━━━━━╇━━━━━━━━╇━━━━━━━━━━━━━━━━━━━╇━━━━━━━━━━━━╇━━━━━━━━━━━━━━━━┩
│ RIDE   │ Lordstown Motors Corp.                    │ 3.41             │ 0.34   │ +11.07%  │ 6.245M │ 7.056M            │ 655.508M   │                │
├────────┼───────────────────────────────────────────┼──────────────────┼────────┼──────────┼────────┼───────────────────┼────────────┼────────────────┤
│ SKLZ   │ Skillz Inc.                               │ 4.56             │ 0.59   │ +14.86%  │ 13.14M │ 13.946M           │ 1.861B     │                │
├────────┼───────────────────────────────────────────┼──────────────────┼────────┼──────────┼────────┼───────────────────┼────────────┼────────────────┤
│ BGCP   │ BGC Partners, Inc.                        │ 4.61             │ 0.33   │ +7.71%   │ 5.293M │ 2.116M            │ 1.7B       │ 40.09          │
├────────┼───────────────────────────────────────────┼──────────────────┼────────┼──────────┼────────┼───────────────────┼────────────┼────────────────┤
│ TIGR   │ UP Fintech Holding Limited                │ 4.92             │ 0.52   │ +11.82%  │ 2.734M │ 4.485M            │ 798.885M   │ 24.85          │
├────────┼───────────────────────────────────────────┼──────────────────┼────────┼──────────┼────────┼───────────────────┼────────────┼────────────────┤
│ EDIT   │ Editas Medicine, Inc.                     │ 16.65            │ 0.86   │ +5.45%   │ 1.386M │ 1.774M            │ 1.139B     │                │
├────────┼───────────────────────────────────────────┼──────────────────┼────────┼──────────┼────────┼───────────────────┼────────────┼────────────────┤
│ DM     │ Desktop Metal, Inc.                       │ 4.36             │ 0.41   │ +10.38%  │ 5.407M │ 5.977M            │ 1.356B     │                │
├────────┼───────────────────────────────────────────┼──────────────────┼────────┼──────────┼────────┼───────────────────┼────────────┼────────────────┤
│ APRN   │ Blue Apron Holdings, Inc.                 │ 6.27             │ 0.35   │ +5.91%   │ 1.29M  │ 1.444M            │ 198.724M   │                │
├────────┼───────────────────────────────────────────┼──────────────────┼────────┼──────────┼────────┼───────────────────┼────────────┼────────────────┤
│ CRK    │ Comstock Resources, Inc.                  │ 7.30             │ -0.14  │ -1.88%   │ 4.106M │ 3.487M            │ 1.7B       │                │
├────────┼───────────────────────────────────────────┼──────────────────┼────────┼──────────┼────────┼───────────────────┼────────────┼────────────────┤
│ GOEV   │ Canoo Inc.                                │ 6.22             │ 0.27   │ +4.54%   │ 1.97M  │ 5.864M            │ 1.485B     │                │
├────────┼───────────────────────────────────────────┼──────────────────┼────────┼──────────┼────────┼───────────────────┼────────────┼────────────────┤
│ BEST   │ BEST Inc.                                 │ 1.12             │ 0.09   │ +8.74%   │ 1.633M │ 1.706M            │ 435.344M   │                │
├────────┼───────────────────────────────────────────┼──────────────────┼────────┼──────────┼────────┼───────────────────┼────────────┼────────────────┤
│ BLU    │ BELLUS Health Inc.                        │ 7.06             │ 0.00   │ 0.00%    │ 1.344M │ 3.323M            │ 751.163M   │                │
├────────┼───────────────────────────────────────────┼──────────────────┼────────┼──────────┼────────┼───────────────────┼────────────┼────────────────┤
│ HYLN   │ Hyliion Holdings Corp.                    │ 4.22             │ 0.23   │ +5.76%   │ 1.988M │ 2.863M            │ 731.381M   │                │
├────────┼───────────────────────────────────────────┼──────────────────┼────────┼──────────┼────────┼───────────────────┼────────────┼────────────────┤
│ VLDR   │ Velodyne Lidar, Inc.                      │ 4.25             │ 0.31   │ +7.87%   │ 5.567M │ 5.266M            │ 841.793M   │                │
├────────┼───────────────────────────────────────────┼──────────────────┼────────┼──────────┼────────┼───────────────────┼────────────┼────────────────┤
│ HUYA   │ HUYA Inc.                                 │ 6.09             │ 0.44   │ +7.79%   │ 1.952M │ 2.844M            │ 1.445B     │ 8.13           │
├────────┼───────────────────────────────────────────┼──────────────────┼────────┼──────────┼────────┼───────────────────┼────────────┼────────────────┤
│ PEI    │ Pennsylvania Real Estate Investment Trust │ 0.90             │ 0.03   │ +3.38%   │ 329076 │ 752054            │ 74.214M    │                │
├────────┼───────────────────────────────────────────┼──────────────────┼────────┼──────────┼────────┼───────────────────┼────────────┼────────────────┤
│ APPH   │ AppHarvest, Inc.                          │ 3.12             │ 0.09   │ +2.97%   │ 782043 │ 1.479M            │ 314.945M   │                │
├────────┼───────────────────────────────────────────┼──────────────────┼────────┼──────────┼────────┼───────────────────┼────────────┼────────────────┤
│ FSM    │ Fortuna Silver Mines Inc.                 │ 3.66             │ 0.00   │ 0.00%    │ 3.637M │ 4.569M            │ 1.068B     │ 12.93          │
├────────┼───────────────────────────────────────────┼──────────────────┼────────┼──────────┼────────┼───────────────────┼────────────┼────────────────┤
│ BGFV   │ Big 5 Sporting Goods Corporation          │ 18.26            │ 0.94   │ +5.43%   │ 603600 │ 1.137M            │ 407.395M   │ 3.97           │
├────────┼───────────────────────────────────────────┼──────────────────┼────────┼──────────┼────────┼───────────────────┼────────────┼────────────────┤
│ ZEV    │ Lightning eMotors, Inc.                   │ 5.49             │ 0.40   │ +7.86%   │ 579157 │ 1.412M            │ 411.507M   │                │
├────────┼───────────────────────────────────────────┼──────────────────┼────────┼──────────┼────────┼───────────────────┼────────────┼────────────────┤
│ DNMR   │ Danimer Scientific, Inc.                  │ 4.07             │ 0.41   │ +11.20%  │ 4.452M │ 3.75M             │ 408.4M     │                │
├────────┼───────────────────────────────────────────┼──────────────────┼────────┼──────────┼────────┼───────────────────┼────────────┼────────────────┤
│ ORPH   │ Orphazyme A/S                             │ 2.13             │ 0.13   │ +6.50%   │ 553864 │ 989978            │ 74.448M    │                │
├────────┼───────────────────────────────────────────┼──────────────────┼────────┼──────────┼────────┼───────────────────┼────────────┼────────────────┤
│ REAL   │ The RealReal, Inc.                        │ 9.89             │ 0.70   │ +7.62%   │ 2.514M │ 3.049M            │ 913.715M   │                │
├────────┼───────────────────────────────────────────┼──────────────────┼────────┼──────────┼────────┼───────────────────┼────────────┼────────────────┤
│ USA    │ Liberty All-Star Equity Fund              │ 7.52             │ 0.12   │ +1.62%   │ 796155 │ 1.374M            │ 1.683B     │ 2.88           │
├────────┼───────────────────────────────────────────┼──────────────────┼────────┼──────────┼────────┼───────────────────┼────────────┼────────────────┤
│ DHY    │ Credit Suisse High Yield Bond Fund, Inc.  │ 2.23             │ -0.00  │ -0.20%   │ 509800 │ 335704            │ 230.836M   │ 6.39           │
├────────┼───────────────────────────────────────────┼──────────────────┼────────┼──────────┼────────┼───────────────────┼────────────┼────────────────┤
│ CENX   │ Century Aluminum Company                  │ 20.35            │ 1.26   │ +6.60%   │ 1.887M │ 1.268M            │ 1.834B     │                │
└────────┴───────────────────────────────────────────┴──────────────────┴────────┴──────────┴────────┴───────────────────┴────────────┴────────────────┘
```