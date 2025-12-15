
# Codebook — Statistics of comprehensive tax amounts for various types of income by county, city, township, and village – New Taipei City

**Source:** https://data.gov.tw/dataset/17791  
**Providing Agency:** Fiscal Information Center of the Ministry of Finance  
**Update Frequency:** Every 1 year  

**Short Description:**  
Townships and urban areas, Village, Taxpaying units, Total, Profit income, Income from business operations, Salary income, Interest income, Leases and royalties, Proceeds from property transactions, Chance winnings, Dividend income, Retirement income, Other income, Income from royalties, The declaration is greater than the return, Net salary income, Comprehensive income calculated based on net salary income, Royalties.

---

## Dataset Schema (Columns)

| Column Name                  | Type    | Unit | Description |
|-----------------------------|---------|------|-------------|
| city                        | text    | —    | City name (e.g., New Taipei City). |
| township                    | text    | —    | Township/District within the city. |
| village                     | text    | —    | Village/Neighborhood name. |
| tax_units                   | integer | —    | Number of tax filing units (filers/households). |
| total                       | integer | NTD  | Sum of reported incomes across categories (dataset-defined total). |
| business_income             | integer | NTD  | Income from profit-seeking enterprises. |
| professional_income         | integer | NTD  | Income from professional/independent services. |
| salary_income               | integer | NTD  | Wage and salary income. |
| interest_income             | integer | NTD  | Interest earned from deposits/bonds, etc. |
| rental_royalty_income       | integer | NTD  | Rental income and royalties. |
| property_transaction_income | integer | NTD  | Income from property/asset transactions. |
| prize_income                | integer | NTD  | Income from chance winnings (e.g., lottery). |
| dividend_income             | integer | NTD  | Dividend distributions received. |
| retirement_income           | integer | NTD  | Retirement/pension income. |
| other_income                | integer | NTD  | Other income not elsewhere classified. |
| royalty_income              | integer | NTD  | Author/royalty fees reported as income. |
| declared_over_household     | integer | —    | Count of filings flagged as “申報大於歸戶” (verify exact definition with dataset metadata). |
| salary_total                | integer | NTD  | Aggregated salary income (dataset-provided subtotal). |
| royalty_total               | integer | NTD  | Aggregated royalty income (dataset-provided subtotal). |

---

## Notes
- Currency is **New Taiwan Dollars (NTD)**.
- Text columns are in Chinese UTF-8; original Chinese values remain for city/township/village.
- Please verify the exact definition of `declared_over_household` on the metadata page above.
