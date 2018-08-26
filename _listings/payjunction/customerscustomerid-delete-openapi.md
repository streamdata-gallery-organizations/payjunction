---
swagger: "2.0"
x-collection-name: PayJunction
x-complete: 0
info:
  title: PayJunction Delete Customers
  description: /customers/{customerid}.
  version: 1.0.0
host: example.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /customers:
    get:
      summary: Get Customers
      description: Gets a list of 15 customers
      operationId: CustomersGet
      x-api-path-slug: customers-get
      parameters:
      - in: query
        name: limit
      - in: query
        name: offset
      - in: header
        name: X-PJ-Application-Key
      responses:
        200:
          description: OK
      tags:
      - Customers
  /customers/{customerId}:
    get:
      summary: Get Customers
      description: /customers/{customerid}.
      operationId: CustomersByCustomerIdGet
      x-api-path-slug: customerscustomerid-get
      parameters:
      - in: path
        name: customerId
      - in: header
        name: X-PJ-Application-Key
      responses:
        200:
          description: OK
      tags:
      - Customers
    put:
      summary: Put Customers
      description: /customers/{customerid}.
      operationId: CustomersByCustomerIdPut
      x-api-path-slug: customerscustomerid-put
      parameters:
      - in: formData
        name: companyName
      - in: formData
        name: custom1
      - in: path
        name: customerId
      - in: formData
        name: defaultAddressId
      - in: formData
        name: email
      - in: formData
        name: firstName
      - in: formData
        name: identifier
      - in: formData
        name: jobTitle
      - in: formData
        name: lastName
      - in: formData
        name: middleName
      - in: formData
        name: phone
      - in: formData
        name: phone2
      - in: formData
        name: website
      - in: header
        name: X-PJ-Application-Key
      responses:
        200:
          description: OK
      tags:
      - Customers
    delete:
      summary: Delete Customers
      description: /customers/{customerid}.
      operationId: CustomersByCustomerIdDelete
      x-api-path-slug: customerscustomerid-delete
      parameters:
      - in: path
        name: customerId
      - in: header
        name: X-PJ-Application-Key
      responses:
        200:
          description: OK
      tags:
      - Customers
x-streamrank:
  polling_total_time_average: 0
  polling_size_download_average: 0
  streaming_total_time_average: 0
  streaming_size_download_average: 0
  change_yes: 0
  change_no: 0
  time_percentage: 0
  size_percentage: 0
  change_percentage: 0
  last_run: ""
  days_run: 0
  minute_run: 0
---