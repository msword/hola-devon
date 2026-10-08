# Analytics Module

This module is about the reports, analytics, and trends that are important to the taco truck business.

The team wants to understand what is selling well, which times are busiest, how much money they are making, where waste is happening, and what changes might improve the next service.

This module will likely use data from the order, inventory, menu, and customer modules to create useful summaries for the team.

## Attributes

Add a list of information the system might need to store or calculate for reports.

- `report_id` - a unique identifier for each generated report.
- `report_date` - the date the data was collected or reported.
- `service_period` - the time period covered, such as lunch rush, evening service, or a full day.
- `gross_income` - total revenue from all sales before costs and taxes.
- `gross_expenses` - total costs of ingredients, packaging, staff, and other operating costs.
- `gross_profit` - revenue minus direct costs.
- `net_profit` - profit after expenses and taxes are considered.
- `tax_rate` - local sales tax rate applied to sales.
- `total_orders` - total number of orders placed during the reporting period.
- `average_order_value` - average spend per order.
- `most_common_item` - the menu item sold most often.
- `best_selling_category` - category with the strongest sales, such as tacos, burritos, or drinks.
- `peak_service_time` - busiest hour or period of service.
- `customer_count` - number of unique or total customers served.
- `repeat_customer_rate` - percentage of customers who return for another purchase.
- `inventory_usage` - ingredients consumed and used over a period.
- `stock_loss` - waste, spoilage, or inventory lost during service.
- `daily_sales_trend` - comparison of sales between different days or service windows.
- `sales_by_item` - totals grouped by individual menu item.
- `sales_by_hour` - sales totals grouped by hour of the day.
- `food_waste_amount` - amount of food discarded or spoiled.
- `profit_margin` - percentage of profit relative to sales.
- `top_customers` - highest-spending or most frequent buyers.

## Functions

Add a list of actions the analytics module might need to perform.

- `generate_daily_report()` - create a summary of sales, profit, and key trends for the day.
- `calculate_total_revenue()` - add up all sales for a selected time period.
- `calculate_profit()` - determine gross or net profit from income and expenses.
- `track_peak_hours()` - identify the busiest times in the service day.
- `identify_top_selling_items()` - find the products that sell most frequently or bring in the most revenue.
- `compare_sales_by_day()` - compare performance across different days or dates.
- `calculate_average_order_value()` - measure how much each customer tends to spend.
- `summarize_inventory_usage()` - review which ingredients are being used most heavily.
- `measure_waste()` - track spoilage, missing stock, or discarded food.
- `forecast_demand()` - estimate which items may sell more during future lunch or evening services.
- `generate_customer_insights()` - identify returning customers and purchasing trends.
- `list_low_profit_items()` - highlight products that contribute little profit relative to their cost.
- `show_best_performing_menu_items()` - display items with the strongest sales numbers.
- `create_financial_summary()` - combine sales, costs, taxes, and profit into one report.
- `export_report()` - share analytics in a printed, PDF, or spreadsheet-friendly format.

This module supports smart decisions for the taco truck, such as adjusting prices, stocking more of a popular item, reducing waste, and planning service staffing around busy periods.
