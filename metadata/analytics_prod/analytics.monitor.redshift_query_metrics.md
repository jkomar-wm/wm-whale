# `monitor.redshift_query_metrics`
`analytics_prod` | `analytics`

## Column details
* [character varying] `user_name`
* [integer]   `query`
* [bigint]    `xid`
* [integer]   `pid`
* [character varying] `database`
* [timestamp without time zone] `starttime`
* [timestamp without time zone] `endtime`
* [integer]   `aborted`
* [bigint]    `query_cpu_time`
* [bigint]    `query_blocks_read`
* [bigint]    `query_execution_time`
* [numeric]   `query_cpu_usage_percent`
* [bigint]    `query_temp_blocks_to_disk`
* [bigint]    `segment_execution_time`
* [numeric]   `cpu_skew`
* [numeric]   `io_skew`
* [bigint]    `scan_row_count`
* [bigint]    `join_row_count`
* [bigint]    `nested_loop_join_row_count`
* [bigint]    `return_row_count`
* [bigint]    `spectrum_scan_row_count`
* [bigint]    `query_queue_time`
* [character varying] `querytxt`
* [date]      `report_date`

-------------------------------------------------------------------------------
*Do not make edits above this line.*
