# Hola Devon Taco Truck - Potential Answer Key

This is not the only correct answer.

Students may suggest different attributes and functions. The aim is to see whether their ideas make sense for the module and whether they can explain why the system might need them.

## Customer Module

Possible attributes:

- `customer_id`
- `name`
- `phone_number`
- `email_address`
- `allergy_notes`
- `favourite_items`
- `loyalty_points`
- `order_history`

Possible functions:

- `create_customer()`
- `update_contact_details()`
- `add_allergy_note()`
- `view_order_history()`
- `add_loyalty_points()`
- `find_customer_by_name()`

## Inventory Module

Possible attributes:

- `ingredient_id`
- `ingredient_name`
- `quantity_available`
- `unit`
- `minimum_stock_level`
- `supplier`
- `expiry_date`
- `storage_location`

Possible functions:

- `check_stock_level()`
- `reduce_stock()`
- `add_stock()`
- `mark_item_expired()`
- `list_low_stock_items()`
- `check_if_ingredient_available()`

## Item Module

Possible attributes:

- `item_id`
- `name`
- `description`
- `price`
- `category`
- `available`
- `spice_level`
- `allergens`

Possible functions:

- `create_item()`
- `update_price()`
- `mark_as_sold_out()`
- `mark_as_available()`
- `add_allergen()`
- `calculate_discount_price()`

## Menu Module

Possible attributes:

- `menu_id`
- `menu_name`
- `active_date`
- `items`
- `daily_specials`
- `sold_out_items`
- `opening_time`
- `closing_time`

Possible functions:

- `add_item_to_menu()`
- `remove_item_from_menu()`
- `show_available_items()`
- `set_daily_special()`
- `hide_sold_out_items()`
- `publish_menu()`

## Order Module

Possible attributes:

- `order_id`
- `customer_name`
- `items_ordered`
- `total_price`
- `payment_status`
- `order_status`
- `created_at`
- `special_instructions`

Possible functions:

- `create_order()`
- `add_item_to_order()`
- `remove_item_from_order()`
- `calculate_total()`
- `mark_as_paid()`
- `mark_as_ready()`
- `cancel_order()`

## Recipe Module

Possible attributes:

- `recipe_id`
- `recipe_name`
- `ingredients`
- `steps`
- `prep_time_minutes`
- `cook_time_minutes`
- `portion_size`
- `allergens`

Possible functions:

- `create_recipe()`
- `update_recipe_steps()`
- `list_required_ingredients()`
- `scale_recipe()`
- `check_recipe_allergens()`
- `calculate_prep_time()`

## Safety Module

Possible attributes:

- `check_id`
- `check_type`
- `checked_by`
- `checked_at`
- `temperature_reading`
- `cleaning_task`
- `status`
- `notes`

Possible functions:

- `record_temperature_check()`
- `record_cleaning_task()`
- `flag_safety_issue()`
- `mark_issue_resolved()`
- `list_open_safety_checks()`
- `check_allergen_warning()`

## Good Student Answers Might Include

- Clear names that describe what the data or function is for.
- Attributes that belong in the chosen module.
- Functions that use or change the module's data.
- Ideas that connect to the real taco truck scenario.
- Simple, understandable names rather than overly complicated technical ones.

## Discussion Prompts

- Which attributes are essential, and which are just nice to have?
- Which functions change data, and which only read or display data?
- Did any ideas appear in more than one module?
- Should `allergens` belong to an item, a recipe, or both?
- Should `customer_name` be stored directly on an order, or should the order link to a customer?
- What could go wrong if the inventory module is not updated when an order is placed?
- Which module would be most important during a busy lunch rush?

## Stretch Ideas

For stronger learners, ask them to group their functions into:

- create
- read
- update
- delete
- calculate
- check/validate

They can also think about which modules need to talk to each other.

Examples:

- An order may need menu items.
- A recipe may need inventory ingredients.
- A safety warning may need item or recipe allergen data.
- Inventory may need to change when an order is completed.
