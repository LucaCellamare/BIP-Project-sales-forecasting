# BIP-Project-sales-forecasting

### Course Project
**Dataset Description**:

This year project is based on a sales forecasting dataset with aggregated information for different products (SKU) throughout a 3-years time window:
•

•

_Weekly data (Dec 2016 – Dec 2019)_
Data are available for 43 SKU but the target for the prediction is restricted to 12 SKUs

**SKU** | Unique identifier for the products | int

**Pack** | Type of pack in which the product is sold | str

**Size (GM)** | Product weight | float

**Brand** | Product brand | str

**Price** | Planned price of sale for the product in week w | float

**POS_exposed w-1** | Number of stores in which the product was put on evidence at w-1 | int

**Volume_on_promo w-1** | % Volume of product put on promo at w-1 | float

**Sales w-1** | Sales of product at w-1 (lagged target) | int

**Scope** | Boolean that indicates SKUs in scope (target) | bool
