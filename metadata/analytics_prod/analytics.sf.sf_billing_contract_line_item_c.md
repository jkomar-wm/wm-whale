# `sf.sf_billing_contract_line_item_c`
`analytics_prod` | `analytics`
{"primary_keys":["id"]}

## Column details
* [timestamp without time zone] `_sdc_batched_at`
* [timestamp without time zone] `_sdc_received_at`
* [bigint]    `_sdc_sequence`
* [bigint]    `_sdc_table_version`
* [boolean]   `active__c`
* [double precision] `acv__c`
* [boolean]   `added_after_bc_creation__c`
* [double precision] `amount_to_credit__c`
* [character varying] `attributes__type`
* [boolean]   `base_bill_date_updated__c`
* [timestamp without time zone] `base_billing_date__c`
* [character varying] `billing_contract__c`
* [timestamp without time zone] `billing_date__c`
* [character varying] `billing_frequency__c`
* [character varying] `createdbyid`
* [timestamp without time zone] `createddate`
* [boolean]   `credit__c`
* [boolean]   `credit_created__c`
* [character varying] `currencyisocode`
* [timestamp without time zone] `current_invoice_date__c`
* [boolean]   `currently_mid_month_add_flag__c`
* [double precision] `cycle_price__c`
* [double precision] `daily_amountproductadded__c`
* [double precision] `days_in_month__c`
* [double precision] `days_in_monthproductadded__c`
* [double precision] `days_offset__c`
* [double precision] `days_offset_from_due__c`
* [double precision] `days_to_credit__c`
* [boolean]   `difference_in_day__c`
* [character varying] `dimension_2__c`
* [character varying] `dimension_3__c`
* [character varying] `dimension_4__c`
* [timestamp without time zone] `due_date__c`
* [double precision] `due_per_billing_cycle__c`
* [timestamp without time zone] `end_of_month__c`
* [boolean]   `equal_days__c`
* [character varying] `id`
* [boolean]   `include_in_rev_rec__c`
* [timestamp without time zone] `initial_bill_date__c`
* [double precision] `initial_price__c`
* [double precision] `invoice_count__c`
* [boolean]   `invoice_processed__c`
* [double precision] `is_spain__c`
* [boolean]   `isdeleted`
* [character varying] `lastmodifiedbyid`
* [timestamp without time zone] `lastmodifieddate`
* [timestamp without time zone] `lastreferenceddate`
* [timestamp without time zone] `lastvieweddate`
* [character varying] `listing_number__c`
* [timestamp without time zone] `local_invoice_end_date__c`
* [timestamp without time zone] `local_invoice_end_date_mid_month__c`
* [timestamp without time zone] `local_invoice_start_date__c`
* [character varying] `name`
* [timestamp without time zone] `next_due_date__c`
* [timestamp without time zone] `next_invoice_date__c`
* [character varying] `oli_id__c`
* [character varying] `opportunity_product_link__c`
* [character varying] `product__c`
* [double precision] `product_added_days_offset__c`
* [character varying] `productid__c`
* [double precision] `prorated_amount__c`
* [double precision] `prorated_amountproductadded__c`
* [double precision] `proration_amount__c`
* [double precision] `quantity__c`
* [timestamp without time zone] `rev_rec_end_date__c`
* [character varying] `revrec_template__c`
* [character varying] `sales_invoice_line_item__c`
* [character varying] `stage__c`
* [timestamp without time zone] `start_date__c`
* [timestamp without time zone] `systemmodstamp`
* [double precision] `unit_price__c`
* [character varying] `dimension_1__c`
* [timestamp without time zone] `_sdc_extracted_at`
* [double precision] `desiredposition__c`
* [timestamp without time zone] `notesupdateddate__c`
* [character varying] `notesupdateduser__c`
* [character varying] `region__c`
* [character varying] `account__c`
* [double precision] `targetspend__c`
* [double precision] `sortweight__c`
* [character varying] `category__c`
* [timestamp without time zone] `expirationdate__c`
* [boolean]   `published__c`
* [character varying] `publishedstatus__c`
* [boolean]   `hidefromdocusign__c`
* [character varying] `opportunity__c`
* [character varying] `convertedopportunity__c`
* [boolean]   `completed__c`
* [timestamp without time zone] `enddate__c`
* [character varying] `changetype__c`
* [character varying] `bcowner__c`
* [character varying] `cancellationrequest__c`
* [character varying] `reasoncancelled__c`
* [character varying] `inactivebillingcontract__c`
* [character varying] `listingurl__c`
* [boolean]   `isactive__c`
* [character varying] `accountname__c`
* [timestamp without time zone] `noteslastupdated__c`
* [character varying] `usernoteslastupdated__c`
* [character varying] `notes__c`
* [boolean]   `isupdated__c`
* [character varying] `cancellationrequeststatus__c`
* [boolean]   `financenotereview__c`
* [boolean]   `active2__c`
* [character varying] `regionstate__c`
* [character varying] `productcode__c`
* [double precision] `walkabilityrating__c`
* [double precision] `unitpriceusd__c`
* [character varying] `regioncountry__c`
* [double precision] `totalamount__c`
* [double precision] `taxamount__c`
* [double precision] `taxrate__c`
* [character varying] `inactivechangetype__c`
* [boolean]   `count__c`
* [character varying] `wmid__c`
* [character varying] `financenotes__c`
* [timestamp without time zone] `expirationdate2__c`
* [boolean]   `enterprise__c`
* [boolean]   `monthmismatch__c`
* [character varying] `service_period__c`
* [double precision] `tech_fees__c`
* [character varying] `monthlyorder__c`
* [character varying] `region_name__c`
* [character varying] `wm_bcli__c`
* [character varying] `list_type__c`
* [character varying] `opportunitytype__c`
* [double precision] `mrr__c`
* [double precision] `total_quantity_received__c`
* [boolean]   `offer_process__c`
* [boolean]   `license_mrr__c`
* [timestamp without time zone] `deactivateddatetime__c`
* [boolean]   `create_order_invoice__c`
* [double precision] `discounted_amount__c`
* [double precision] `discounted_quantity__c`
* [timestamp without time zone] `offer_date__c`
* [double precision] `rate__c`
* [character varying] `advertiser_id__c`
* [character varying] `rate_type__c`
* [double precision] `clicks_impressions__c`
* [character varying] `saasname__c`
* [boolean]   `isprepaid__c`
* [timestamp without time zone] `paidtodate__c`
* [character varying] `line_description__c`
* [character varying] `old_bcli__c`
* [boolean]   `dataloader_flag__c`
* [character varying] `listing_id__c`
* [boolean]   `loop_flag__c`
* [boolean]   `product_isactive__c`
* [character varying] `converted_action__c`
* [double precision] `offer_amount__c`
* [character varying] `downgrade_options__c`
* [character varying] `offered_account__c`
* [timestamp without time zone] `offer_due_date__c`
* [timestamp without time zone] `offer_email_sent_date__c`
* [character varying] `product_category_level__c`
* [character varying] `listing_type_dev__c`
* [boolean]   `active_bc__c`
* [timestamp without time zone] `next_billing_date_bc__c`
* [character varying] `product_category__c`

-------------------------------------------------------------------------------
*Do not make edits above this line.*
