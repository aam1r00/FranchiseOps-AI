# FranchiseOps Database

This folder contains the database schema and dataset used for the FranchiseOps AI project.

## Database Schema

`schema.sql` contains the SQL definitions for the project database tables.

## Dataset

The `data/` folder contains the datasets used for the FranchiseOps system:

- franchises.csv
- outlets.csv
- food_items.csv
- outlet_menu.csv
- sales.csv
- inventory.csv
- stock_movements.csv
- reorders.csv
- staff.csv
- attendance.csv
- marketing_campaigns.csv
- outlet_performance.csv
- validation_report.csv

## Dataset Coverage

The dataset supports:

- Outlet Performance Intelligence
- Inventory Intelligence and Optimization
- Workforce Intelligence
- Marketing Intelligence

## Database Platform

The dataset was imported and tested in Supabase using PostgreSQL.

## Validation

`validation_report.csv` contains the dataset validation results, including checks for duplicate records, broken relationships, negative stock, and invalid quantities.
