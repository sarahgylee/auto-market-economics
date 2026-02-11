# Auto Market Economics Analysis using Python

### Project Overview
I developed a custom Python analytics pipeline to quantify how high interest rate environments impact consumer brand loyalty. This project integrates disparate datasets including the Consumer Price Index and sales data to identify structural shifts in market share.

### Key Findings
I identified a critical six month lag between interest rate hikes and shifts in consumer behavior. While market share remains stable initially it eventually erodes by over ten percentage points as borrowing costs force a transition to value oriented alternatives.

* **The Shock 2022 Q2**: Interest rates spiked historically fast.
* **The Resilience**: North American market share remained stable for about six months post hike.
* **The Breakpoint**: After this buffer market share shifted significantly.

### Technical Methodology
I utilized Python with Pandas and Matplotlib for data processing and visualization. I also leveraged LLMs to accelerate the development of the engineering workflow and automate data ingestion from the Bank of Canada and Statistics Canada.

* **Data Ingestion**: Automated retrieval of economic indicators.
* **Data Processing**: Used Pandas for time series resampling and merging multi source dataframes.
* **Visualization**: Built custom dual axis charts to overlay economic shocks against market performance.

### Data Sources
* **Car Sales Data**
[Statistics Canada Table 20 10 0085 01](https://www150.statcan.gc.ca/t1/tbl1/en/tv.action?pid=2010008501)
* **Interest Rates**
[Bank of Canada Series V39079](https://www.bankofcanada.ca/rates/interest-rates/canadian-interest-rates/)
* **Inflation CPI**
[Statistics Canada Table 18 10 0004 01](https://www150.statcan.gc.ca/t1/tbl1/en/tv.action?pid=1810000401)
