# dataset-shopify
Shopify app to practice Spark applications

Columns:
==========
urlApp url -- used to join other tables

title -- Title of app

developer -- Developer title

developer_link -- Link to developers page

icon -- Link to app icon

rating -- Rating from app page

reviews_count -- Number of the reviews from app page

description -- Extracted description of the app

description_raw -- HTML markup with description of the app

short_description -- Extracted short description of the app

short_description_raw -- HTML markup with short description of the app

key_benefits_raw -- HTML markup with benefits of the app (the developer selects them when submits the new app)

key_benefits -- Extracted benefits of the app (the developer selects them when submits the new app)

pricing_raw -- HTML markup with pricing information, the structured versions of this data is in plan_features and pricing_plans tables

pricing -- Extracted pricing information, the structured versions of this data is in plan_features and pricing_plans tables

pricing_hint -- Short summary of pricing advantages
