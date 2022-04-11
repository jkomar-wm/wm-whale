# `s3adzerk.request`
`analytics_uat` | `analytics`

## Column details
* [string]    `meta:schema`
* [string]    `meta:version`
* [int]       `networkid`
* [string]    `id`
* [int]       `requestcount`
* [bigint]    `timestamp`
* [int]       `deliverymode`
* [string]    `hostname`
* [string]    `protocol`
* [string]    `url`
* [string]    `referrerurl`
* [boolean]   `isvalidua`
* [struct<CountryCode:string,CountryName:string,Region:string,City:string,PostalCode:string,MetroCode:int,DmaCode:int,Latitude:int,] `location`
* [struct<brandName:string,modelName:string,osRawVersion:string,osMajorVersion:int,osMinorVersion:int,browser:string,browserRawVers] `device`
* [array<string>] `keywords`
* [boolean]   `datacenter`
* [struct<Key:string,IsNew:boolean>] `user`
* [boolean]   `gdprcomputed`
* [string]    `year`
* [string]    `month`
* [string]    `day`

-------------------------------------------------------------------------------
*Do not make edits above this line.*
