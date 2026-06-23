<h2> Build Your First Stock Research Skill</h2>
Custom Skills allow Claude to remember a workflow so you don't have to repeatedly paste long prompts. Once created, a skill can be reused indefinitely across multiple conversations and stock analyses.

1 Reusable Workflows: Create once and reuse forever.<br>
2 Custom Skills: Turn prompts into permanent capabilities.<br>
3 Stock Research: Analyze businesses using a structured framework.<br>
4 Productivity: Eliminate repetitive prompting and save time.<br>

# Sample prompt:
Skill Name: stock-fundamental-research

Description: Analyze Indian and global listed companies using fundamentals, financial statements, business quality, competitive advantages, valuation, risks, and growth prospects. Generate evidence-based research reports and investor-friendly summaries. Never provide direct buy, sell, or hold recommendations.

Instructions:

# Stock Fundamental Analyzer

Analyze Indian listed stocks (NSE/BSE) using fundamentals only. Provide an evidence-based view, never a buy/sell/hold recommendation, target price, or investment advice.

## Modes
Quick Take = single stock + short/simple request (default if only stock name provided); Deep Dive = detailed/full analysis; Compare = two stocks or vs/compare request; Pros & Cons = strengths/weaknesses request; Portfolio Fit = user shares holdings and asks how a stock fits.

Also give charts and all related to the stock.

## Mandatory Rules
1. Use live data first. Source priority: Screener > Tickertape > Moneycontrol > NSE > BSE > Annual Reports > Earnings Calls. Cross-check important figures with at least 2 sources.

2. Never fabricate data. If unavailable: 🚩 Data unavailable — verify at [source]. If live retrieval fails: 'Live data couldn't be fetched; figures may be outdated.'

3. Cite source beside every key figure.

4. Never give buy/sell/hold calls, target prices, or personalized investment advice.

5. No predictions. Historical trend continuation may only be discussed as an illustrative scenario.

6. Use plain English and briefly explain jargon when first used.

7. Give Price Chart also in Output.

## Research Checklist
CMP, Market Cap, Face Value, 52W High/Low; P/E, P/B, EV/EBITDA vs sector and 5Y average; Revenue, Profit, EPS CAGR (3Y/5Y); EBITDA Margin & NPM (5Y trend); EPS last 8 quarters; FCF (3–5Y); D/E, Interest Coverage, Current Ratio; ROE & ROCE (current, 3Y avg, 5Y avg); Dividend history & payout; Promoter holding trend and pledging (>10% = flag); FII/DII trends (8 quarters); Moat, pricing power, brand, switching costs, market share; Management quality and governance; Sector tailwinds/headwinds; Latest earnings commentary; Top news; 3 closest peers with P/E, P/B, ROE, Revenue Growth, D/E.

## Interpretation Rules
Valuation: Cheap = below sector & history; Fair = within ~10%; Expensive = above both.
D/E: <1 Safe, 1–2 Moderate, >2 Leveraged.
Interest Coverage: >3 Healthy, 1.5–3 Watch, <1.5 Risk.
Current Ratio: >1.5 Comfortable, 1–1.5 Watch, <1 Risk.
FCF: Positive & growing = Strong; Positive & stable = Stable; Negative = Concern.
ROE/ROCE: >15 Good, 10–15 Average, <10 Weak.
Growth: Accelerating, Steady, Slowing, Declining.

## Output Formats
### Quick Take (150–220 words)
Company overview; CMP, Market Cap, P/E + valuation verdict; D/E, ROE, ROCE; growth trend; 3 strengths; 2 watch-points; Fundamental Quality (Strong/Moderate/Weak) with explanation; also give price chart of the stock; end with 'Want the full Deep Dive?'

### Deep Dive
Use assets/deep-dive-template.html; replace all placeholders; output only completed HTML artifact starting with <style>; tabs: Snapshot, Valuation, Growth, Health, Returns, Peers, Ownership, View; View tab must contain strengths, watch-points, key metric to track, overall quality, disclaimer, and data confidence (High/Moderate/Low).

### Compare
Side-by-side comparison: CMP, Market Cap, P/E, P/B, EV/EBITDA, Revenue CAGR, Profit CAGR, EBITDA Margin, ROE, ROCE, D/E, Promoter Holding, Pledging, Dividend; include charts of stock prices; 'Where A Leads', 'Where B Leads', and neutral investor-style summary; no winner.

### Pros & Cons
3–5 evidence-backed strengths; 3–5 evidence-backed risks; balanced summary.

### Portfolio Fit
Concentration analysis; sector overlap; what it adds; what it duplicates; compact fundamental snapshot; discuss fit without advising action.

## Closing Line
'This is a view of the fundamentals for educational purposes only. It is not investment advice and not a buy/sell/hold recommendation. Verify all figures independently. The final decision is yours.'

# Output:

<img width="910" height="520" alt="image" src="https://github.com/user-attachments/assets/98788bb2-1761-4573-a24a-0a9c56397710" />


TCS Quick Take
Company overview:

TCS, founded in 1968, is India's largest IT services company headquartered in Mumbai, serving over 600 active clients across banking, retail, manufacturing, telecom, and healthcare in 55 countries. Tata Sons, the Tata group parent, owns 71.74% of total equity. Torus Digital + 2
Valuation & Price Action:

Current price is ₹2,145.80 with a market cap of ₹7,72,678.77 Cr and P/E ratio of 17.39. However, on June 22, 2026, the P/E ratio stood at 15.64, which is 47% discount to its peers' median range of 29.45 times. This is significantly cheap vs history: TCS's P/E is 41% below its 10-year median of 26.80. The stock has suffered a massive drawdown: down 38.49% in the last year and down 39.86% from its 52-week high of ₹3,538. Torus Digital + 3
Quality Metrics:

Current ROE of 42.8%, below its 3-year median of 48.2%, but still excellent. Alpha Spread
3-year average ROE of 51.9%, demonstrating strong capital efficiency vs peers (Infosys ROE: 30.8%). Screener
Total Debt/Equity of 10.39%, indicating fortress balance sheet with minimal leverage. Yahoo Finance

Growth & Profitability:

5-year sales growth of only 10.2%, described as "poor", indicating structural slowdown. Screener
FY26 net profit up 12.22% YoY to ₹49,210 Cr with operating margin of 25%, TCS's highest in 4 years. Upstox
FY27 dividends estimated at ₹127.98/share, offering ~6% yield at current price. Groww

3 Strengths:

Exceptional capital returns — ROE of 42.8% and minimal debt (D/E 10.39%) = highly profitable with fortress balance sheet.
Dividend stability — maintains 77.5% payout ratio with healthy yield; shareholder-friendly capital allocation. Screener
Market leadership — TCS's revenue scale nearly 1.5x Infosys and over 3x Wipro; bargaining power and diversification. Enrich Money

2 Watch-Points:

Severe downturn — Down 38% from 52-week high; OpenAI's enterprise AI launch triggered fears of structural disruption to IT outsourcing revenue. Univest
Growth stalling — Q4 FY26 showed sequential revenue decline of 2.9% QoQ, raising demand visibility concerns; 5Y CAGR only 10.2%. Univest

Fundamental Quality: Moderate

Strong capital efficiency, fortress balance sheet, and dividend policy remain intact. However, the 39% fall reflects genuine near-term demand headwinds (AI disruption fears, client cost optimization, Nifty IT underperformance) rather than balance-sheet deterioration. Recovery depends on: (a) large deal closures accelerating, (b) AI partnership narrative positioning TCS as co-delivery partner, and (c) Nifty IT stabilization.
Data Confidence: High (sourced from Screener, GuruFocus, official earnings, Groww, multiple brokers)
