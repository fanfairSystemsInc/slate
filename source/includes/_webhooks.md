# Introduction

The webhooks are used in response to certain actions within Amplify. For example if an order is occuring, we will send a request to your webhook address asking for your system to process the order.

You can register your Webhook endpoint within the amplify API developer integration.

A list of the webhook types are:

- get_product
- create_customer
- create_order
- get_shipping_class

## General request structure

The general overall structure for the webhook request is as follows:

> Example request

```json
{
  "api_version": "v1",
  "created": "213435343",
  "data": {
    "object": {
    }
  },
  "id": "d35e34e333",
  "livemode": true,
  "object": "product",
  "type": "get_product",
  "user_id": "365345"
  }

```

The type attribute will change depending on the type of webhook being sent.

## get_product

The structure of the create refund object is as follows:

> Example request

```json
{
  "product_ref_id": "389353",
  "integration_id": "32434543"
}

```

To respond to this request properly an example response is as follows:

> Example response

```json
{
  "_key": "string",
  "categories": "string",
  "currency": "string",
  "handle": "string",
  "image_source_url": "string",
  "image_thubnail": "string",
  "is_downloadable": true,
  "is_virtual": true,
  "keyword_locked": true,
  "out_stock": true,
  "price": 0,
  "price_compare": 0,
  "product_tags": [
    "string"
  ],
  "published_at": "2017-02-12T00:24:35Z",
  "ref_id": "string",
  "sku": "string",
  "source": "string",
  "tags": "string",
  "title": "string",
  "type": "string",
  "user_id": "string",
  "variants": [
    {
      "attributes": [
        {
          "name": "string",
          "option": "string",
          "slug": "string"
        }
      ],
      "created": "2017-02-12T00:24:35Z",
      "image_source_url": "string",
      "in_stock": true,
      "inventory_management": "string",
      "inventory_quantity": "string",
      "price": 0,
      "price_compare": 0,
      "product_ref_id": "string",
      "ref_id": "string",
      "sku": "string",
      "taxable": true,
      "title": "string",
      "updated": "2017-02-12T00:24:35Z",
      "visible": true,
      "weight": 0
    }
  ],
  "vendor": "string"
}

```

The product will be used to check for inventory numbers and other attributes as needed.

## create_customer

The structure of the create refund object is as follows:

> Example request

```json
{
  "first_name": "John",
  "last_name": "Smith",
  "email": "john@mail.com",
  "phone": "7786734536",
  "profile_id": "32434543",
  "shipping_address_1": "234 Long Lane",
  "shipping_address_2": "#7867",
  "shipping_city": "Vancouver",
  "shipping_state": "BC",
  "shipping_zip": "V6B 0Y1",
  "shipping_country": "CA",
  "integration_id": "32434543"
}

```

To respond to this request properly an example response is as follows:

> Example response

```json
{
  "ref_id": "string"
}

```

The reference id for amplify to store the new customer against.

## create_order

The structure of the create a new order object is as follows:

> Example request

```json
{
  "type": "1234566",
  "variation_id": "completed",
  "first_name": "John",
  "last_name": "Smith",
  "email": "john@mail.com",
  "phone": "7786734536",
  "shipping_rate": 49.98,
  "shipping_rate_code": 56.00,
  "tax_rate": 0,
  "total": 0,
  "quantity": "234324323",
  "product_ref_id": "234324323",
  "profile_ref_id": "234324323",
  "shipping_address_1": "234 Long Lane",
  "shipping_address_2": "#7867",
  "shipping_city": "Vancouver",
  "shipping_state": "BC",
  "shipping_zip": "V6B 0Y1",
  "shipping_country": "CA",
  "integration_id": "32434543"
}

```

To respond to this request properly an example response is as follows:

> Example response

```json
{
  "customer_ref_id": "1234566",
  "financial_status": "completed",
  "iqx_order": "2314324",
  "line_items": [
    {
      "attributes": [
        {
          "fulfillable_quantity": 2,
          "price": 29.99,
          "product_ref_id": 2137432,
          "ref_id": 1234324234,
          "sku": "123nds3"
        }
      ]
    }
  ],
  "processed_at": "2017-02-12T00:24:35Z",
  "ref_id": 123143242,
  "subtotal_price": 49.98,
  "total_price": 56.00,
  "total_shipping": 0,
  "total_tax": 0,
  "user_id": "234324323"
}

```

The reference id for amplify to store the new customer against.

## get_shipping_class

The structure of the get shipping class object is as follows:

> Example request

```json
{
  "shipping_country": "CA",
  "shipping_state": "BC",
  "integration_id": "John",
  "price": "29.99",
  "weight": 0
}

```

To respond to this request properly an example response is as follows:

> Example response

```json
{
  "Standard Shipping": 10.00,
  "Express Shipping": 29.99,
}

```

A JSON object with addtibute keys as the shipping rate name and the value as the cost of the shipping.
