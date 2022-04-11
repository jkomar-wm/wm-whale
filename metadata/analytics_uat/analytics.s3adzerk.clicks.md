# `s3adzerk.clicks`
`analytics_uat` | `analytics`

## Column details
* [string]    `meta:schema`
* [string]    `meta:version`
* [boolean]   `gdprcomputed`
* [string]    `gdprsource`
* [string]    `remoteip`
* [string]    `useragent`
* [double]    `ecpm`
* [boolean]   `datacenter`
* [boolean]   `burnin`
* [boolean]   `isvalidua`
* [struct<Key:string,IsNew:boolean,Type:int>] `user`
* [string]    `userkey`
* [int]       `clickcount`
* [string]    `id`
* [string]    `createdon`
* [bigint]    `eventcreatedon`
* [bigint]    `impressioncreatedon`
* [int]       `adtypeid`
* [int]       `brandid`
* [int]       `campaignid`
* [array<string>] `categories`
* [int]       `channelid`
* [int]       `creativeid`
* [int]       `creativepassid`
* [int]       `deliverymode`
* [int]       `firstchannelid`
* [string]    `impressionid`
* [string]    `decisionid`
* [boolean]   `isnotrack`
* [boolean]   `istrackingcookieevents`
* [string]    `keywords`
* [struct<CountryCode:string,CountryName:string,Region:string,City:string,PostalCode:string,MetroCode:int,DmaCode:int,Latitude:int,] `location`
* [struct<brandName:string,modelName:string,osRawVersion:string,osMajorVersion:int,osMinorVersion:int,browser:string,browserRawVers] `device`
* [array<string>] `matchingkeywords`
* [int]       `networkid`
* [int]       `passid`
* [int]       `phantomcreativepassid`
* [string]    `placementname`
* [int]       `phantompassid`
* [string]    `price`
* [int]       `priorityid`
* [int]       `ratetype`
* [string]    `referrerurl`
* [bigint]    `revenue`
* [string]    `servedby`
* [int]       `servedbypid`
* [string]    `servedbyasg`
* [int]       `siteid`
* [string]    `url`
* [int]       `zoneid`
* [string]    `ecpmpartition`
* [string]    `timezoneid`
* [int]       `decisionidx`
* [struct<rank:string,anonymousId:string>] `properties`
* [int]       `gmv`
* [boolean]   `duplicateimpression`
* [boolean]   `fraudulent`
* [struct<Unique:struct<Value:boolean>>] `clickbuckets`
* [boolean]   `isadgoal`
* [double]    `optimizedprice`
* [string]    `partition_0`
* [string]    `partition_1`
* [string]    `partition_2`

-------------------------------------------------------------------------------
*Do not make edits above this line.*