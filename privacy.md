# Privacy Policy

**App:** DCA — Strategy Backtester
**Effective date:** 2026-04-26
## Summary

DCA does not collect, store, or transmit any personal data. Everything you do in the app stays on your device.

## What we collect

**Nothing.**

DCA has no user accounts, no sign-in, no analytics SDKs, no advertising SDKs, no crash reporters, and no telemetry of any kind. We do not have a backend server, and we do not see, store, or process any information about you or how you use the app.

## What stays on your device

All of the following are written only to your device's local storage and never leave it:

- Saved DCA calculation results (asset, plan parameters, transactions, equity curve, summary)
- Your last-used DCA setup parameters (amount, frequency, dates, execution time)
- The cached list of supported tickers

If you delete the app, this data is removed with it. If you restore your device from an iCloud backup, this data may be restored alongside the rest of your apps; that backup is governed by Apple's iCloud privacy terms, not ours.

## Network requests

The app makes anonymous outbound HTTPS requests to public sources to fetch market data and the supported-ticker list. These requests do **not** include any identifier, account information, advertising ID, or usage data. They contain only the ticker symbol and date range you are calculating against.

The endpoints contacted are:

| Purpose | Endpoint | Provider |
| --- | --- | --- |
| Historical daily prices | `query1.finance.yahoo.com/v8/finance/chart/<symbol>` | Yahoo Finance (publicly accessible) |
| S&P 500 constituents refresh | `raw.githubusercontent.com/datasets/s-and-p-500-companies/main/data/constituents.csv` | GitHub-hosted public dataset |

These third-party services may log standard request metadata such as your IP address and user-agent string; that handling is governed by their own privacy policies, not ours. We do not receive or store any of that data.

## Children

DCA is not directed at children. It does not collect any personal information from anyone, including children.

## Third-party services

DCA does not embed any third-party SDKs. It does not use Google Analytics, Firebase, Crashlytics, Facebook SDK, AdMob, or any similar service.

## Your rights

Because we collect no data, there is nothing for you to access, export, correct, or delete on our side. To remove the data the app stores on your device, delete the app from your device.

## Changes to this policy

If this policy ever changes, the new version will be published in this file alongside the date it took effect. Material changes will also be reflected in the App Store listing for the next app release.
