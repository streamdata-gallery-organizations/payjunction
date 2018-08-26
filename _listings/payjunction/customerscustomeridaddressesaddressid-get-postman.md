{
  "info": {
    "name": "PayJunction Get Customers Addresses",
    "_postman_id": "66b27326-d2c8-441f-ba55-8eecd27b486b",
    "description": "/customers/{customerid}/addresses/{addressid}.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Customers",
      "item": [
        {
          "id": "e4605cdf-3bc1-4659-a1e3-70faac5a06a1",
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
              "id": "072eb084-dc14-44fa-8bdb-f12a3873a0a5"
            }
          ]
        },
        {
          "id": "3fed8865-3436-44f5-a9f9-1eefcfe0b6f3",
          "name": "CustomersByCustomerIdGet",
          "request": {
            "url": {
              "protocol": "http",
              "host": "example.com",
              "path": [
                "customers/:customerId"
              ],
              "variable": [
                {
                  "id": "customerId",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
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
            "description": "/customers/{customerid}."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "bc1916af-17e3-4ca4-b613-c6437d82b6a3"
            }
          ]
        },
        {
          "id": "009692c3-e0d7-4950-872f-a975c6a11d40",
          "name": "CustomersByCustomerIdPut",
          "request": {
            "url": {
              "protocol": "http",
              "host": "example.com",
              "path": [
                "customers/:customerId"
              ],
              "variable": [
                {
                  "id": "customerId",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "PUT",
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
              "mode": "urlencoded",
              "urlencoded": [
                {
                  "key": "companyName",
                  "value": "{}",
                  "disabled": false,
                  "description": ""
                },
                {
                  "key": "custom1",
                  "value": "{}",
                  "disabled": false,
                  "description": ""
                },
                {
                  "key": "defaultAddressId",
                  "value": "{}",
                  "disabled": false,
                  "description": ""
                },
                {
                  "key": "email",
                  "value": "{}",
                  "disabled": false,
                  "description": ""
                },
                {
                  "key": "firstName",
                  "value": "{}",
                  "disabled": false,
                  "description": ""
                },
                {
                  "key": "identifier",
                  "value": "{}",
                  "disabled": false,
                  "description": ""
                },
                {
                  "key": "jobTitle",
                  "value": "{}",
                  "disabled": false,
                  "description": ""
                },
                {
                  "key": "lastName",
                  "value": "{}",
                  "disabled": false,
                  "description": ""
                },
                {
                  "key": "middleName",
                  "value": "{}",
                  "disabled": false,
                  "description": ""
                },
                {
                  "key": "phone",
                  "value": "{}",
                  "disabled": false,
                  "description": ""
                },
                {
                  "key": "phone2",
                  "value": "{}",
                  "disabled": false,
                  "description": ""
                },
                {
                  "key": "website",
                  "value": "{}",
                  "disabled": false,
                  "description": ""
                }
              ]
            },
            "description": "/customers/{customerid}."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "a34f7208-5be8-488c-9340-dc9a66bfbf4b"
            }
          ]
        },
        {
          "id": "87582643-d06e-4fe6-a2e9-a28ae8577efc",
          "name": "CustomersByCustomerIdDelete",
          "request": {
            "url": {
              "protocol": "http",
              "host": "example.com",
              "path": [
                "customers/:customerId"
              ],
              "variable": [
                {
                  "id": "customerId",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "DELETE",
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
            "description": "/customers/{customerid}."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "a8678de9-d72f-446e-800c-8e54b7133b17"
            }
          ]
        },
        {
          "id": "299840be-af45-4b4f-bff3-44edabcb8127",
          "name": "CustomersPost",
          "request": {
            "url": "http://example.com/customers/",
            "method": "POST",
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
              "mode": "urlencoded",
              "urlencoded": [
                {
                  "key": "companyName",
                  "value": "{}",
                  "disabled": false,
                  "description": "Text, Max Length 64"
                },
                {
                  "key": "custom1",
                  "value": "{}",
                  "disabled": false,
                  "description": "Text, Max Length 32"
                },
                {
                  "key": "email",
                  "value": "{}",
                  "disabled": false,
                  "description": "Email (1), Max Length 128"
                },
                {
                  "key": "firstName",
                  "value": "{}",
                  "disabled": false,
                  "description": "Text, Max Length 16"
                },
                {
                  "key": "identifier",
                  "value": "{}",
                  "disabled": false,
                  "description": "Text, Max Length 64"
                },
                {
                  "key": "jobTitle",
                  "value": "{}",
                  "disabled": false,
                  "description": "Text, Max Length 32"
                },
                {
                  "key": "lastName",
                  "value": "{}",
                  "disabled": false,
                  "description": "Text, Max Length 32"
                },
                {
                  "key": "middleName",
                  "value": "{}",
                  "disabled": false,
                  "description": "Text, Max Length 32"
                },
                {
                  "key": "phone",
                  "value": "{}",
                  "disabled": false,
                  "description": "Phone Number, Max Length 24, Must contain at least 10 digits"
                },
                {
                  "key": "phone2",
                  "value": "{}",
                  "disabled": false,
                  "description": "Phone Number, Max Length 24, Must contain at least 10 digits"
                },
                {
                  "key": "website",
                  "value": "{}",
                  "disabled": false,
                  "description": "Text, Max Length 128"
                }
              ]
            },
            "description": "Add a new customer"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "0b98ef5c-bf3a-4cf4-8335-f4aef8c053b5"
            }
          ]
        },
        {
          "id": "6a9f1dec-d97f-4ee4-8cc7-d372b3d17192",
          "name": "CustomersNotesByCustomerIdGet",
          "request": {
            "url": {
              "protocol": "http",
              "host": "example.com",
              "path": [
                "customers/:customerId/notes"
              ],
              "query": [
                {
                  "key": "limit",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "offset",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "customerId",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
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
            "description": "/customers/{customerid}/notes."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "51427f09-b9e7-458c-bc0e-d8b90f636151"
            }
          ]
        },
        {
          "id": "f3bcf2eb-8943-4bce-a896-92e9fc0a8be4",
          "name": "CustomersNotesByCustomerIdPost",
          "request": {
            "url": {
              "protocol": "http",
              "host": "example.com",
              "path": [
                "customers/:customerId/notes"
              ],
              "variable": [
                {
                  "id": "customerId",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "POST",
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
              "mode": "urlencoded",
              "urlencoded": [
                {
                  "key": "note",
                  "value": "{}",
                  "disabled": false,
                  "description": "Max Length 2048"
                }
              ]
            },
            "description": "/customers/{customerid}/notes."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f6cec56f-6f3a-4611-b123-c55adfb8da91"
            }
          ]
        },
        {
          "id": "68681b8d-6721-415b-b9cf-24784c505ee5",
          "name": "CustomersNotesByCustomerIdAndNoteIdGet",
          "request": {
            "url": {
              "protocol": "http",
              "host": "example.com",
              "path": [
                "customers/:customerId/notes/:noteId"
              ],
              "variable": [
                {
                  "id": "customerId",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "noteId",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
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
            "description": "/customers/{customerid}/notes/{noteid}."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "cb196b17-659e-458e-994c-592c7329ff4e"
            }
          ]
        },
        {
          "id": "faf875a4-a3ab-4039-84e2-4b85d92c7823",
          "name": "CustomersNotesByCustomerIdAndNoteIdPut",
          "request": {
            "url": {
              "protocol": "http",
              "host": "example.com",
              "path": [
                "customers/:customerId/notes/:noteId"
              ],
              "variable": [
                {
                  "id": "customerId",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "noteId",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "PUT",
            "header": [
              {
                "key": "Content-Type",
                "value": "{}",
                "description": "",
                "disabled": false
              },
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
              "mode": "urlencoded",
              "urlencoded": [
                {
                  "key": "note",
                  "value": "{}",
                  "disabled": false,
                  "description": "Max Length 2048"
                }
              ]
            },
            "description": "/customers/{customerid}/notes/{noteid}."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "5ad974b7-6f70-4f6a-b072-adba161a5534"
            }
          ]
        },
        {
          "id": "1ef2a1cb-1b03-4d29-b8b3-c228373bdc7b",
          "name": "CustomersNotesByCustomerIdAndNoteIdDelete",
          "request": {
            "url": {
              "protocol": "http",
              "host": "example.com",
              "path": [
                "customers/:customerId/notes/:noteId"
              ],
              "variable": [
                {
                  "id": "customerId",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "noteId",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "DELETE",
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
            "description": "/customers/{customerid}/notes/{noteid}."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "06ad5486-be08-4da6-afb5-7830a3e96958"
            }
          ]
        },
        {
          "id": "17e52cdc-054b-4440-9b39-507b89464fdb",
          "name": "CustomersVaultsByCustomerIdGet",
          "request": {
            "url": {
              "protocol": "http",
              "host": "example.com",
              "path": [
                "customers/:customerId/vaults/"
              ],
              "variable": [
                {
                  "id": "customerId",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
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
            "description": "Retrieve customer's payment vaults"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "130888d5-2593-4194-9fd4-e8c6bc45d260"
            }
          ]
        },
        {
          "id": "50c9d25a-a957-4b03-bcd9-12cd18e4b066",
          "name": "CustomersVaultsByCustomerIdAndVaultIdGet",
          "request": {
            "url": {
              "protocol": "http",
              "host": "example.com",
              "path": [
                "customers/:customerId/vaults/:vaultId"
              ],
              "variable": [
                {
                  "id": "customerId",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "vaultId",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
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
            "description": "/customers/{customerid}/vaults/{vaultid}."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "e321b73f-4244-4fc6-b9c0-efb587de4c14"
            }
          ]
        },
        {
          "id": "048772dd-539b-49f4-b975-0cf787a84c57",
          "name": "CustomersVaultsByCustomerIdAndVaultIdDelete",
          "request": {
            "url": {
              "protocol": "http",
              "host": "example.com",
              "path": [
                "customers/:customerId/vaults/:vaultId"
              ],
              "variable": [
                {
                  "id": "customerId",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "vaultId",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "DELETE",
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
            "description": "/customers/{customerid}/vaults/{vaultid}."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "8f883262-9211-4dac-a9ba-7e06e95bb59c"
            }
          ]
        },
        {
          "id": "ff9ebec8-e4d4-4f46-ace2-ea4dcf500945",
          "name": "CustomersVaultsByCustomerIdPost2",
          "request": {
            "url": {
              "protocol": "http",
              "host": "example.com",
              "path": [
                "customers/:customerId/vaults"
              ],
              "variable": [
                {
                  "id": "customerId",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "POST",
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
              "mode": "urlencoded",
              "urlencoded": [
                {
                  "key": "address",
                  "value": "{}",
                  "disabled": false,
                  "description": ""
                },
                {
                  "key": "addressId",
                  "value": "{}",
                  "disabled": false,
                  "description": ""
                },
                {
                  "key": "cardExpMonth",
                  "value": "{}",
                  "disabled": false,
                  "description": "1-12"
                },
                {
                  "key": "cardExpYear",
                  "value": "{}",
                  "disabled": false,
                  "description": "YYYY, YY"
                },
                {
                  "key": "cardNumber",
                  "value": "{}",
                  "disabled": false,
                  "description": "5105105105105100,5105-1051-0510-5100,5105 1051 0510 5100"
                },
                {
                  "key": "city",
                  "value": "{}",
                  "disabled": false,
                  "description": ""
                },
                {
                  "key": "state",
                  "value": "{}",
                  "disabled": false,
                  "description": ""
                },
                {
                  "key": "zip",
                  "value": "{}",
                  "disabled": false,
                  "description": ""
                }
              ]
            },
            "description": "/customers/{customerid}/vaults (card)."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "9d139b9e-9e84-416c-967b-9bae26372229"
            }
          ]
        },
        {
          "id": "18ff3b47-d18a-4006-bcd5-cf5f22387102",
          "name": "CustomersVaultsByCustomerIdAndAchVaultPut",
          "request": {
            "url": {
              "protocol": "http",
              "host": "example.com",
              "path": [
                "customers/:customerId/vaults/:achVault"
              ],
              "variable": [
                {
                  "id": "achVault",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "customerId",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "PUT",
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
              "mode": "urlencoded",
              "urlencoded": [
                {
                  "key": "achAccountType",
                  "value": "{}",
                  "disabled": false,
                  "description": "CHECKING, SAVINGS"
                },
                {
                  "key": "achType",
                  "value": "{}",
                  "disabled": false,
                  "description": "CCD, PPD, TEL, WEB"
                },
                {
                  "key": "address",
                  "value": "{}",
                  "disabled": false,
                  "description": ""
                },
                {
                  "key": "addressId",
                  "value": "{}",
                  "disabled": false,
                  "description": ""
                },
                {
                  "key": "city",
                  "value": "{}",
                  "disabled": false,
                  "description": ""
                },
                {
                  "key": "state",
                  "value": "{}",
                  "disabled": false,
                  "description": ""
                },
                {
                  "key": "zip",
                  "value": "{}",
                  "disabled": false,
                  "description": ""
                }
              ]
            },
            "description": "/customers/{customerid}/vaults/{vaultid} (ach)."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "e8759c8b-9731-42df-9c1a-38c86009d4fd"
            }
          ]
        },
        {
          "id": "f4b1ad0e-6cb5-4334-a185-e19b5605742a",
          "name": "CustomersVaultsByCustomerIdAndCardVaultPut",
          "request": {
            "url": {
              "protocol": "http",
              "host": "example.com",
              "path": [
                "customers/:customerId/vaults/:cardVault"
              ],
              "variable": [
                {
                  "id": "cardVault",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "customerId",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "PUT",
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
              "mode": "urlencoded",
              "urlencoded": [
                {
                  "key": "address",
                  "value": "{}",
                  "disabled": false,
                  "description": ""
                },
                {
                  "key": "addressId",
                  "value": "{}",
                  "disabled": false,
                  "description": ""
                },
                {
                  "key": "cardExpMonth",
                  "value": "{}",
                  "disabled": false,
                  "description": "1-12"
                },
                {
                  "key": "cardExpYear",
                  "value": "{}",
                  "disabled": false,
                  "description": "YYYY, YY"
                },
                {
                  "key": "city",
                  "value": "{}",
                  "disabled": false,
                  "description": ""
                },
                {
                  "key": "state",
                  "value": "{}",
                  "disabled": false,
                  "description": ""
                },
                {
                  "key": "zip",
                  "value": "{}",
                  "disabled": false,
                  "description": ""
                }
              ]
            },
            "description": "/customers/{customerid}/vaults/{vaultid} (card)."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "8d43f495-d55a-40ef-9f62-233e9c8b80de"
            }
          ]
        },
        {
          "id": "be5f8b4f-a1be-4087-9574-229eef3f9453",
          "name": "CustomersAddressesByCustomerIdGet",
          "request": {
            "url": {
              "protocol": "http",
              "host": "example.com",
              "path": [
                "customers/:customerId/addresses"
              ],
              "variable": [
                {
                  "id": "customerId",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
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
            "description": "Gets a list of a customer's addresses."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "053f1113-f8f6-4d5d-b45c-e89f4d4fa0fd"
            }
          ]
        },
        {
          "id": "b4c12fe4-c4cb-42af-ba8c-1043a6737fb7",
          "name": "CustomersAddressesByCustomerIdPost",
          "request": {
            "url": {
              "protocol": "http",
              "host": "example.com",
              "path": [
                "customers/:customerId/addresses"
              ],
              "variable": [
                {
                  "id": "customerId",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "POST",
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
              "mode": "urlencoded",
              "urlencoded": [
                {
                  "key": "address",
                  "value": "{}",
                  "disabled": false,
                  "description": "Text, Max Length 128"
                },
                {
                  "key": "city",
                  "value": "{}",
                  "disabled": false,
                  "description": "Text, Max Length 32"
                },
                {
                  "key": "country",
                  "value": "{}",
                  "disabled": false,
                  "description": "Text, Max Length 32"
                },
                {
                  "key": "state",
                  "value": "{}",
                  "disabled": false,
                  "description": "Text, Max Length 32"
                },
                {
                  "key": "zip",
                  "value": "{}",
                  "disabled": false,
                  "description": "Text, Max Length 16"
                }
              ]
            },
            "description": "/customers/{customerid}/addresses/."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "fa445b47-72e5-4b6b-98cb-6fdd81c59713"
            }
          ]
        },
        {
          "id": "7db3eb3c-f625-49ca-981c-9539a0745041",
          "name": "CustomersAddressesByCustomerIdAndAddressIdGet",
          "request": {
            "url": {
              "protocol": "http",
              "host": "example.com",
              "path": [
                "customers/:customerId/addresses/:addressId"
              ],
              "variable": [
                {
                  "id": "addressId",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "customerId",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
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
            "description": "/customers/{customerid}/addresses/{addressid}."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "c6725775-b80a-4f93-9641-d33b37414883"
            }
          ]
        }
      ]
    }
  ]
}