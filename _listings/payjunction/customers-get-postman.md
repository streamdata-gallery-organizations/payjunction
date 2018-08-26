{
  "info": {
    "name": "PayJunction Get Customers",
    "_postman_id": "3bec1bd7-9852-4050-8be7-6a89c5ed3d40",
    "description": "Gets a list of 15 customers",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Customers",
      "item": [
        {
          "id": "f726eafc-b461-4217-aee1-2d31346fa898",
          "name": "CustomersGet",
          "request": {
            "url": "http://example.com/customers?limit=%7B%7D&offset=%7B%7D",
            "method": "GET",
            "header": [
              {
                "key": "X-PJ-Application-Key",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Gets a list of 15 customers"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "06deb45e-334a-47a9-844f-076c97138cd5"
            }
          ]
        }
      ]
    }
  ]
}