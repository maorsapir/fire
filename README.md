# fire

This repository provides a simple Liquid snippet for Shopify to display only positive reviews (rating 4 and above).

## Snippet Usage

1. Copy the `snippets/good_reviews.liquid` file into your Shopify theme's `snippets` directory.
2. Include the snippet in a product template where you want the positive reviews to appear:

```liquid
{% render 'good_reviews' %}
```

The snippet assumes that the product has a `reviews` array with fields `rating`, `author`, and `comment`. Only reviews with a rating of 4 or higher are displayed.
