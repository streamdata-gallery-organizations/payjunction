---
swagger: "2.0"
x-collection-name: PayJunction
x-complete: 0
info:
  title: PayJunction Put Customers Vaults Card Vault
  description: /customers/{customerid}/vaults/{vaultid} (card).
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
  /customers/:
    post:
      summary: Post Customers
      description: Add a new customer
      operationId: CustomersPost
      x-api-path-slug: customers-post
      parameters:
      - in: formData
        name: companyName
        description: Text, Max Length 64
      - in: formData
        name: custom1
        description: Text, Max Length 32
      - in: formData
        name: email
        description: Email (1), Max Length 128
      - in: formData
        name: firstName
        description: Text, Max Length 16
      - in: formData
        name: identifier
        description: Text, Max Length 64
      - in: formData
        name: jobTitle
        description: Text, Max Length 32
      - in: formData
        name: lastName
        description: Text, Max Length 32
      - in: formData
        name: middleName
        description: Text, Max Length 32
      - in: formData
        name: phone
        description: Phone Number, Max Length 24, Must contain at least 10 digits
      - in: formData
        name: phone2
        description: Phone Number, Max Length 24, Must contain at least 10 digits
      - in: formData
        name: website
        description: Text, Max Length 128
      - in: header
        name: X-PJ-Application-Key
      responses:
        200:
          description: OK
      tags:
      - Customers
  /customers/{customerId}/notes:
    get:
      summary: Get Customers Notes
      description: /customers/{customerid}/notes.
      operationId: CustomersNotesByCustomerIdGet
      x-api-path-slug: customerscustomeridnotes-get
      parameters:
      - in: path
        name: customerId
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
      - Notes
    post:
      summary: Post Customers Notes
      description: /customers/{customerid}/notes.
      operationId: CustomersNotesByCustomerIdPost
      x-api-path-slug: customerscustomeridnotes-post
      parameters:
      - in: path
        name: customerId
      - in: formData
        name: note
        description: Max Length 2048
      - in: header
        name: X-PJ-Application-Key
      responses:
        200:
          description: OK
      tags:
      - Customers
      - Notes
  /customers/{customerId}/notes/{noteId}:
    get:
      summary: Get Customers Notes
      description: /customers/{customerid}/notes/{noteid}.
      operationId: CustomersNotesByCustomerIdAndNoteIdGet
      x-api-path-slug: customerscustomeridnotesnoteid-get
      parameters:
      - in: path
        name: customerId
      - in: path
        name: noteId
      - in: header
        name: X-PJ-Application-Key
      responses:
        200:
          description: OK
      tags:
      - Customers
      - Notes
    put:
      summary: Put Customers Notes
      description: /customers/{customerid}/notes/{noteid}.
      operationId: CustomersNotesByCustomerIdAndNoteIdPut
      x-api-path-slug: customerscustomeridnotesnoteid-put
      parameters:
      - in: header
        name: Content-Type
      - in: path
        name: customerId
      - in: formData
        name: note
        description: Max Length 2048
      - in: path
        name: noteId
      - in: header
        name: X-PJ-Application-Key
      responses:
        200:
          description: OK
      tags:
      - Customers
      - Notes
    delete:
      summary: Delete Customers Notes
      description: /customers/{customerid}/notes/{noteid}.
      operationId: CustomersNotesByCustomerIdAndNoteIdDelete
      x-api-path-slug: customerscustomeridnotesnoteid-delete
      parameters:
      - in: path
        name: customerId
      - in: path
        name: noteId
      - in: header
        name: X-PJ-Application-Key
      responses:
        200:
          description: OK
      tags:
      - Customers
      - Notes
  /customers/{customerId}/vaults/:
    get:
      summary: Get Customers Vaults
      description: Retrieve customer's payment vaults
      operationId: CustomersVaultsByCustomerIdGet
      x-api-path-slug: customerscustomeridvaults-get
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
      - Vaults
  /customers/{customerId}/vaults/{vaultId}:
    get:
      summary: Get Customers Vaults
      description: /customers/{customerid}/vaults/{vaultid}.
      operationId: CustomersVaultsByCustomerIdAndVaultIdGet
      x-api-path-slug: customerscustomeridvaultsvaultid-get
      parameters:
      - in: path
        name: customerId
      - in: path
        name: vaultId
      - in: header
        name: X-PJ-Application-Key
      responses:
        200:
          description: OK
      tags:
      - Customers
      - Vaults
    delete:
      summary: Delete Customers Vaults
      description: /customers/{customerid}/vaults/{vaultid}.
      operationId: CustomersVaultsByCustomerIdAndVaultIdDelete
      x-api-path-slug: customerscustomeridvaultsvaultid-delete
      parameters:
      - in: path
        name: customerId
      - in: path
        name: vaultId
      - in: header
        name: X-PJ-Application-Key
      responses:
        200:
          description: OK
      tags:
      - Customers
      - Vaults
  /customers/{customerId}/vaults:
    post:
      summary: Post Customers Vaults
      description: /customers/{customerid}/vaults (card).
      operationId: CustomersVaultsByCustomerIdPost2
      x-api-path-slug: customerscustomeridvaults-post
      parameters:
      - in: formData
        name: address
      - in: formData
        name: addressId
      - in: formData
        name: cardExpMonth
        description: 1-12
      - in: formData
        name: cardExpYear
        description: YYYY, YY
      - in: formData
        name: cardNumber
        description: 5105105105105100,5105-1051-0510-5100,5105 1051 0510 5100
      - in: formData
        name: city
      - in: path
        name: customerId
      - in: formData
        name: state
      - in: header
        name: X-PJ-Application-Key
      - in: formData
        name: zip
      responses:
        200:
          description: OK
      tags:
      - Customers
      - Vaults
  /customers/{customerId}/vaults/{achVault}:
    put:
      summary: Put Customers Vaults ACH Vault
      description: /customers/{customerid}/vaults/{vaultid} (ach).
      operationId: CustomersVaultsByCustomerIdAndAchVaultPut
      x-api-path-slug: customerscustomeridvaultsachvault-put
      parameters:
      - in: formData
        name: achAccountType
        description: CHECKING, SAVINGS
      - in: formData
        name: achType
        description: CCD, PPD, TEL, WEB
      - in: path
        name: achVault
      - in: formData
        name: address
      - in: formData
        name: addressId
      - in: formData
        name: city
      - in: path
        name: customerId
      - in: formData
        name: state
      - in: header
        name: X-PJ-Application-Key
      - in: formData
        name: zip
      responses:
        200:
          description: OK
      tags:
      - Customers
      - Vaults
      - ACH
      - Vault
  /customers/{customerId}/vaults/{cardVault}:
    put:
      summary: Put Customers Vaults Card Vault
      description: /customers/{customerid}/vaults/{vaultid} (card).
      operationId: CustomersVaultsByCustomerIdAndCardVaultPut
      x-api-path-slug: customerscustomeridvaultscardvault-put
      parameters:
      - in: formData
        name: address
      - in: formData
        name: addressId
      - in: formData
        name: cardExpMonth
        description: 1-12
      - in: formData
        name: cardExpYear
        description: YYYY, YY
      - in: path
        name: cardVault
      - in: formData
        name: city
      - in: path
        name: customerId
      - in: formData
        name: state
      - in: header
        name: X-PJ-Application-Key
      - in: formData
        name: zip
      responses:
        200:
          description: OK
      tags:
      - Customers
      - Vaults
      - Card
      - Vault
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