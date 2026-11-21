# ipo-data

Indian IPO data (GMP, dates, subscription, issue details) as JSON, used by the IPO Tracker app.
Updated automatically by a scheduled workflow every 3 hours from 9 AM to 9 PM IST.
Source: investorgain.com. **Do not edit by hand**: changes are overwritten on the next run.

| File | Contents |
|---|---|
| [`v1/index.json`](v1/index.json) | Every current IPO: status, GMP, price, dates, subscription, listing |
| `v1/ipo/<id>.json` | One IPO in full: GMP history, dates, lot sizes, financials, KPIs, registrar |

Raw URLs:

```
https://raw.githubusercontent.com/Kingsman16781/ipo-data/main/v1/index.json
https://raw.githubusercontent.com/Kingsman16781/ipo-data/main/v1/ipo/<id>.json
```

GMP (grey market premium) is unofficial and indicative only. Not investment advice.
