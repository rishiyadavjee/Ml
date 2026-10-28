# Gujarat Fresh Mart — Synthetic Practice Datasets

IMPORTANT: These files are synthetic practice data created for learning. They are NOT the official instructor-provided hackathon datasets and must not be presented as official results.

Files:
- customers.csv: one row per loyalty member; member_id, joining_date, city, age_band, household_size, preferred_store, declared_preference
- transactions.csv: transaction line items; bill_id, member_id, date, store_id, product_id, quantity, amount
- products.csv: product_id, product_name, category, price_band
- stores.csv: store_id, city, format, opening_date
- coupon_history.csv: coupon history; member_id, coupon_id, date_sent, used

Some deliberate data-quality issues are included for audit practice (missing values, invalid dates, invalid numeric values, orphan IDs, and duplicate rows). Document the issues you actually detect rather than assuming every planted issue is detected.

All member IDs, transactions, coupon records, and amounts are fabricated. Use these datasets to practise audit/preparation, feature engineering, association rules, modeling, and reproducible reporting.
