# Joel Shore

AI & Software Engineer. I find where a business is slow and build the fix.

I'm an AI & Software Engineer at Gtech (May 2024 to present), based in Birmingham, UK. I work with management to find where operations slow down, then build the software that removes the slowdown: internal tools, API integrations, data pipelines and AI automation, from the database through to the UI. I hold a BSc in Computer Science with First Class Honours from Newman University (2026).

I like owning a problem end to end: understanding the business process, structuring the data, building the system and shipping it with tests. I use Claude Code for agentic development, and the first project below is built for Claude Code agents to use directly over MCP.

## Stack

![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=white)
![PHP](https://img.shields.io/badge/PHP-777BB4?logo=php&logoColor=white)
![Go](https://img.shields.io/badge/Go-00ADD8?logo=go&logoColor=white)
![Rust](https://img.shields.io/badge/Rust-000000?logo=rust&logoColor=white)
![SolidJS](https://img.shields.io/badge/SolidJS-2C4F7C?logo=solid&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?logo=postgresql&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white)

- **Languages:** Python, TypeScript/JavaScript, PHP, Go, Rust, SQL
- **Web and APIs:** SolidJS, React, Next.js, FastAPI, Django, Gin/Echo, GraphQL (gqlgen), REST
- **Data and ML:** PostgreSQL, MySQL/MariaDB, Redis, PyTorch, scikit-learn, Pandas, NumPy, NLTK
- **Infrastructure:** Linux, Docker, Caddy, Nginx, CI pipelines
- **AI tooling:** Claude Code, MCP servers, LLM integration

## Featured projects

<!-- TODO: link this heading to the repo once the repo is public. It may be published under a new name. -->
### ticketing

A ticket tracker with two queues: tickets that Claude Code files from audits and reviews, and tickets people create by hand. Go and gqlgen on Postgres at the back, SolidJS at the front, plus a REST API and an MCP server so Claude Code agents can file, claim and work tickets themselves.

`Go` `GraphQL` `PostgreSQL` `SolidJS` `MCP`

<!-- TODO: link this heading to the repo once the repo is public. -->
### trading_platform

A backtesting and paper-trading platform for systematic crypto strategies across spot, perpetuals and options, built to test and falsify strategies. Orders fill on the next bar to prevent lookahead, spread, slippage and commission are charged on every fill by default, and pre-trade risk checks cap notional, leverage and drawdown. Backed by a large pytest suite. It has never traded real money and has no path to a live venue.

`Python` `pytest` `PostgreSQL`

### [trading-bot-initial](https://github.com/joelshore4747/trading-bot-initial)

A rules-based scanner for ICT-style trading setups across forex, gold, crypto and indices. A Rust engine detects and scores setups, a Go API serves them over REST and WebSocket, and staged alerts go to Telegram and Discord. It produces alerts and paper-trading results for a human to act on; it does not place trades.

`Rust` `Go` `PostgreSQL` `Redis`

### [uni-fall-monitor](https://github.com/joelshore4747/uni-fall-monitor)

My dissertation project for the BSc (First Class Honours): fall detection and human activity recognition from a phone's motion sensors. Gyroscope data goes from the phone to a server database, a Python ML backend classifies the user's movement, and a web admin page shows the results. It reached about 60% accuracy on roughly 100 self-collected samples, and accuracy improves as more data is collected. The full pipeline, admin app and API are in [edge-har-fall-detection-archive](https://github.com/joelshore4747/edge-har-fall-detection-archive).

`Python` `SolidJS` `PostgreSQL` `Docker` `Caddy`

### More

- [nlp_language_tutor](https://github.com/joelshore4747/nlp_language_tutor): scores short learner answers with language ID, syntax checks, semantic similarity, NER and fluency scoring. FastAPI backend and SolidJS UI.
- [airbnb-deep-learning](https://github.com/joelshore4747/airbnb-deep-learning): Keras models that combine tabular features (MLP) with listing text (bidirectional LSTM) to predict Airbnb nightly prices and classify premium listings.

## Contact

- LinkedIn: [linkedin.com/in/joelshore](https://www.linkedin.com/in/joelshore/)
- Email: [joel.careers@shoremail.cc](mailto:joel.careers@shoremail.cc)
