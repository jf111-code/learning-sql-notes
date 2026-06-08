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

## Lessons From Chapter 2

### Data Types

company_name → VARCHAR

ticker → VARCHAR

trade_date → DATE

close_price → DECIMAL

volume → BIGINT

revenue → DECIMAL

net_income → DECIMAL