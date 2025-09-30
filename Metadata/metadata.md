# 🛒 Metadata : Ecommerce Analysis in Power BI

## 🗺️ State Mapping Table

| Column             | Description                                                                 |
|--------------------|-----------------------------------------------------------------------------|
| Order State        | State code, description, and all its variations                             |
| State              | Full name of the state                                                      |
| Region             | Region name                                                                 |
| State Abbreviation | Standardized state code                                                     |

---

## 📦 Product Table

| Column                | Description                                                                 |
|------------------------|-----------------------------------------------------------------------------|
| Stock Code             | Product code                                                               |
| Weight                 | Weight of a single unit                                                    |
| Landed Cost            | Manufacturer cost + freight                                                |
| Shipping_Cost_1000_m   | Average cost of shipping 1000 miles to customers                           |
| Description            | Most recent product description                                            |
| Category               | Product category                                                           |

---

## 👤 Customer Table

| Column         | Description                                                                 |
|----------------|-----------------------------------------------------------------------------|
| Customer ID    | Unique customer identifier                                                  |
| Order City     | City of the order                                                           |
| Order Postal   | Postal code of the order                                                    |
| Order State    | State of the order                                                          |
| Latitude       | Latitude of customer location                                               |
| Longitude      | Longitude of customer location                                              |

---

## 💰 Sales Table

| Column          | Description                                                                 |
|------------------|-----------------------------------------------------------------------------|
| Transaction Date | Date of purchase                                                           |
| Customer ID      | Customer identifier                                                        |
| Description      | Product description                                                        |
| Stock Code       | Product code                                                               |
| Invoice No       | Invoice identifier (multiple products per checkout)                        |
| Quantity         | Quantity of product purchased                                              |
| Sales            | Total amount of product in a single checkout                               |
| Unit Price       | Unit price of the product                                                  |

---

> 📁 This metadata supports the Power BI dashboard for ecommerce performance analysis, customer segmentation, and regional sales insights.
