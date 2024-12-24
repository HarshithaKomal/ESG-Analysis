# ESG-Analysis
Sustainability Meets Strategy: Portfolio Optimization with ESG Insights

Harshitha Suresh

Introduction

Environmental, Social, and Governance (ESG) scores have become critical for evaluating
corporate responsibility and ethical practices. This analysis leverages ESG scores to optimize
portfolio performance while balancing financial returns with sustainable practices. Combining
data-driven insights and advanced economic modeling, this study provides actionable
recommendations for creating efficient ESG-focused investment strategies.

Data Sources

The data for this analysis was sourced from two primary repositories. Yahoo Finance provided
detailed financial information, including stock prices, sectors, and ESG scores, while DataHub
supplied a comprehensive list of securities constituting the S&P 500 index. These resources
formed the backbone of the dataset, ensuring thorough coverage of financial and sustainability
metrics.
https://datahub.io/core/s-and-p-500-companies#resource-constituents

Data Formation Process

Integration and Cleaning

The initial stage involved consolidating datasets from multiple sources, including risk_data,
esg_data, security_data, and snp. Using an inner join approach, only securities common
across all datasets were retained, ensuring consistency and alignment in subsequent analyses. To
maintain data integrity, rows with missing values in key metrics, such as totalEsg, were
removed. This cleaning step ensured that the analysis was conducted on a complete and reliable
dataset.

Categorization and Grouping

The dataset was further enhanced by categorizing companies into meaningful groups. Market
capitalization was segmented into small, medium, and large categories based on percentile
distributions. Similarly, peer groups were streamlined by consolidating less frequent groups
under the label "Others," while retaining the most prominent ones. ESG scores were classified
into five distinct risk levels—Severe Risk, High Risk, Medium Risk, Low Risk, and No Risk—
using quantile-based thresholds, enabling a granular understanding of ESG performance across
the dataset.

Final Dataset Overview

The resulting dataset contained 465 rows and 25 columns, encapsulating key metrics such as
social, environmental, governance, and total ESG scores. Additional fields included market
capitalization categories and peer group classifications, providing a robust foundation for
portfolio construction and analysis.

Portfolio Analysis

Methodology

The analysis involved constructing portfolios based on different ESG score dimensions, each
comprising 20 securities to maintain uniformity. An equally weighted portfolio spanning all
industries served as the benchmark. Four ESG-driven portfolios were analyzed, focusing
respectively on social, governance, environmental, and total ESG scores. The methodology
ensured comparability across portfolios and highlighted the influence of ESG criteria on
financial performance.

Stock Selection Strategies

1. Broad Market Selection

This approach evaluated performance across all industries without sector-specific focus.
Securities were selected based on their rankings in the top 30 for each ESG category. The
cumulative performance revealed that the socialScore portfolio slightly outperformed the
benchmark over time, maintaining a Sharpe ratio of 0.8519. While the environmentScore
portfolio exhibited higher volatility, the socialScore portfolio offered the best risk-adjusted
returns.

2. Outperforming Sectors

Focusing on high-performing sectors such as Information Technology, Consumer Discretionary,
and Industrials, this strategy targeted top ESG-ranked securities. The governanceScore
portfolio emerged as the leader, achieving the highest annualized return (21.41%) and Sharpe
ratio (0.902). Governance-focused strategies excelled in high-growth sectors, demonstrating their
potential for enhanced financial performance.

3. Excluding Underperforming Sectors

By excluding sectors with weak historical performance—Utilities, Real Estate, and Consumer
Staples—this strategy refined portfolio composition. The socialScore portfolio delivered
superior returns of 17.50% and competitive risk-adjusted performance. Excluding
underperforming sectors also reduced volatility, enhancing portfolio stability.

4. Sector-Focused Selection

This approach capitalized on sectors with strong ESG characteristics, specifically Financials and
Health Care, identified for their high governance and social scores. The environmentScore
portfolio outperformed the benchmark, achieving the highest Sharpe ratio (0.827). Financials and
Health Care demonstrated robust ESG performance, emphasizing sector-specific opportunities
for ESG-driven strategies.

Results

The results of the analysis reveal notable insights into the performance of ESG-focused
portfolios:

1. Broad Market Selection: The socialScore portfolio slightly outperformed the benchmark,
with a Sharpe ratio of 0.8519. It demonstrated stable risk-adjusted returns despite moderate
volatility.

2. Outperforming Sectors: The governanceScore portfolio led in annualized return (21.41%)
and Sharpe ratio (0.902), driven by strong performance in high-growth sectors like
Information Technology.

3. Excluding Underperforming Sectors: By removing Utilities, Real Estate, and Consumer
Staples, the socialScore portfolio achieved superior returns (17.50%) while maintaining a
competitive Sharpe ratio. Exclusion also reduced portfolio volatility.

4. Sector-Focused Selection: The environmentScore portfolio excelled with a Sharpe ratio of
0.827, driven by strong performance in Financials and Health Care. These sectors provided a
stable foundation for ESG-led investments.


Conclusion

This analysis highlights the interplay between sustainability and profitability, offering practical
insights for ESG-focused investors. Key findings include:

• Broad market performance reveals that portfolios incorporating ESG scores outperform
benchmarks in risk-adjusted returns, particularly when prioritizing social or governance
factors. Sectoral strategies further emphasize the importance of selecting high-performing
industries such as Information Technology to enhance returns while avoiding
underperforming sectors like Utilities to reduce volatility.

• Governance emerged as a key driver of portfolio success, with the governanceScore
portfolio consistently delivering the highest returns and Sharpe ratio. Sector-specific
strengths in Financials and Health Care underscore the value of focusing on ESG leaders
within traditionally stable industries.

• By aligning investment strategies with ESG principles, investors can achieve a balance
between ethical practices and financial performance. This study underscores the potential of
ESG-driven approaches in modern portfolio optimization, demonstrating that sustainability
and profitability can coexist in harmony.
