# Supplier and Product Distribution Analysis

**Author:** Cameron Batts

**Tools:** SAS Visual Analytics / SAS Viya

## Validation update - October 22, 2026

The 2-page PDF parsed successfully, a sampled dashboard page was rendered and reviewed, and repository file links were checked. The original export bytes are preserved. Native SAS interactions, report calculations, filters and forecasts were not rerun. Editable SAS report definitions are absent; projects without source tables remain static case studies. This is an asset/evidence audit, not certification of a functioning native dashboard.

[Aggregate validation record](Reports/validation_results.json). 
## Problem
Compare supplier quantities and product assortment across regional dashboard controls.

## Approach
Review the supplier treemap, product-category quantity bars and product-group count table. Region buttons show Australia/Pacific, Europe and North America.

## Findings
Clothes has the longest category quantity bar. Eclipse Inc and 3Top Sports occupy the largest visible supplier rectangles. The product-group table shows 351 products for Assorted Sports articles and 333 for Eclipse Clothing. These are product counts, separate from the Quantity measure. The 236 to 248K treemap legend is a scale, not a company inventory total.

## Limitations
No source tables, date coverage or editable report are included. Quantity does not establish stock on hand, sales, supplier performance or facility-level efficiency without a data definition. The region selections and cross-filter behavior have not been tested. Visual ranks are observations from one exported view.

## Data and provenance
Supplier and product names appear in the supplied SAS dashboard. Earlier claims of real operational data are unverified; source provenance and licensing are not documented.

## Verification
PDF pages and repository assets reviewed; source data and native SAS interactions are unavailable.

## View the project
- [Analysis report](Reports/sas_facility_products.html)
- [Portfolio analysis](https://cameron-batts.github.io/sas_facility_products.html)
- [Original PDF export](Reports/Family_Products_on_Apr_25__2026.pdf)

## Dashboard previews
![Facility-and-Products](Images/Facility-and-Products.png)

## Reproduce and inspect
Open the HTML report and original PDF. Rebuilding the dashboard requires the original SAS report definition, source tables and measure definitions; those files are not included.

The static exports are preserved as historical evidence. Their source captions and map attribution remain intact.
