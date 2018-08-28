{
  "info": {
    "name": "AWS Service Catalog API List Portfolios For Product",
    "_postman_id": "afaf1fd8-64eb-4eb2-94ba-ea9454881171",
    "description": "Lists all portfolios that the specified product is associated with.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Portfolios",
      "item": [
        {
          "id": "901719bb-14d4-4655-979c-f13220103237",
          "name": "acceptPortfolioShare",
          "request": {
            "url": "http://example.com/api/?Action=AcceptPortfolioShare?AcceptLanguage=AcceptLanguage&PortfolioId=PortfolioId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Accepts an offer to share a portfolio."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "51f8cc38-f7f9-491e-8fa3-31e40db51a63"
            }
          ]
        },
        {
          "id": "617ffd8e-97d5-47e2-b681-44df8b199a21",
          "name": "associatePrincipalWithPortfolio",
          "request": {
            "url": "http://example.com/api/?Action=AssociatePrincipalWithPortfolio?AcceptLanguage=AcceptLanguage&PortfolioId=PortfolioId&PrincipalARN=PrincipalARN&PrincipalType=PrincipalType",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Associates the specified principal ARN with the specified portfolio."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "e869ef7c-2257-4d11-bc4d-e91f6df0d309"
            }
          ]
        },
        {
          "id": "8557dbc9-515c-41cd-bd88-0799793f538f",
          "name": "associateProductWithPortfolio",
          "request": {
            "url": "http://example.com/api/?Action=AssociateProductWithPortfolio?AcceptLanguage=AcceptLanguage&PortfolioId=PortfolioId&ProductId=ProductId&SourcePortfolioId=SourcePortfolioId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Associates a product with a portfolio."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "c0948edc-cb14-4ca6-85d8-3031ebfea499"
            }
          ]
        },
        {
          "id": "10b40010-5851-4614-9530-c7dc27760b64",
          "name": "createPortfolio",
          "request": {
            "url": "http://example.com/api/?Action=CreatePortfolio?AcceptLanguage=AcceptLanguage&Description=Description&DisplayName=DisplayName&IdempotencyToken=IdempotencyToken&ProviderName=ProviderName&Tags=Tags",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Creates a new portfolio."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "925d466d-5d8f-427c-888d-df1cddc93535"
            }
          ]
        },
        {
          "id": "b820257c-94ee-47f0-882e-58301c3ebaf4",
          "name": "createPortfolioShare",
          "request": {
            "url": "http://example.com/api/?Action=CreatePortfolioShare?AcceptLanguage=AcceptLanguage&AccountId=AccountId&PortfolioId=PortfolioId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Creates a new portfolio share."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "ceb5f7ff-d652-45d8-857e-7cee0f2786ee"
            }
          ]
        },
        {
          "id": "8e1182c8-a012-433c-b98c-9442ed93ff3e",
          "name": "deletePortfolio",
          "request": {
            "url": "http://example.com/api/?Action=DeletePortfolio?AcceptLanguage=AcceptLanguage&Id=Id",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes the specified portfolio."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "ccf40577-8c3d-4008-8b3e-a327785d365d"
            }
          ]
        },
        {
          "id": "43f89f2b-9904-448a-b4cc-297b61edf0f7",
          "name": "deletePortfolioShare",
          "request": {
            "url": "http://example.com/api/?Action=DeletePortfolioShare?AcceptLanguage=AcceptLanguage&AccountId=AccountId&PortfolioId=PortfolioId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes the specified portfolio share."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "2790f15f-b79f-48c4-94bc-7d7ee395fbba"
            }
          ]
        },
        {
          "id": "2e6b5a09-210b-40b6-9775-20c8bb9db279",
          "name": "describePortfolio",
          "request": {
            "url": "http://example.com/api/?Action=DescribePortfolio?AcceptLanguage=AcceptLanguage&Id=Id",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Retrieves detailed information and any tags associated with the specified\n         portfolio."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "fee232ef-19ba-49d2-8cb6-2e6d49122bda"
            }
          ]
        },
        {
          "id": "9dd9b3f5-a3e2-414f-a8da-534221c7b202",
          "name": "disassociatePrincipalFromPortfolio",
          "request": {
            "url": "http://example.com/api/?Action=DisassociatePrincipalFromPortfolio?AcceptLanguage=AcceptLanguage&PortfolioId=PortfolioId&PrincipalARN=PrincipalARN",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Disassociates a previously associated principal ARN from a specified\n         portfolio."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "2f487eae-c586-48aa-af99-43486582c44f"
            }
          ]
        },
        {
          "id": "06d3c3cd-0309-45ce-8a15-d7925288952a",
          "name": "disassociateProductFromPortfolio",
          "request": {
            "url": "http://example.com/api/?Action=DisassociateProductFromPortfolio?AcceptLanguage=AcceptLanguage&PortfolioId=PortfolioId&ProductId=ProductId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Disassociates the specified product from the specified portfolio."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "ebca036f-59b7-433c-825a-7ad24d26145f"
            }
          ]
        },
        {
          "id": "5bbde450-d490-4efd-a87b-72fabecf823e",
          "name": "listAcceptedPortfolioShares",
          "request": {
            "url": "http://example.com/api/?Action=ListAcceptedPortfolioShares?AcceptLanguage=AcceptLanguage&PageSize=PageSize&PageToken=PageToken",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Lists details of all portfolios for which sharing was accepted by this\n         account."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "2e66c03d-1e8d-43f9-9b8a-6d4968e160f1"
            }
          ]
        },
        {
          "id": "834eb2ac-155b-448b-9b0e-c4f771634d81",
          "name": "listConstraintsForPortfolio",
          "request": {
            "url": "http://example.com/api/?Action=ListConstraintsForPortfolio?AcceptLanguage=AcceptLanguage&PageSize=PageSize&PageToken=PageToken&PortfolioId=PortfolioId&ProductId=ProductId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Retrieves detailed constraint information for the specified portfolio and\n         product."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "84e4af8d-e399-4b54-af89-bf89330ba7bc"
            }
          ]
        },
        {
          "id": "08d65178-1092-4f8c-9a30-502bddcdd165",
          "name": "listPortfolioAccess",
          "request": {
            "url": "http://example.com/api/?Action=ListPortfolioAccess?AcceptLanguage=AcceptLanguage&PortfolioId=PortfolioId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Lists the account IDs that have been authorized sharing of the specified\n         portfolio."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "8e86ef89-a552-4f4f-b96c-e86d7fe71e8a"
            }
          ]
        },
        {
          "id": "941c264f-2729-46b6-88f5-ea9d02245b2f",
          "name": "listPortfolios",
          "request": {
            "url": "http://example.com/api/?Action=ListPortfolios?AcceptLanguage=AcceptLanguage&PageSize=PageSize&PageToken=PageToken",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Lists all portfolios in the catalog."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "1858e541-c26c-4265-97cf-36143c12ed64"
            }
          ]
        },
        {
          "id": "4a8803f6-6bbc-48eb-8417-20f5ede13b98",
          "name": "listPortfoliosForProduct",
          "request": {
            "url": "http://example.com/api/?Action=ListPortfoliosForProduct?AcceptLanguage=AcceptLanguage&PageSize=PageSize&PageToken=PageToken&ProductId=ProductId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Lists all portfolios that the specified product is associated with."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "0623da94-4582-4590-b724-a7cc291cf87e"
            }
          ]
        }
      ]
    },
    {
      "name": "Constraints",
      "item": [
        {
          "id": "53ed12c3-48bd-48f8-9d0f-4411b3066c67",
          "name": "createConstraint",
          "request": {
            "url": "http://example.com/api/?Action=CreateConstraint?AcceptLanguage=AcceptLanguage&Description=Description&IdempotencyToken=IdempotencyToken&Parameters=Parameters&PortfolioId=PortfolioId&ProductId=ProductId&Type=Type",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Creates a new constraint."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f4d5804d-d236-47b7-8c66-b88276949505"
            }
          ]
        },
        {
          "id": "1227e6d4-c10b-41f9-a0ca-e8d854398444",
          "name": "deleteConstraint",
          "request": {
            "url": "http://example.com/api/?Action=DeleteConstraint?AcceptLanguage=AcceptLanguage&Id=Id",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes the specified constraint."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "d68ef6f8-1635-40c6-942d-4ab7710288e1"
            }
          ]
        },
        {
          "id": "3c30e667-3663-4e51-8387-7cf3a9b18a38",
          "name": "describeConstraint",
          "request": {
            "url": "http://example.com/api/?Action=DescribeConstraint?AcceptLanguage=AcceptLanguage&Id=Id",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Retrieves detailed information for a specified constraint."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "1865747a-7276-4d51-aa99-124eef2a35b6"
            }
          ]
        }
      ]
    },
    {
      "name": "Products",
      "item": [
        {
          "id": "66a692d4-52a7-419f-8f9a-23f506aedc66",
          "name": "createProduct",
          "request": {
            "url": "http://example.com/api/?Action=CreateProduct?AcceptLanguage=AcceptLanguage&Description=Description&Distributor=Distributor&IdempotencyToken=IdempotencyToken&Name=Name&Owner=Owner&ProductType=ProductType&ProvisioningArtifactParameters=ProvisioningArtifactParameters&SupportDescription=SupportDescription&SupportEmail=SupportEmail&SupportUrl=SupportUrl&Tags=Tags",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Creates a new product."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "c64930b6-f838-4ecb-8807-b13ff05c6015"
            }
          ]
        },
        {
          "id": "9dc83545-4dd3-4685-b3f1-a2d4f34771d5",
          "name": "deleteProduct",
          "request": {
            "url": "http://example.com/api/?Action=DeleteProduct?AcceptLanguage=AcceptLanguage&Id=Id",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes the specified product."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "137c0126-00d8-4ec8-9ec8-8dfdb3536d95"
            }
          ]
        },
        {
          "id": "7bc253f2-084b-4af5-a1ce-1a320771ce21",
          "name": "describeProduct",
          "request": {
            "url": "http://example.com/api/?Action=DescribeProduct?AcceptLanguage=AcceptLanguage&Id=Id",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Retrieves information about a specified product."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "0a6d0170-b30a-4eb9-99d1-19071d9da9d6"
            }
          ]
        },
        {
          "id": "0a2429a3-ad6f-4f3f-9436-9478d0906658",
          "name": "describeProductAsAdmin",
          "request": {
            "url": "http://example.com/api/?Action=DescribeProductAsAdmin?AcceptLanguage=AcceptLanguage&Id=Id",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Retrieves information about a specified product, run with administrator\n         access."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f0cd8e74-32fd-4e5e-9acb-d7a5a2537770"
            }
          ]
        },
        {
          "id": "c646dae0-5fae-4fbb-b6b9-e467321856bb",
          "name": "describeProductView",
          "request": {
            "url": "http://example.com/api/?Action=DescribeProductView?AcceptLanguage=AcceptLanguage&Id=Id",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Retrieves information about a specified product."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "170b0078-8edf-41fe-b14c-42a9a2f56e28"
            }
          ]
        }
      ]
    },
    {
      "name": "Provisioning Artifacts",
      "item": [
        {
          "id": "efae3277-9e6b-4332-bb76-3897da216345",
          "name": "createProvisioningArtifact",
          "request": {
            "url": "http://example.com/api/?Action=CreateProvisioningArtifact?AcceptLanguage=AcceptLanguage&IdempotencyToken=IdempotencyToken&Parameters=Parameters&ProductId=ProductId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Create a new provisioning artifact for the specified product."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "c47c0018-c12b-4496-8632-e43e288b20eb"
            }
          ]
        },
        {
          "id": "77cf3b7d-aa94-4a78-b2e9-836d939517bd",
          "name": "deleteProvisioningArtifact",
          "request": {
            "url": "http://example.com/api/?Action=DeleteProvisioningArtifact?AcceptLanguage=AcceptLanguage&ProductId=ProductId&ProvisioningArtifactId=ProvisioningArtifactId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes the specified provisioning artifact."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "92e40367-651b-4046-972a-402a7439e53c"
            }
          ]
        },
        {
          "id": "3b0e6c79-1df3-4dce-90ac-643d8a222d8d",
          "name": "describeProvisioningArtifact",
          "request": {
            "url": "http://example.com/api/?Action=DescribeProvisioningArtifact?AcceptLanguage=AcceptLanguage&ProductId=ProductId&ProvisioningArtifactId=ProvisioningArtifactId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Retrieves detailed information about the specified provisioning artifact."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "ce21c04b-00dd-4109-8032-6adf5e2f73dd"
            }
          ]
        }
      ]
    },
    {
      "name": "Provisioning Parameters",
      "item": [
        {
          "id": "57c9d5ff-b776-40b0-9930-47c14c2cf005",
          "name": "describeProvisioningParameters",
          "request": {
            "url": "http://example.com/api/?Action=DescribeProvisioningParameters?AcceptLanguage=AcceptLanguage&PathId=PathId&ProductId=ProductId&ProvisioningArtifactId=ProvisioningArtifactId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Provides information about parameters required to provision a specified product in a\n         specified manner."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "58676bd5-72de-4650-aeca-c5df169f5358"
            }
          ]
        }
      ]
    },
    {
      "name": "Records",
      "item": [
        {
          "id": "ec687639-18f6-458a-8e84-63c7c970aabe",
          "name": "describeRecord",
          "request": {
            "url": "http://example.com/api/?Action=DescribeRecord?AcceptLanguage=AcceptLanguage&Id=Id&PageSize=PageSize&PageToken=PageToken",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Retrieves a paginated list of the full details of a specific request."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "28ecd622-74c1-450f-904c-f6b44bd92808"
            }
          ]
        }
      ]
    },
    {
      "name": "Launch Paths",
      "item": [
        {
          "id": "32854b60-5944-4321-b995-498b74f052dd",
          "name": "listLaunchPaths",
          "request": {
            "url": "http://example.com/api/?Action=ListLaunchPaths?AcceptLanguage=AcceptLanguage&PageSize=PageSize&PageToken=PageToken&ProductId=ProductId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns a paginated list of all paths to a specified product."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "30f2da06-3494-4a1c-9c99-576ea9f998d1"
            }
          ]
        }
      ]
    }
  ]
}