# Market Database Design

## Company

- company_id
- ticker
- company_name
- sector_id

## Sector

- sector_id
- sector_name

## Price_History

- price_id
- company_id
- trade_date
- close_price
- volume

## Financial_Statement

- statement_id
- company_id
- fiscal_period
- revenue
- net_income
- assets
- liabilities