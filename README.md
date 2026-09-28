# Autonomous Data Pipeline (AI + n8n)
## Built a hands-free ETL pipeline that runs daily at 9 AM IST, cleaning raw sales data, computing KPIs, and sending an AI-written executive report with visuals.

# Workflow Highlights
## Cron Trigger → Daily automation
## Python Cleaning → Null imputation, outlier removal, deduplication (~9k clean rows)
## Canonical Output → Single Cleaned_Ai.csv (no clutter)
## KPI Engine → Revenue trends, cohorts, city/age segments, feedback health
## Quality Gate → Alerts if >20% Customer_ID missing
## AI Summary + Chart → GPT-4o-mini + QuickChart → Gmail report
## Audit Trail → Stats logged to Google Sheets (Power BI-ready)

# Sample Output
## 8,992 customers · $221.8M revenue · MoM -70.8% · Rolling 7d $4.3M · Top city: Kolkata ($55M)

# Tech Stack
## n8n · Python · Google Drive/Sheets · OpenAI · QuickChart · Gmail 

# Why It Matters
## Industrial relevance: Mirrors real-world ETL + reporting pipelines
## Autonomous: Zero manual intervention, daily insights delivered
