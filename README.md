# User Behavior Analysis

## Project Overview

This project analyzes Taobao user behavior data, including page views,
favorites, cart additions, and purchases.

## Project Objectives

- Load and process large-scale user behavior data
- Perform exploratory data analysis
- Build user, item, and time-based features
- Predict future purchase behavior
- Provide business-oriented recommendations

## Data Fields

- `time`: behavior timestamp
- `user_id`: user identifier
- `item_id`: item identifier
- `item_category`: item category identifier
- `behavior_type`: 1=page view, 2=favorite, 3=cart, 4=purchase

## Project Structure

```text
data/        Raw and processed data
notebooks/   Exploratory analysis notebooks
src/         Reusable Python scripts
sql/         SQL scripts
reports/     Reports and learning notes
outputs/     Charts and model outputs