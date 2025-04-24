# 🛍️ E-Commerce Database Project

This project is a comprehensive relational database design for an e-commerce platform. It includes an Entity-Relationship Diagram (ERD) and the full SQL schema implementation. The database is built to support flexible product variations, attributes, sizes, and categories.

---

## 🎯 Objective

To design and implement a robust database system that can support an e-commerce platform’s data structure, including:

- Product listings
- Brands and categories
- Sizes and colors
- Custom attributes
- Images and variations

---

## 📐 Entity-Relationship Diagram (ERD)

The ERD visually defines all relationships and constraints between the following tables:

- `product_image`
- `color`
- `product_category`
- `product`
- `product_item`
- `brand`
- `product_variation`
- `size_category`
- `size_option`
- `product_attribute`
- `attribute_category`
- `attribute_type`


---

## 🗃️ Tables Overview

| Table Name           | Description                                                  |
|----------------------|--------------------------------------------------------------|
| `product_image`      | Stores image URLs for each product item                      |
| `color`              | Lists available colors with hex codes                        |
| `product_category`   | Categorizes products (e.g., electronics, clothing)           |
| `product`            | Holds general product information                            |
| `product_item`       | Represents individual purchasable product units              |
| `brand`              | Stores brand-related metadata                                |
| `product_variation`  | Defines variations of a product by size and color            |
| `size_category`      | Groups size options (e.g., clothing sizes, shoe sizes)       |
| `size_option`        | Contains size options (e.g., S, M, L, 42)                    |
| `product_attribute`  | Assigns custom attributes to products                        |
| `attribute_category` | Groups attributes into categories (e.g., physical, technical)|
| `attribute_type`     | Specifies the type of each attribute (text, number, etc.)    |

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
