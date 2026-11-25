# Vinayak Deshmuk

India. I build AI-assisted software, developer tools, and data products with TypeScript and Python. I like turning complex workflows into useful, understandable tools.

## Model training / optimization

I don't have a published fine-tuned model yet — I'm working toward that now, starting with the Halo post-training competition. What I can show today:

- **Live Polymarket trading bot (Python)** — a real-money BTC up/down bot running on an EC2 box, trading every 15 minutes. 215 settled trades, 118 wins / 97 losses, net +$31.16, tallied on on-chain balance. The backtests behind it cover 400+ days of 15-minute windows, thousands of trades, with the same entry rules.
- **[Halo SFT demo](https://github.com/Vinayak19112003/halo-sft-demo)** — real Qwen3-0.6B LoRA SFT on CPU (TRL, Halo needs a GPU): 100 chat examples, 12 steps, loss 2.36 → 0.85, eval 1.02. Also a tiny 20M-param smoke test (loss 11.93 → 10.96). GPU run (Qwen3-4B LoRA, Halo) queued on Kaggle.
- **Python data pipelines** — live order-book collection, one-second market snapshots, and backtest harnesses built for the bot above.

## Selected work

- **[TeklaMCP](https://github.com/Vinayak19112003/TeklaMCP)** — Prototype for generating Tekla OpenAPI code from structured building requirements with an AI-assisted pipeline.
- **[TradeZend](https://github.com/Vinayak19112003/tradezend)** — Trading journal with an AI-assisted import flow that extracts structured trades from CSV, PDF, and image inputs.
- **[QuantMath](https://github.com/Vinayak19112003/quantmath-phase1)** — Interactive math labs for learning foundations used in quantitative finance.
- **[Polymarket order book collector](https://github.com/Vinayak19112003/Polymarket-orderbooks)** — Python tooling for live order books and one-second market snapshots.

## Open source

12 merged PRs in other people's repos:

- **[pylint-dev/pylint #11573](https://github.com/pylint-dev/pylint/pull/11573)** · merged — Fixed arguments-differ (W0221) missing positional-only parameters.
- **[pylint-dev/pylint #11481](https://github.com/pylint-dev/pylint/pull/11481)** · merged — Fixed a crash in import-private-name on attribute access rooted at a non-Name node.
- **[scikit-bio/scikit-bio #2604](https://github.com/scikit-bio/scikit-bio/pull/2604)** · merged — Corrected the dirmult_ttest q-value calculation description.
- **[narwhals-dev/narwhals #3998](https://github.com/narwhals-dev/narwhals/pull/3998)** · merged — Fixed concat(how="diagonal") on DuckDB to use the relations' own connection.
- **[skfolio/skfolio #507](https://github.com/skfolio/skfolio/pull/507)** · merged — Bias-corrected EWMA beta accumulators for late-listed assets.
- **[skfolio/skfolio #338](https://github.com/skfolio/skfolio/pull/338)** · merged — Rejected MultiPeriodPortfolio mutations that misalign sample_weight.
- **[pdm-project/pdm #3898](https://github.com/pdm-project/pdm/pull/3898)** · merged — Made `pdm install` interruptible with Ctrl+C.
- **[online-ml/river #2017](https://github.com/online-ml/river/pull/2017)** · merged — Rejected constant scores in check_roc_auc.
- **[NodeSecure/js-x-ray #720](https://github.com/NodeSecure/js-x-ray/pull/720)** · merged — Added an optional weak PBKDF2 detection probe to the JavaScript security scanner, with tests and documentation.
- **[skrub-data/skrub #2319](https://github.com/skrub-data/skrub/pull/2319)** · merged — Fixed deduplicate failing on missing values.
- **[aeon-toolkit/aeon #3850](https://github.com/aeon-toolkit/aeon/pull/3850)** · merged — Stopped COPOD predict from modifying the fitted PyOD model.
- **[eslint-stylistic/eslint-stylistic #1289](https://github.com/eslint-stylistic/eslint-stylistic/pull/1289)** · merged — Added a jsx option for JSX-specific indent size.

Also merged: **[XSpoonAi/spoon-awesome-skill #22](https://github.com/XSpoonAi/spoon-awesome-skill/pull/22)** — Contributed a read-only AI DeFi safety and swap simulation skill.

**Working with:** TypeScript · Python · React/Next.js · AI APIs · data pipelines

I share what I build and learn on [X](https://x.com/vinayakbuild).
