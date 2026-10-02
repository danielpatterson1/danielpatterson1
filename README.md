# Daniel Patterson

**Healthcare Revenue Cycle Analytics | R, Python, SQL | M.S. Analytics, Georgia Tech (2028)**

I build automated reporting pipelines that turn messy healthcare billing data into daily tools that operations teams actually work from. My focus is data engineering for analytics: reliable ETL, reconciliations that tie out, and dashboards that lead directly to action.

## Impact highlights

* **$1M+ in write off and recovery opportunities** identified through payment integrity analyses, each validated account by account with the owning team before rollout
* **78% reduction in aged unposted cash** within three weeks of launching an automated daily cash reconciliation
* **100K+ accounts and $1.5B+ in claims** tracked in a single automated AR report with full drill down to the account level
* **3,000+ stuck claims traced to one root cause**, which turned thousands of manual follow ups into a single system fix
* **Zero manual steps** in daily report runs: scheduled pipelines with archiving, backups, and data checks

## Featured work

**Aged Trial Balance (ATB) Dashboard** | R Markdown, R, Parquet
One automated report covering the full claim lifecycle from discharge to payment. Every unbilled balance shows its reason, and any chart drills down to an Excel export of the accounts behind it, so AR teams no longer need to request lists from analytics.

**Cash Posting Reconciliation** | R Markdown, R
Replaced a daily manual comparison of bank deposits against patient accounting. It runs every morning, shows about 700 open deposits by facility, owner and reason, and cut aged unposted cash by 78% in three weeks.

**Quarterly Performance Summary Pipeline** | R, DuckDB, Parquet
Rebuilt a manually maintained spreadsheet as a daily pipeline that archives one row per facility to DuckDB and a Parquet history. It ties out exactly to the legacy version on core metrics, and anyone on the team can run it.

**Team Performance Snapshots** | Python, Parquet
A daily job that renders team level performance reports and saves dated snapshots with automatic backups, which made trend tracking and team scorecards possible.

**Payment Integrity Analyses** | SQL, R
Medicaid due diligence and Medicare Advantage eligibility reviews that surfaced over $1M in write off and recovery opportunities, each proven at the account level.

## Tech stack

* **Languages:** R, Python, SQL
* **Data:** DuckDB, Parquet, Arrow, SQL Server
* **Reporting:** Quarto, R Markdown, Excel automation
* **Practices:** ETL design, data validation and reconciliation, scheduled automation, version control

## Currently

* M.S. in Analytics (OMSA) at Georgia Tech, applying predictive modeling and anomaly detection to denials, bad debt and payment postings
* Mentoring teammates and setting team standards for dashboard quality and documentation

## Contact

dpatterson6575@gmail.com

*Code samples use synthetic or anonymized data. No patient or proprietary information is published here.*
