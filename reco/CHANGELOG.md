### 2024-11-20 - Version 1.1.4 - switch180
* Updated pricing to reflect new rates for GT rWCU [even though we don't use this pricing data](https://aws.amazon.com/blogs/database/new-amazon-dynamodb-lowers-pricing-for-on-demand-throughput-and-global-tables/)

### 2024-07-25 - Version 1.1.3 - switch180
* Added pricing for TLV and DXB
* Updated pricing for BOM, CPT, BAH

### 2024-03-20 - Version 1.1.2 - switch180
* Removed CMH 3yr RI because it does not appear on [public pricing page](https://aws.amazon.com/dynamodb/pricing/provisioned/).
* Fixed off-by-one error in day calculation

### 2023-02-24 - Version 1.1.1 - switch180
* Added three regions' 3-year RI rates to the configuration.

### 2022-12-21 - Version 1.1.0 - switch180
* BUG: Fix bug that includes S-IA capacity units in reservation recommendation. This created potentially incorrect recommendations in regions where customers have tables in the Standard Infrequent Access table class

### 2022-10-01 - Version 1.0.0 - switch180
* Initial release on GitHub
