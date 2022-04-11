# `pg_catalog.stv_table_partitions`
`analytics_uat` | `analytics`

## Column details
* [integer]   `id`
* [integer]   `slice`
* [bigint]    `partition_id`
* [bigint]    `rows`
* [integer]   `flags`
* [bigint]    `num_blocks`
* [integer]   `num_overlapping_partitions`
* [integer]   `degree_of_overlap`
* [character] `is_hot`
* [character] `is_sorted`
* [character] `is_range_partitioned`
* [integer]   `qpd`
* [bigint]    `total_wasted_blocks`
* [bigint]    `total_blocks_read`
* [bigint]    `total_blocks_used`
* [bigint]    `no_loss_scans_count`
* [bigint]    `zero_bias_scans_count`
* [bigint]    `scan_count`
* [timestamp without time zone] `first_qpd_rise_ts`
* [timestamp without time zone] `first_marked_hot_ts`
* [bigint]    `num_scans_to_mark_hot`

-------------------------------------------------------------------------------
*Do not make edits above this line.*
