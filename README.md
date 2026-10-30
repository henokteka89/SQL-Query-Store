# SQL-Query-Store

SQL Server Query Store scripts and notes, consolidated from separate repositories. Each folder is one former repo, with its full commit history preserved.

| Folder | What it covers |
|---|---|
| [QueryStore-Note](QueryStore-Note) | Core Query Store queries: top resource consumers, most expensive by CPU, regressed queries, query variants, query hints, timeouts/errors, query ID details |
| [Find-your-query-from-query-store-or-cache](Find-your-query-from-query-store-or-cache) | Find a query by text in Query Store or the plan cache |
| [Query-Query-store](Query-Query-store) | Log Query Store data to a table and analyze it; working around a slow Query Store UI |
| [QSGetplanbyNameForMonitoring](QSGetplanbyNameForMonitoring) | `ufn_getplansbyname`: get plans by object name for monitoring |
| [Stored-proc-information-based-on-text-Query-Store-](Stored-proc-information-based-on-text-Query-Store-) | Stored procedure / dynamic SQL info from Query Store by text |
| [regressed-plan-with-query-variant-sendalert](regressed-plan-with-query-variant-sendalert) | Detect regressed plans (including query variants) and send an alert |
| [Query-Store-Query-plan-and-Performance-tuning-Execution-Plan](Query-Store-Query-plan-and-Performance-tuning-Execution-Plan) | Notes document on query plans, Query Store and execution-plan tuning |
