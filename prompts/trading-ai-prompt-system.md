# Trading AI Prompt System
## Research, Analysis & Journaling — 40 Expert Prompts

**Version:** 1.0 | **Date:** May 2026 | **Price:** $29
**Works with:** ChatGPT-4/5, Claude 4, Gemini 3 Flash

---

## How to Use This System

1. **Copy** any prompt below into your AI tool of choice
2. **Replace** bracketed variables `[LIKE_THIS]` with your specific data
3. **Iterate** — follow up with questions to drill deeper
4. **Save** outputs to your trading journal for reference

### Pro Tips
- Start a **new chat** for each analysis to avoid context contamination
- Set temperature to **0.3-0.5** for consistent, analytical outputs
- Use **system prompts** (if available) to set the AI's role before each session
- Always **verify** data points — AI can hallucinate numbers

---

## Table of Contents
1. [Market Overview & Macro Analysis](#1-market-overview--macro-analysis)
2. [Stock Research & Fundamental Analysis](#2-stock-research--fundamental-analysis)
3. [Technical Analysis & Chart Patterns](#3-technical-analysis--chart-patterns)
4. [Risk Management & Position Sizing](#4-risk-management--position-sizing)
5. [Trade Planning & Execution](#5-trade-planning--execution)
6. [Trading Journal Analysis & Review](#6-trading-journal-analysis--review)
7. [Earnings & Event Analysis](#7-earnings--event-analysis)
8. [Options & Derivatives Analysis](#8-options--derivatives-analysis)

---

## 1. Market Overview & Macro Analysis

### Prompt 1: Daily Market Briefing
```
Act as a senior market strategist at a hedge fund. Provide a concise daily market briefing covering:

1. Key indices performance (S&P 500, Nasdaq, DOW, HK Hang Seng) — yesterday's close and key levels
2. Major macro drivers: interest rates, inflation data, geopolitical events
3. Sector rotation trends — which sectors are leading/lagging
4. Key economic events scheduled for today/this week
5. Market sentiment indicators (VIX, put/call ratio, advance/decline line)

Format as a structured briefing with bullet points. Flag any anomalies or unusual patterns.
Focus on actionable insights, not generic commentary.
```

### Prompt 2: Sector Rotation Analysis
```
Act as a sector rotation analyst. Analyze the current sector rotation cycle:

1. Identify which sectors are in early, mid, and late cycle phases
2. Compare sector performance vs. their 200-day moving averages
3. Identify relative strength/weakness leaders and laggards
4. Map current rotation to historical patterns (2003, 2009, 2020 cycles)
5. Recommend sector allocation shifts based on the current cycle position

Use [CURRENT_DATE] as the reference date. Cite specific ETFs as proxies (XLK, XLF, XLE, etc.).
```

### Prompt 3: Central Bank Policy Impact
```
Act as a macro strategist specializing in central bank policy analysis.

Given the following recent Fed/[BANK] decision:
[SUMMARIZE_DECISION_OR_RATE_MOVE]

Analyze:
1. Immediate market impact (rates, FX, equities, commodities)
2. Forward guidance interpretation — what is the market pricing in for next 3 meetings?
3. Historical comparison — similar policy moves and subsequent market performance
4. Sector-specific implications (financials, real estate, tech, exports)
5. Trading strategy recommendations for the next 30-90 days

Be specific about instruments and timeframes.
```

### Prompt 4: Geopolitical Risk Assessment
```
Act as a geopolitical risk analyst for an institutional portfolio.

Given this development:
[DESCRIBE_GEOPOLITICAL_EVENT]

Assess:
1. Direct market impact channels (energy, supply chains, FX, risk sentiment)
2. Historical precedents — similar events and market reactions
3. Probability-weighted scenarios (base case, escalation, de-escalation)
4. Portfolio hedging recommendations
5. Specific assets/sectors to overweight/underweight

Quantify impacts where possible (e.g., "Brent could move $5-8/barrel in escalation scenario").
```

---

## 2. Stock Research & Fundamental Analysis

### Prompt 5: Company Deep-Dive Research
```
Act as an equity research analyst covering [SECTOR] sector. Conduct a comprehensive deep-dive on [TICKER/COMPANY]:

1. Business model — how do they make money? Revenue streams, customer base, moat
2. Financial health — revenue growth, margins, cash flow, debt levels, ROIC trend (last 5 years)
3. Competitive positioning — market share, moat durability, threat of disruption
4. Growth catalysts — near-term (0-12mo) and long-term (1-5yr)
5. Key risks — regulatory, competitive, operational, financial
6. Valuation — current multiples vs. historical averages and peer comparison
7. Analyst consensus — price targets, recent upgrades/downgrades

Output as a structured research memo. Include a "bull case / bear case" summary.
Flag any red flags or areas needing further investigation.
```

### Prompt 6: Financial Statement Analysis
```
Act as a forensic accountant and equity analyst. Analyze the following financial data for [TICKER]:

[INSERT_KEY_FINANCIAL_METRICS_OR_PASTE_EXCERPT_FROM_10K/10Q]

Perform:
1. Horizontal analysis — year-over-year trends in revenue, margins, expenses
2. Vertical analysis — common-size income statement and balance sheet
3. Cash flow quality — operating vs. reported earnings, free cash flow conversion
4. Balance sheet stress test — debt maturity profile, liquidity ratios, covenant risk
5. Red flag detection — unusual items, one-time charges, accounting changes
6. Quality of earnings score (1-10) with justification

Focus on what the numbers are NOT saying. What questions would you ask management in an earnings call?
```

### Prompt 7: Peer Comparison & Relative Value
```
Act as a quantitative analyst. Compare [TICKER] against its top [N] peers:
[LIST_PEERS_OR_SECTOR]

Create a comparison matrix across:
1. Valuation multiples (P/E, P/S, EV/EBITDA, P/B) — current and 5-year average
2. Growth metrics (revenue CAGR, earnings CAGR, forward growth estimates)
3. Profitability (gross margin, operating margin, ROE, ROIC)
4. Financial health (debt/equity, interest coverage, current ratio)
5. Market performance (1Y/3Y/5Y returns, volatility, beta)

Identify:
- The cheapest/most expensive on each metric
- The best risk-adjusted value proposition
- Any anomalies or outliers requiring explanation
- A ranked recommendation (1 to N) with rationale
```

### Prompt 8: Moat & Competitive Advantage Assessment
```
Act as a strategy consultant specializing in competitive moat analysis.

Evaluate [COMPANY/TICKER] using Warren Buffett's moat framework:

1. Intangible assets — brand power, patents, regulatory licenses
2. Switching costs — how hard is it for customers to leave?
3. Network effects — does the product improve with more users?
4. Cost advantages — scale, process, access to inputs
5. Efficient scale — is the market served by limited competitors?

Score each dimension 1-10. Provide a composite moat rating.
Compare to the strongest moat in the sector.
Identify any moat erosion trends.
```

---

## 3. Technical Analysis & Chart Patterns

### Prompt 9: Multi-Timeframe Technical Analysis
```
Act as a technical analyst using multi-timeframe analysis. Analyze [TICKER] across daily, weekly, and monthly timeframes:

For each timeframe, assess:
1. Trend direction and strength (higher highs/lows or not)
2. Key support and resistance levels (specific price levels)
3. Moving average alignment (20, 50, 100, 200 EMA/SMA)
4. Volume profile — is volume confirming the trend?
5. Key indicators: RSI (14), MACD, Bollinger Bands position

Synthesize across timeframes:
- What is the confluence of signals?
- What is the highest-probability near-term scenario?
- What level would invalidate the bullish/bearish case?

Provide specific entry, stop-loss, and target price levels.
```

### Prompt 10: Chart Pattern Recognition & Playbook
```
Act as a chart pattern specialist. I'm looking at [TICKER] and I see the following pattern:
[DESCRIBE_PATTERN: e.g., "ascending triangle on daily, breaking above $X resistance with volume"]

Provide:
1. Pattern identification confirmation — is this a valid [PATTERN_NAME]?
2. Historical success rate and average move for this pattern
3. Key confirmation signals to watch for (volume, breakout level, retest)
4. Price target calculation (measured move)
5. Stop-loss placement and invalidation level
6. Timeframe for the expected move
7. Alternative scenario if pattern fails

Include a "trade setup" summary with exact levels.
```

### Prompt 11: Divergence Analysis
```
Act as a technical analyst specializing in divergence trading.

Analyze [TICKER] for the following divergences:
[DESCRIBE_PRICE_ACTION_AND_INDICATOR_BEHAVIOR]

For each divergence found:
1. Type: regular vs. hidden, bullish vs. bearish
2. Timeframe and duration of divergence
3. Strength score (weak/medium/strong) based on:
   - Number of peaks/troughs diverging
   - Indicator extreme readings
   - Volume confirmation
4. Historical reliability of this specific divergence type
5. Entry strategy, stop-loss, and profit targets
6. Time decay — how long until this divergence likely resolves?

Focus on the strongest signal. Provide a clear trade plan.
```

### Prompt 12: Volume Profile & Market Structure
```
Act as an auction market theorist. Analyze [TICKER] using volume profile and market structure:

1. Value area (VAH/VAL/POC) — where is price relative to value?
2. Volume nodes — high-volume acceptance zones vs. low-volume rejection zones
3. Market profile — is the market in balance or imbalance?
4. Acceptance vs. rejection at current levels
5. Auction theory interpretation — where is price likely to move next?
6. Specific levels for entry, stop, and target

Provide a "market narrative" — what is the auction telling us about buyer/seller behavior?
```

---

## 4. Risk Management & Position Sizing

### Prompt 13: Portfolio Risk Audit
```
Act as a risk manager at a multi-strategy fund. Audit the following portfolio:
[LIST_POSITIONS_WITH_SIZES_AND_COST_BASIS]

Analyze:
1. Concentration risk — top 5 positions as % of portfolio, sector exposure
2. Correlation risk — how correlated are the positions? (estimate correlations)
3. Beta exposure — portfolio beta vs. benchmark
4. Drawdown analysis — worst-case scenario based on historical volatility
5. VaR (Value at Risk) estimate — 95% confidence, 1-month horizon
6. Tail risk — exposure to black swan events

Provide specific risk reduction recommendations:
- Which positions to reduce/eliminate
- Suggested position size limits
- Hedging strategies (options, inverse ETFs, cash allocation)
- Rebalancing triggers
```

### Prompt 14: Position Sizing Calculator
```
Act as a quantitative risk manager. Calculate optimal position size using multiple methods:

Portfolio details:
- Total capital: $[AMOUNT]
- Risk per trade: [X]% of portfolio
- Entry price: $[PRICE]
- Stop-loss price: $[PRICE]
- Target price: $[PRICE]
- Position type: [LONG/SHORT/CALL/PUT]

Calculate using:
1. Fixed fractional (risk-based): shares = (capital × risk%) / (entry - stop)
2. Kelly Criterion: f* = (win% × avg_win - loss% × avg_loss) / avg_win
3. Volatility-based (ATR): position scaled to 1-2% of portfolio volatility
4. Fixed ratio method (Ryan Jones)

Provide:
- Recommended position size (shares and $ value)
- R-multiple of the trade
- Maximum acceptable position size
- A "conservative / moderate / aggressive" sizing recommendation
```

### Prompt 15: Correlation & Diversification Analysis
```
Act as a portfolio construction specialist. Analyze the correlation structure of:
[List assets/ETFs in portfolio]

1. Create a correlation matrix (estimate based on historical data)
2. Identify hidden correlations — positions that seem different but move together
3. Calculate effective diversification ratio
4. Identify concentration blind spots
5. Recommend additions to improve diversification (uncorrelated assets)
6. Stress test: what happens to the portfolio in a 2008-style crisis?

Provide a "diversification score" and specific improvement actions.
```

### Prompt 16: Drawdown Recovery Plan
```
Act as a portfolio recovery specialist. My portfolio is down [X]% from peak.
Current portfolio: [LIST_POSITIONS]
Peak value: $[AMOUNT] | Current value: $[AMOUNT]

Create a recovery plan:
1. Diagnosis — what caused the drawdown? (market-wide, sector-specific, stock-specific, strategy failure)
2. Triage — which positions to cut immediately, which to hold, which to average down
3. Recovery timeline — realistic timeframe to break even based on historical data
4. Position sizing during recovery — reduce size by X% until recovered
5. Psychological framework — rules to prevent revenge trading
6. Specific action steps for the next 30 days

Be realistic about timelines. Most drawdowns take 2-3x longer to recover than expected.
```

---

## 5. Trade Planning & Execution

### Prompt 17: Trade Setup Generator
```
Act as a professional trader. Help me build a complete trade plan for:

Asset: [TICKER]
Direction: [LONG/SHORT]
Timeframe: [SCALP/DAY/SWING/POSITION]
Thesis: [BRIEF_DESCRIPTION_OF_THESIS]

Generate a structured trade plan with:
1. Entry criteria — exact conditions that must be met before entering
2. Entry price(s) — primary entry and any scale-in levels
3. Stop-loss — exact level and rationale
4. Profit targets — T1 (partial), T2 (partial), T3 (runner)
5. Position size — based on [X]% risk per trade
6. R-multiple — reward:risk ratio
7. Time stop — maximum holding period
8. Invalidation — what would prove this thesis wrong?
9. Pre-trade checklist (5 items to verify before clicking buy/sell)
10. Post-entry management rules (when to move stop, when to take partials)

Format as a printable trade card.
```

### Prompt 18: Catalyst Event Trading Plan
```
Act as an event-driven trader. I'm planning to trade around this event:
[DESCRIBE_EVENT: earnings, FDA decision, rate decision, product launch, etc.]
Asset: [TICKER] | Event Date: [DATE]

Provide:
1. Historical performance — how has this asset reacted to similar events?
2. Implied move — what is the options market pricing in? (straddle cost vs. expected move)
3. Pre-event positioning — what to do 1-5 days before
4. Event day strategy — specific entry/exit scenarios
5. Post-event scenarios:
   - Beat & raise: action plan
   - Beat & guide down: action plan
   - Miss: action plan
6. Risk management — position sizing reduction, hedging strategies
7. Alternative: "stay out" analysis — when is the safest trade to not trade?

Include a decision tree for event day execution.
```

### Prompt 19: Multi-Leg Trade Construction
```
Act as a derivatives strategist. Help me construct a multi-leg trade:

Base thesis: [DESCRIBE_THESIS]
Asset: [TICKER]
Current price: $[PRICE]
Time horizon: [DAYS/WEEKS]
Max capital: $[AMOUNT]

Design 3 trade structures:
1. Conservative — defined risk, lower reward
2. Moderate — balanced risk/reward
3. Aggressive — higher risk, higher reward

For each structure, specify:
- Exact legs (buy/sell specific strikes and expirations)
- Net debit/credit
- Max profit and max loss
- Breakeven points
- Probability of profit (estimate)
- Greeks (delta, theta, vega exposure)
- Management rules (when to adjust, roll, or close)

Rank the structures by risk-adjusted expected value.
```

### Prompt 20: Trade Journal Entry Template
```
Act as a trading psychologist and performance coach. Generate a comprehensive trade journal entry for this trade:

[PROVIDE_TRADE_DETAILS: asset, direction, entry, exit, P&L, timeframe, thesis]

Structure the journal entry with:
1. Trade metadata (date, asset, direction, size, P&L in $ and R)
2. Thesis — why did I take this trade? (pre-trade)
3. Execution quality — did I follow the plan? (yes/no with specifics)
4. Emotional state — what was I feeling? (fear, greed, FOMO, confidence, revenge)
5. Decision log — key decision points and what drove each decision
6. Outcome analysis — was the P&L a result of skill or luck?
7. Lessons learned — 3 specific takeaways
8. Process grade (A-F) — separate from P&L result
9. Improvement action — one specific thing to do differently next time

Make this a template I can reuse for every trade.
```

---

## 6. Trading Journal Analysis & Review

### Prompt 21: Weekly Performance Review
```
Act as a trading performance analyst. Analyze my trading journal data from this week:
[PASTE_WEEKLY_TRADE_DATA: date, asset, direction, entry, exit, P&L, R-multiple, notes]

Generate a weekly review report:
1. Summary stats: total P&L, win rate, avg R, best/worst trade, total trades
2. Performance by:
   - Asset/sector
   - Trade duration (scalp vs. swing vs. position)
   - Setup type
   - Time of day
3. Pattern detection:
   - Which setups are most profitable?
   - Which timeframes produce best R-multiples?
   - Any recurring mistakes?
4. Emotional analysis — are there patterns in trades taken when [emotion]?
5. Specific recommendations for next week:
   - What to do more of
   - What to stop doing
   - What to start doing
6. One metric to focus on improving next week

Be brutally honest. Identify leaks, not just celebrate wins.
```

### Prompt 22: Monthly Edge Identification
```
Act as a quantitative trading analyst. Analyze [N] trades from my journal:
[PASTE_MONTHLY_TRADE_DATA]

Identify my actual trading edge (not what I think my edge is):
1. Statistical edge — which specific setups have positive expected value?
2. Edge quantification:
   - Win rate by setup type
   - Average R by setup type
   - Expected value per trade by setup type
3. Edge degradation — is my edge getting stronger or weaker over time?
4. Market condition dependency — does my edge work in all regimes?
5. Sample size adequacy — do I have enough data to trust these conclusions?
6. Recommendations:
   - Double down on: [specific setups]
   - Reduce: [specific setups]
   - Eliminate: [specific setups]
   - Test: [new variations]

Present findings as a "trading edge report card."
```

### Prompt 23: Psychological Pattern Detection
```
Act as a trading psychologist. Analyze my trading journal for psychological patterns:
[PASTE_TRADE_DATA_WITH_NOTES_AND_EMOTION_TAGS]

Detect and analyze:
1. Revenge trading patterns — trades taken immediately after losses
2. FOMO entries — trades taken after watching an asset run without you
3. Premature exits — winning trades closed too early (calculate opportunity cost)
4. Holding losers — losing trades held too long (calculate drag on performance)
5. Position sizing inconsistencies — oversized trades after wins or losses
6. Time-based patterns — does performance vary by day of week, time of day?
7. Streak behavior — how do I perform after 3+ wins? After 3+ losses?

For each pattern found:
- Frequency (how often does it occur?)
- Cost (what is the average P&L impact?)
- Trigger (what precedes this behavior?)
- Intervention (specific rule to prevent it)

Provide a "psychological risk profile" with the top 3 behavioral leaks.
```

### Prompt 24: Trading Plan Compliance Audit
```
Act as a trading compliance officer. Audit my recent trades against my stated trading plan:

My trading plan rules:
[PASTE_YOUR_TRADING_PLAN_RULES]

Recent trades:
[PASTE_TRADE_DATA]

For each trade, check:
1. Was the trade within my defined setups? (yes/no)
2. Was position size within limits? (yes/no)
3. Was stop-loss placed before entry? (yes/no)
4. Were profit targets defined before entry? (yes/no)
5. Was the trade within my daily loss limit? (yes/no)
6. Was the trade taken during allowed hours? (yes/no)

Calculate:
- Overall compliance rate (%)
- Compliance rate by rule
- P&L of compliant vs. non-compliant trades
- The single most violated rule and its cost

Provide a "compliance scorecard" with specific improvement actions.
```

---

## 7. Earnings & Event Analysis

### Prompt 25: Earnings Preview & Playbook
```
Act as an earnings season strategist. Prepare a trading playbook for [TICKER]'s upcoming earnings:

Earnings Date: [DATE]
Current Price: $[PRICE]
Consensus EPS: $[ESTIMATE]
Consensus Revenue: $[ESTIMATE]
Implied Move (from options): [X]%

Provide:
1. Earnings history — last 8 quarters: beat/miss pattern, stock reaction
2. Guidance history — how often do they raise/lower guidance?
3. Key metrics to watch — beyond EPS/revenue (what drives this stock?)
4. Analyst expectations — recent note summaries, price target changes
5. Options market read — where is the open interest concentrated?
6. Trading scenarios:
   - Beat on both + raised guidance: expected move and strategy
   - Beat on both + lowered guidance: expected move and strategy
   - Miss on both: expected move and strategy
   - Mixed results: expected move and strategy
7. Pre-earnings positioning recommendation (hold/exit/hedge/position for event)
8. Post-earnings trade management rules

Include a "cheat sheet" for earnings day.
```

### Prompt 26: Earnings Call Transcript Analysis
```
Act as an equity research analyst. Analyze this earnings call transcript excerpt:
[PASTE_TRANSCRIPT_OR_KEY_QUOTES]

Extract and analyze:
1. Key numbers — revenue, EPS, guidance vs. consensus
2. Tone analysis — is management more/less confident than last quarter?
3. Specific language changes — what words/phrases changed from last call?
4. Q&A session highlights — what did analysts press on? How did management respond?
5. Forward guidance — explicit and implicit
6. Red flags — evasive answers, deferred guidance, unusual items
7. Bull/bear case evidence from the call
8. Trade implication — how should I position based on this call?

Score management credibility 1-10 based on consistency and specificity.
```

### Prompt 27: SEC Filing Analysis (10-K/10-Q)
```
Act as a forensic accountant and SEC filing specialist. Analyze this [10-K/10-Q] filing excerpt:
[PASTE_KEY_SECTIONS_OR_SUMMARY]

Focus on:
1. Risk factors — any new or expanded risk disclosures?
2. MD&A changes — how does management's narrative differ from prior periods?
3. Footnote analysis — any unusual accounting treatments or contingencies?
4. Insider activity — are executives buying or selling?
5. Cash flow vs. earnings — quality of earnings assessment
6. Segment performance — which businesses are growing/declining?
7. Off-balance-sheet items — special purpose entities, guarantees, leases
8. Related-party transactions — any concerning related-party activity?

Provide a "filing health score" (1-10) and list the top 5 questions to ask management.
```

---

## 8. Options & Derivatives Analysis

### Prompt 28: Options Strategy Selection
```
Act as an options strategist. Help me select the optimal options strategy:

Asset: [TICKER]
Current price: $[PRICE]
Market view: [BULLISH/BEARISH/NEUTRAL]
Conviction: [HIGH/MEDIUM/LOW]
Time horizon: [DAYS/WEEKS]
Volatility view: [HIGH_IV/LOW_IV/NEUTRAL]
Max capital: $[AMOUNT]
Risk tolerance: [CONSERVATIVE/MODERATE/AGGRESSIVE]

Recommend the top 3 strategies ranked by suitability. For each:
1. Strategy name and structure
2. Entry: specific strikes and expirations
3. Max profit, max loss, breakeven
4. Probability of profit (estimate)
5. Greeks profile (delta, theta, vega)
6. When to use vs. when to avoid
7. Management rules (adjustment, roll, close triggers)

Explain why each strategy fits (or doesn't fit) my specific situation.
```

### Prompt 29: Options Flow Analysis
```
Act as an options flow analyst. Analyze this unusual options activity:
[DESCRIBE_OPTIONS_FLOW: ticker, strikes, volume, open interest, premium]

1. Decode the signal — what is the "smart money" positioning for?
2. Is this flow unusual? (volume vs. average open interest, premium size)
3. Possible interpretations:
   - Directional bet
   - Hedging activity
   - Arbitrage
   - Market maker positioning
4. Historical context — similar flows and subsequent price action
5. Trade implications — should I follow this flow or fade it?
6. Specific trade ideas based on this flow
7. Risk warnings — why this flow might be misleading

Be skeptical. Not all unusual flow is "smart money."
```

### Prompt 30: IV Rank & Volatility Trading
```
Act as a volatility trader. Analyze the volatility environment for [TICKER]:

Current IV: [X]% | IV Rank: [X]% | IV Percentile: [X]%
HV (20-day): [X]% | HV (60-day): [X]%

1. IV context — is IV expensive or cheap relative to history?
2. IV vs. HV — is the market overpricing or underpricing future volatility?
3. Term structure — is the curve in contango or backwardation?
4. Skew analysis — are puts more expensive than calls? (fear gauge)
5. Earnings/event impact — is IV inflated by upcoming events?
6. Strategy recommendations:
   - If IV is expensive: sell volatility strategies
   - If IV is cheap: buy volatility strategies
   - Specific trade structures for each scenario
7. Volatility timing — when is the optimal entry for volatility trades?

Provide a "volatility regime" assessment and trade plan.
```

---

## Bonus Prompts

### Prompt 31: Investment Thesis Stress Test
```
Act as a skeptical hedge fund PM. I'm about to take a position in [TICKER] with this thesis:
[PASTE_YOUR_THESIS]

Stress-test my thesis by:
1. Identifying the 3 weakest assumptions in my thesis
2. Presenting the strongest bear case I haven't considered
3. Listing 5 specific data points I should verify before entering
4. Identifying any cognitive biases in my thinking (confirmation bias, recency, etc.)
5. Providing a "pre-mortem" — assume this trade loses 50%. What went wrong?
6. Scoring my thesis confidence 1-10 with justification

Be ruthless. My goal is to find flaws before the market does.
```

### Prompt 32: Portfolio Rebalancing Trigger
```
Act as a portfolio manager. My portfolio target allocation:
[List target allocations by asset class/sector]

Current allocation:
[List current positions and weights]

Analyze:
1. Drift analysis — how far from target is each position/sector?
2. Rebalancing urgency — which positions need immediate action?
3. Tax implications — short-term vs. long-term capital gains
4. Transaction cost analysis — is the drift large enough to justify trading costs?
5. Rebalancing plan — specific buy/sell actions with order of execution
6. Alternative: rebalance with new cash vs. selling existing positions

Provide a "rebalancing checklist" with prioritized actions.
```

### Prompt 33: Market Regime Detection
```
Act as a macro strategist. Analyze current market conditions to identify the regime:

Current data:
[INSERT_KEY_INDICATORS: VIX, yield curve, credit spreads, USD, commodities, etc.]

1. Classify the current regime:
   - Risk-on / Risk-off
   - Growth / Value
   - Inflationary / Deflationary
   - Tightening / Easing
   - High vol / Low vol
2. Historical analog — which past period is most similar?
3. How long do similar regimes typically last?
4. Portfolio positioning for this regime:
   - Asset allocation shifts
   - Sector preferences
   - Factor exposure (quality, momentum, value, low vol)
   - Hedging requirements
5. Regime change signals — what would indicate a regime shift is coming?
6. Early warning indicators to monitor daily

Provide a "regime dashboard" with current readings.
```

### Prompt 34: Backtesting Hypothesis Generator
```
Act as a quantitative researcher. Help me formalize a trading hypothesis for backtesting:

My observation: [DESCRIBE_PATTERN_OR_STRATEGY_YOU_BELIEVE_EXISTS]

Convert this into a testable hypothesis:
1. Clear hypothesis statement (If [condition], then [outcome])
2. Entry rules — precise, unambiguous conditions
3. Exit rules — precise, unambiguous conditions
4. Position sizing rules
5. Data requirements — what data do I need? (daily, intraday, options, fundamentals)
6. Backtesting parameters:
   - Time period to test
   - Assets/universe to test on
   - Transaction costs to assume
   - Slippage assumptions
7. Success criteria — what metrics define a "good" result?
8. Potential pitfalls and look-ahead bias to avoid
9. Suggested tools for backtesting (Python, TradingView, etc.)

Make this hypothesis specific enough that anyone could code it.
```

### Prompt 35: Trade Idea Sourcing System
```
Act as a systematic trader. Design a trade idea sourcing system for me:

My preferences:
- Markets: [STOCKS/OPTIONS/FOREX/CRYPTO]
- Timeframe: [SCALP/DAY/SWING/POSITION]
- Style: [VALUE/GROWTH/MOMENTUM/MEAN_REVERSION]
- Time available: [HOURS_PER_DAY]

Design a daily/weekly routine that generates 5-10 high-quality trade ideas:
1. Daily scan setup — specific screeners and filters to run each morning
2. Catalyst calendar — what events to track daily/weekly
3. Sector rotation signals — how to identify leading sectors
4. Options flow monitoring — what to look for and how to filter noise
5. Social sentiment tracking — which indicators are actually useful
6. Idea prioritization framework — how to rank ideas by quality
7. Idea tracking system — how to log and review ideas before trading them

Provide a printable "daily routine checklist."
```

### Prompt 36: Risk-On / Risk-Off Positioning
```
Act as a macro portfolio manager. Assess the current risk environment:

[INSERT_CURRENT_MARKET_CONDITIONS]

1. Risk sentiment gauge (1-10 scale):
   - VIX level and trend
   - Credit spread widening/narrowing
   - USD strength/weakness
   - Emerging market performance
   - High-yield vs. investment grade
2. Positioning recommendations:
   - Equity allocation (% of portfolio)
   - Cash allocation (%)
   - Hedge allocation (puts, VIX, gold, bonds)
   - Sector tilts (defensive vs. cyclical)
3. Specific instruments for each allocation
4. Trigger levels for changing allocation
5. "Break glass" plan — what to do if risk-off accelerates

Provide a clear "gas or brake" recommendation.
```

### Prompt 37: Dividend & Income Strategy
```
Act as an income portfolio manager. Design a dividend/income strategy:

Capital: $[AMOUNT]
Target yield: [X]%
Risk tolerance: [CONSERVATIVE/MODERATE/AGGRESSIVE]
Growth requirement: [YES/NO]
Tax situation: [TAXABLE/TAX_ADVANTAGED]

Design a portfolio that:
1. Generates [X]% annual income with monthly/quarterly distributions
2. Has dividend growth potential (not just high yield traps)
3. Is diversified across sectors and geographies
4. Includes specific tickers with current yields and payout ratios
5. Has a reinvestment strategy (DRIP vs. cash)
6. Includes options overlay ideas (covered calls, cash-secured puts) to boost yield
7. Risk analysis — what could cut the dividend?
8. Comparison to bond yields and inflation

Provide a "monthly income calendar" showing when each position pays.
```

### Prompt 38: Forex & Currency Analysis
```
Act as a forex strategist. Analyze the following currency pair:
[PAIR, e.g., EUR/USD, USD/JPY]

Current rate: [X] | Trend: [UP/DOWN/RANGING]

1. Fundamental drivers:
   - Interest rate differential and central bank policy divergence
   - Economic data comparison (GDP, inflation, employment)
   - Terms of trade and current account
   - Political factors
2. Technical analysis:
   - Multi-timeframe trend
   - Key support/resistance levels
   - Momentum indicators
3. Positioning:
   - CFTC net positioning data
   - Retail sentiment (contrarian indicator)
4. Trade setup:
   - Entry, stop, target
   - Timeframe
   - R-multiple

Provide a "forex trade card" with all levels.
```

### Prompt 39: Crypto Market Analysis
```
Act as a crypto market analyst. Analyze the current crypto market:

[INSERT_CURRENT_MARKET_CONDITIONS_OR_SPECIFIC_ASSET]

1. On-chain metrics to check:
   - Active addresses trend
   - Exchange flows (inflow/outflow)
   - Hash rate (for BTC)
   - Stablecoin market cap growth
   - Funding rates (perp markets)
2. Macro correlation — how is crypto correlating with equities/bonds?
3. Regulatory landscape — any pending legislation or enforcement actions?
4. DeFi metrics — TVL, yields, lending rates
5. Risk assessment — liquidation heat map, funding rate extremes
6. Trade/position recommendations with specific levels
7. "Crypto fear & greed" assessment

Provide a "crypto regime" assessment and positioning guide.
```

### Prompt 40: Annual Trading Performance Report
```
Act as a trading performance analyst. Generate my annual trading report:

[PASTE_FULL_YEAR_TRADE_DATA]

Create a comprehensive report with:
1. Executive summary — total P&L, return %, best/worst month
2. Monthly performance breakdown (table format)
3. Win rate analysis by:
   - Month
   - Setup type
   - Asset class
   - Trade duration
4. R-multiple distribution — histogram of outcomes
5. Best 10 trades and worst 10 trades (with lessons)
6. Drawdown analysis — max drawdown, recovery time
7. Consistency metrics:
   - Sharpe ratio (estimate)
   - Profit factor
   - Expectancy per trade
   - Average holding period
8. Year-over-year comparison (if data available)
9. Top 5 strengths and top 5 weaknesses
10. Goals and focus areas for next year

Format as a professional report I could share with a mentor or coach.
```

---

## Quick Reference Card

### When to Use Each Category

| Situation | Use Prompts |
|-----------|-------------|
| Starting your trading day | #1, #2, #36 |
| Researching a new stock | #5, #6, #7, #8 |
| Analyzing a chart setup | #9, #10, #11, #12 |
| Sizing a position | #13, #14, #15 |
| Planning a specific trade | #17, #18, #19 |
| Reviewing your trading | #21, #22, #23, #24 |
| Earnings season | #25, #26, #27 |
| Options trading | #28, #29, #30 |
| Stress-testing ideas | #31, #33 |
| Building a routine | #35 |
| Income investing | #37 |
| Forex/crypto | #38, #39 |
| Year-end review | #40 |

### Prompt Customization Tips
- **Add your data**: The more specific your input, the better the output
- **Chain prompts**: Use output from one prompt as input to the next
- **Save outputs**: Store AI analysis in your trading journal
- **Iterate**: Ask follow-up questions to drill deeper
- **Verify**: Always cross-check AI outputs with your own research

---

*Trading AI Prompt System v1.0 — Built for serious traders who use AI as a research assistant, not a crystal ball.*
*Pair with the Pro Trading Journal template for a complete trading system.*
