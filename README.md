# CryptoVault Starter

Mobile-friendly prototype for a crypto product with:
- Crypto market prices (CoinGecko public endpoint; availability/rate limits can change)
- Virtual-money paper trading (no real orders)
- Savings goal tracking
- Retirement projection calculator
- Local browser storage for prototype data

## Run / publish
1. Create a new GitHub repository named `cryptovault`.
2. Upload `index.html` and `README.md` from this project.
3. For the easiest first deployment, import the repository into Vercel and deploy it as a static site.
4. Open the deployed site and test it on mobile.

## Important scope
This starter does **not** execute real-money trades, accept deposits, custody crypto, or manage retirement accounts. Trading and savings state is stored in the user's browser and is not a secure multi-user database. Do not use it for real funds or as a public financial service without redesigning the security and backend architecture.

## Moving toward real trading
A production version should generally integrate with a regulated/appropriate exchange or brokerage through official APIs, preferably using a non-custodial model. Never ask users to paste exchange passwords or withdrawal-enabled API keys into the browser. Keep credentials server-side, restrict API permissions, and get a security review. Public account creation, order execution, deposits, custody, yield products, and retirement-related services can trigger legal, licensing, KYC/AML, privacy, tax, and consumer-protection requirements depending on jurisdictions and product design.

## Free-start note
The prototype can be created and tested with free developer tools, but market-data limits, hosting limits, database services, exchange accounts, and real trading may require fees. No returns are guaranteed.
