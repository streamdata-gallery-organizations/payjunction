{
  "info": {
    "name": "PayJunction Get Smart Terminals",
    "_postman_id": "f6ca145c-a010-4bdb-9c25-b8619d85093e",
    "description": "Get a list of Smart Terminals for an account",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Customers",
      "item": [
        {
          "id": "25f68f65-8283-4d8e-a3b6-91e746cc33c8",
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
              "id": "492ea4bf-bfcb-40f7-ac2e-d8358182c7d8"
            }
          ]
        },
        {
          "id": "9c3ea122-67d2-4b24-aa01-7581e28e7788",
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
              "id": "26bdf4d3-43e0-4b3f-b3b1-d1a566dc4666"
            }
          ]
        },
        {
          "id": "313899b3-0f31-4ffa-91f1-d8315f7a5b6b",
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
              "id": "021be36f-4b5e-4cac-b86b-aacf7918bc48"
            }
          ]
        },
        {
          "id": "d587ee45-0d7c-4371-836a-0308405e7cc8",
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
              "id": "2f532f59-3e22-4cb4-a436-2feb0966260c"
            }
          ]
        },
        {
          "id": "9edc3fda-ea00-49a7-90c1-68a3c4b13455",
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
              "id": "890f6bec-1dfa-4028-9c91-096522d81df2"
            }
          ]
        },
        {
          "id": "b3736171-8381-414b-837b-f6685a491e51",
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
              "id": "e6975588-38fd-41d0-9297-91e763ea9382"
            }
          ]
        },
        {
          "id": "6a992304-cb50-4d3e-af41-55783c63a2b7",
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
              "id": "83763105-81e2-4c2f-81bd-cf78f6bfcbb0"
            }
          ]
        },
        {
          "id": "ae2b2beb-3bcd-4496-bc49-6a083ce97143",
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
              "id": "64c87a40-959f-40cc-96d3-9c5e7be73e5f"
            }
          ]
        },
        {
          "id": "ee1176a0-1840-40d2-8e1b-f83daff37686",
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
              "id": "05900de4-fc3a-4d68-a737-035265147f53"
            }
          ]
        },
        {
          "id": "3ea5a6c4-1fa9-4fd9-8121-d4c8eabfd0bd",
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
              "id": "477153df-00b0-43cc-8541-d85a54842822"
            }
          ]
        },
        {
          "id": "a1a0949a-f8f0-451d-88fa-cf59b9bc128b",
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
              "id": "5e302aef-becf-407e-b815-59a8c15c60ed"
            }
          ]
        },
        {
          "id": "19a64534-4f4a-463f-92e8-b0253a67e9f9",
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
              "id": "a3b61153-86af-4dfa-85f6-d782afd4ceea"
            }
          ]
        },
        {
          "id": "02ec16cb-2697-452d-aabb-294c30aa1253",
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
              "id": "4a7089f8-4bdd-49c6-bf5f-4b4330d4b6f7"
            }
          ]
        },
        {
          "id": "23913c38-b154-468c-bda5-935c09d0736e",
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
              "id": "847abb0c-55d9-44b1-8c18-15609b3f0506"
            }
          ]
        },
        {
          "id": "d9878f65-6923-4fa1-9011-31f54e7ccd1f",
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
              "id": "d96bc733-277a-4d71-9c3d-bd08fbdc68af"
            }
          ]
        },
        {
          "id": "39a85de0-6456-4f03-acbf-9a53331f8df9",
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
              "id": "c1955754-4066-4ed8-b85b-f608a68ee992"
            }
          ]
        },
        {
          "id": "32a25f06-830a-4f37-971e-adda9ee18c70",
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
              "id": "f68804e7-f904-43e0-8bd3-e8f83926a90d"
            }
          ]
        },
        {
          "id": "62068c03-71a8-486c-9cb3-968708f2a797",
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
              "id": "a10f59a4-a702-4f20-b153-481fea547be8"
            }
          ]
        },
        {
          "id": "cc565e7b-38b4-47ca-99d5-169a76908963",
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
              "id": "674d2c8a-8159-4a1c-9de8-df1a1cd2f850"
            }
          ]
        },
        {
          "id": "1ee40135-406e-429b-9923-73e8814e2513",
          "name": "CustomersAddressesByCustomerIdAndAddressIdPut",
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
                  "key": "city",
                  "value": "{}",
                  "disabled": false,
                  "description": ""
                },
                {
                  "key": "country",
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
            "description": "/customers/{customerid}/addresses/{addressid}."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "1d0ba6dd-f80e-4536-8765-3e54ee895896"
            }
          ]
        },
        {
          "id": "dcc64d52-4fc1-4da6-a17c-d87f02a2d9be",
          "name": "CustomersAddressesByCustomerIdAndAddressIdDelete",
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
            "method": "DELETE",
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
              "mode": "raw"
            },
            "description": "/customers/{customerid}/addresses/{addressid}."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "2979c5c8-308f-4e7c-bde2-cd7d3c550dc9"
            }
          ]
        }
      ]
    },
    {
      "name": "Transactions",
      "item": [
        {
          "id": "ff20caea-bc23-48dd-b517-cd9931ae429e",
          "name": "TransactionsPost6",
          "request": {
            "url": "http://example.com/transactions",
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
                  "key": "action",
                  "value": "{}",
                  "disabled": false,
                  "description": ""
                },
                {
                  "key": "amountBase",
                  "value": "{}",
                  "disabled": false,
                  "description": ""
                },
                {
                  "key": "billingCompanyName",
                  "value": "{}",
                  "disabled": false,
                  "description": ""
                },
                {
                  "key": "billingFirstName",
                  "value": "{}",
                  "disabled": false,
                  "description": ""
                },
                {
                  "key": "billingLastName",
                  "value": "{}",
                  "disabled": false,
                  "description": ""
                },
                {
                  "key": "cardTrack",
                  "value": "{}",
                  "disabled": false,
                  "description": ""
                }
              ]
            },
            "description": "/transactions/ (swiped cc)."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "15afe58d-4b74-450b-8007-a38ed6b77880"
            }
          ]
        },
        {
          "id": "ec1b9697-8a7e-490f-9cfd-cb29150b19b8",
          "name": "TransactionsGet",
          "request": {
            "url": "http://example.com/transactions/?limit=%7B%7D&offset=%7B%7D",
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
            "description": "Not Available At Time at Time of Publishing this collection: Get a list of transactions"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "7421a94b-58c8-495f-b698-b58c9510a1d7"
            }
          ]
        },
        {
          "id": "5aab4037-35e4-424b-afe3-45414b6bf1e1",
          "name": "TransactionsByTransactionIdGet",
          "request": {
            "url": {
              "protocol": "http",
              "host": "example.com",
              "path": [
                "transactions/:transactionId"
              ],
              "variable": [
                {
                  "id": "transactionId",
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
            "description": "/transactions/{transactionid}."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f4f36c65-8024-4198-af06-3f22b2ec2484"
            }
          ]
        },
        {
          "id": "8901cccf-2e97-4d55-a53b-37c2dac19245",
          "name": "TransactionsByTransactionIdPut",
          "request": {
            "url": {
              "protocol": "http",
              "host": "example.com",
              "path": [
                "transactions/:transactionId"
              ],
              "variable": [
                {
                  "id": "transactionId",
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
                  "key": "amountBase",
                  "value": "{}",
                  "disabled": false,
                  "description": ""
                },
                {
                  "key": "amountReject",
                  "value": "{}",
                  "disabled": false,
                  "description": ""
                },
                {
                  "key": "amountShipping",
                  "value": "{}",
                  "disabled": false,
                  "description": ""
                },
                {
                  "key": "amountTax",
                  "value": "{}",
                  "disabled": false,
                  "description": ""
                },
                {
                  "key": "amountTip",
                  "value": "{}",
                  "disabled": false,
                  "description": ""
                },
                {
                  "key": "status",
                  "value": "{}",
                  "disabled": false,
                  "description": ""
                }
              ]
            },
            "description": "Update an unsettled transaction"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "e16c4ea5-2dd4-4310-ba58-9db987f7fa1c"
            }
          ]
        },
        {
          "id": "a6f27da9-c290-4e41-bcd0-b7109c695c12",
          "name": "TransactionsNotesByTransactionIdGet",
          "request": {
            "url": {
              "protocol": "http",
              "host": "example.com",
              "path": [
                "transactions/:transactionId/notes"
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
                  "id": "transactionId",
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
            "description": "Get a list of notes for a transaction"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "140dbe3b-c174-4ab3-8035-2a3d00211fc5"
            }
          ]
        },
        {
          "id": "7023f860-f3aa-4e36-9244-a035569f3366",
          "name": "TransactionsNotesByTransactionIdPost",
          "request": {
            "url": {
              "protocol": "http",
              "host": "example.com",
              "path": [
                "transactions/:transactionId/notes"
              ],
              "variable": [
                {
                  "id": "transactionId",
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
                  "description": ""
                }
              ]
            },
            "description": "/transactions/{transactionid}/notes/."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "73b54c82-a9fb-4d54-84da-f85b2bdadeac"
            }
          ]
        },
        {
          "id": "55f8feac-2285-4fd4-8380-b45d095e9ef5",
          "name": "TransactionsNotesByTransactionIdAndNoteIdGet",
          "request": {
            "url": {
              "protocol": "http",
              "host": "example.com",
              "path": [
                "transactions/:transactionId/notes/:noteId"
              ],
              "variable": [
                {
                  "id": "noteId",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "transactionId",
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
            "description": "/transactions/{transactionid}/notes/{noteid}."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "85c9e950-79ff-4da0-aa10-1c6c554aa482"
            }
          ]
        },
        {
          "id": "bf88bdb7-a6c2-4496-8a6c-77f17548f2e0",
          "name": "TransactionsNotesByTransactionIdAndNoteIdPut",
          "request": {
            "url": {
              "protocol": "http",
              "host": "example.com",
              "path": [
                "transactions/:transactionId/notes/:noteId"
              ],
              "variable": [
                {
                  "id": "noteId",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "transactionId",
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
                  "key": "note",
                  "value": "{}",
                  "disabled": false,
                  "description": ""
                }
              ]
            },
            "description": "/transactions/{transactionid}/notes/{noteid}."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "df460604-bec1-4e1a-a324-2f6036f99884"
            }
          ]
        },
        {
          "id": "71e20f3b-e4c0-43bb-9168-25f242f459be",
          "name": "TransactionsNotesByTransactionIdAndNoteIdDelete",
          "request": {
            "url": {
              "protocol": "http",
              "host": "example.com",
              "path": [
                "transactions/:transactionId/notes/:noteId"
              ],
              "variable": [
                {
                  "id": "noteId",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "transactionId",
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
            "description": "/transactions/{transactionid}/notes/{noteid}."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "3a5ed3b9-da50-4bec-a8b2-e3ca3a9c5f48"
            }
          ]
        },
        {
          "id": "65099902-012d-480a-b84d-8e1b2c13d379",
          "name": "TransactionsSignatureCaptureByTransactionIdPost",
          "request": {
            "url": {
              "protocol": "http",
              "host": "example.com",
              "path": [
                "transactions/:transactionId/signature/capture"
              ],
              "variable": [
                {
                  "id": "transactionId",
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
                  "key": "signature",
                  "value": "{}",
                  "disabled": false,
                  "description": ""
                }
              ]
            },
            "description": "Capture a signature using the scriptel signature capture"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "aeaa3e3b-ce2a-4c8b-93cb-06406e48883a"
            }
          ]
        },
        {
          "id": "dee4f9a3-8bb7-4c54-ad2f-19e4cba5f292",
          "name": "TransactionsReceiptsLatestEmailByTransactionIdPost",
          "request": {
            "url": {
              "protocol": "http",
              "host": "example.com",
              "path": [
                "transactions/:transactionId/receipts/latest/email"
              ],
              "variable": [
                {
                  "id": "transactionId",
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
                  "key": "replyTo",
                  "value": "{}",
                  "disabled": false,
                  "description": ""
                },
                {
                  "key": "requestSignature",
                  "value": "{}",
                  "disabled": false,
                  "description": ""
                },
                {
                  "key": "to",
                  "value": "{}",
                  "disabled": false,
                  "description": ""
                }
              ]
            },
            "description": "/transactions/{transactionid}/receipts/latest/email."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "76217888-7031-4191-936f-33f2170d54c7"
            }
          ]
        },
        {
          "id": "012abdeb-64dd-488f-bffd-0d4dbc5182c4",
          "name": "TransactionsReceiptsByTransactionIdGet",
          "request": {
            "url": {
              "protocol": "http",
              "host": "example.com",
              "path": [
                "transactions/:transactionId/receipts"
              ],
              "variable": [
                {
                  "id": "transactionId",
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
            "description": "Get all of the signed receipts for a transaction."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "0dc43944-23e1-44de-b437-9e8fc06f3c3c"
            }
          ]
        },
        {
          "id": "ffd50b8b-6f4a-444b-848d-8f2fe0191972",
          "name": "TransactionsReceiptsLatestByTransactionIdGet",
          "request": {
            "url": {
              "protocol": "http",
              "host": "example.com",
              "path": [
                "transactions/:transactionId/receipts/latest"
              ],
              "variable": [
                {
                  "id": "transactionId",
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
            "description": "Retrieve the most recent version of the receipt."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "d8d302cf-984c-40dc-9904-7a3400d7b30d"
            }
          ]
        },
        {
          "id": "79c97036-3887-45ca-abce-f2afbe43c12e",
          "name": "TransactionsReceiptsLatestThermalByTransactionIdGet",
          "request": {
            "url": {
              "protocol": "http",
              "host": "example.com",
              "path": [
                "transactions/:transactionId/receipts/latest/thermal"
              ],
              "variable": [
                {
                  "id": "transactionId",
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
            "description": "Get the most recent version of the thermal receipt HTML Document"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "9d0fb0d9-2348-4712-a136-56065c2c6127"
            }
          ]
        },
        {
          "id": "a2104cc4-0a14-442c-b6ea-984400581812",
          "name": "TransactionsReceiptsLatestFullpageByTransactionIdGet",
          "request": {
            "url": {
              "protocol": "http",
              "host": "example.com",
              "path": [
                "transactions/:transactionId/receipts/latest/fullpage"
              ],
              "variable": [
                {
                  "id": "transactionId",
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
            "description": "Get the most recent version of the full page (8.5x11) receipt HTML document"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "3da96bf6-1031-4372-b7c1-aa3b801946c4"
            }
          ]
        },
        {
          "id": "fd2ec68b-1d8b-4c9c-a77c-162046ec8adb",
          "name": "TransactionsReceiptsUnsignedByTransactionIdGet",
          "request": {
            "url": {
              "protocol": "http",
              "host": "example.com",
              "path": [
                "transactions/:transactionId/receipts/unsigned"
              ],
              "variable": [
                {
                  "id": "transactionId",
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
            "description": "/transactions/{transactionid}/receipts/unsigned."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "2c9fd744-9b5c-407a-b00e-633906369ba1"
            }
          ]
        },
        {
          "id": "5f4220ca-0161-4188-b5ab-d23a449a8145",
          "name": "TransactionsReceiptsUnsignedThermalByTransactionIdGet",
          "request": {
            "url": {
              "protocol": "http",
              "host": "example.com",
              "path": [
                "transactions/:transactionId/receipts/unsigned/thermal"
              ],
              "variable": [
                {
                  "id": "transactionId",
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
            "description": "/transactions/{transactionid}/receipts/unsigned/thermal."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "1cae25d9-9abd-4236-8cda-7c2928635b6e"
            }
          ]
        },
        {
          "id": "430af2cf-267e-4a65-bc85-5a398d9c0d7c",
          "name": "TransactionsReceiptsUnsignedFullpageByTransactionIdGet",
          "request": {
            "url": {
              "protocol": "http",
              "host": "example.com",
              "path": [
                "transactions/:transactionId/receipts/unsigned/fullpage"
              ],
              "variable": [
                {
                  "id": "transactionId",
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
            "description": "/transactions/{transactionid}/receipts/unsigned/fullpage."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "d531c5b0-14ba-4ce1-bb46-8ecf6696246b"
            }
          ]
        },
        {
          "id": "f2ed3df5-1cda-48c8-ac12-7a0d26d5c974",
          "name": "TransactionsReceiptByTransactionIdAndReceiptIdGet",
          "request": {
            "url": {
              "protocol": "http",
              "host": "example.com",
              "path": [
                "transactions/:transactionId/receipt/:receiptId"
              ],
              "variable": [
                {
                  "id": "receiptId",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "transactionId",
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
            "description": "/transactions/{transactionid}/receipts/{receiptid}."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "e642c20d-b5b5-4f35-9600-47d37e2c3c69"
            }
          ]
        }
      ]
    },
    {
      "name": "Webhooks",
      "item": [
        {
          "id": "12311a2c-01af-422f-a37a-618af6a4c50b",
          "name": "WebhooksGet",
          "request": {
            "url": "http://example.com/webhooks",
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
            "description": "Gets a list of webhooks"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "8c65ef5f-0ab9-4b30-98f8-25bd46d0efd9"
            }
          ]
        },
        {
          "id": "ccf7df0e-c84c-4859-86d5-299c34854715",
          "name": "WebhooksPost",
          "request": {
            "url": "http://example.com/webhooks?event=%7B%7D",
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
                  "key": "secret",
                  "value": "{}",
                  "disabled": false,
                  "description": "Text, max length 255"
                },
                {
                  "key": "url",
                  "value": "{}",
                  "disabled": false,
                  "description": "Text, URL with max length 255"
                }
              ]
            },
            "description": "/webhooks/{webhooks}."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f2c800e5-135e-4ed0-a162-1846b2a6870a"
            }
          ]
        },
        {
          "id": "d0a66fe9-3a2e-469f-a2f9-8b5b34503595",
          "name": "WebhooksByWebhookIdPut",
          "request": {
            "url": {
              "protocol": "http",
              "host": "example.com",
              "path": [
                "webhooks/:webhookId"
              ],
              "variable": [
                {
                  "id": "webhookId",
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
                  "key": "secret",
                  "value": "{}",
                  "disabled": false,
                  "description": "Text, max length 255"
                },
                {
                  "key": "url",
                  "value": "{}",
                  "disabled": false,
                  "description": "Text, URL with max length 255"
                }
              ]
            },
            "description": "/webhooks/{webhookid}."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "c2edf705-daf4-4697-9cb3-f914ecb3945a"
            }
          ]
        },
        {
          "id": "e8e8bcea-e147-47e4-b6f4-6653538748d0",
          "name": "WebhooksByWebhookIdDelete",
          "request": {
            "url": {
              "protocol": "http",
              "host": "example.com",
              "path": [
                "webhooks/:webhookId"
              ],
              "variable": [
                {
                  "id": "webhookId",
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
            "description": "/webhooks/{webhookid}."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "081a556c-4813-41c4-b8b5-2ee1d5232fe6"
            }
          ]
        }
      ]
    },
    {
      "name": "Terminals",
      "item": [
        {
          "id": "eb23fb47-f901-4783-bf43-d14e2570ce12",
          "name": "TerminalsGet",
          "request": {
            "url": "http://example.com/terminals",
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
            "description": "Get a list of Terminal Id's for an account."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "b8f42ab8-cc54-46f9-b905-9cc5b032d59d"
            }
          ]
        }
      ]
    },
    {
      "name": "Smart",
      "item": [
        {
          "id": "951a6242-a30a-4480-abb3-786341b6066b",
          "name": "SmartterminalsRequestPaymentBySmartTerminaIIdPost",
          "request": {
            "url": {
              "protocol": "http",
              "host": "example.com",
              "path": [
                "smartterminals/:smartTerminaIId/request-payment"
              ],
              "query": [
                {
                  "key": "amountBase",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "terminalId",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "smartTerminaIId",
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
                  "key": "invoiceNumber",
                  "value": "{}",
                  "disabled": false,
                  "description": "NumericAn invoice number to include in the transaction details"
                },
                {
                  "key": "showReceiptPrompt",
                  "value": "{}",
                  "disabled": false,
                  "description": "true | falsetrue - Displays the receipt prompt"
                }
              ]
            },
            "description": "/smartterminals/{smartterminald}/request-payment."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "c6bf3f4d-f60a-4530-895d-b0d365291595"
            }
          ]
        },
        {
          "id": "6e060e36-2849-40aa-872a-b89f409feda9",
          "name": "SmartterminalsMainBySmartTerminaIIdPost",
          "request": {
            "url": {
              "protocol": "http",
              "host": "example.com",
              "path": [
                "smartterminals/:smartTerminaIId/main"
              ],
              "variable": [
                {
                  "id": "smartTerminaIId",
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
              "mode": "raw"
            },
            "description": "Returns the Smart Terminal to the main \"Smart Terminal by PayJunction\" screen to await a new transaction request. \n\nFor instance, this request can be used when a user decides to cancel a Smart Terminal payment request. When this request is sent, the Smart Terminal will return to the main screen that reads \"Smart Terminal by PayJunction\", preventing the customer from making a payment.\n\nNote: If the customer has already inserted the chip card, or swiped the card, then the transaction is already processed and it is too late to cancel the payment request. In this case, the transaction should be voided instead."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "9e8b8b6d-bd0b-4a2a-ab8e-2a5812d5c8ea"
            }
          ]
        },
        {
          "id": "14822333-8c5e-4bab-84d7-b34744294602",
          "name": "SmartterminalsGet",
          "request": {
            "url": "http://example.com/smartterminals",
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
            "description": "Get a list of Smart Terminals for an account"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "2122473f-d558-4f20-bd62-6a68d6508a3e"
            }
          ]
        }
      ]
    }
  ]
}