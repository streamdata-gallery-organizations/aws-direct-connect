{
  "info": {
    "name": "AWS Direct Connect API Delete Interconnect",
    "_postman_id": "331b6986-a1d6-4cc9-b392-e557c465486b",
    "description": "Deletes the specified interconnect.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Connections",
      "item": [
        {
          "id": "6fe8acd2-5bf5-428c-aedf-908b64d9c9f8",
          "name": "allocateConnectionOnInterconnect",
          "request": {
            "url": "http://example.com/api/?Action=AllocateConnectionOnInterconnect?bandwidth=bandwidth&connectionName=connectionName&interconnectId=interconnectId&ownerAccount=ownerAccount&vlan=vlan",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Creates a hosted connection on an interconnect."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "c194b557-ad45-492e-9143-4bbd9d44eaba"
            }
          ]
        },
        {
          "id": "648a7b35-6da0-4fd7-8e2a-2f3e82b662aa",
          "name": "confirmConnection",
          "request": {
            "url": "http://example.com/api/?Action=ConfirmConnection?connectionId=connectionId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Confirm the creation of a hosted connection on an interconnect."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "243fa9fb-370f-4ce4-8f1d-5e4e5cbea144"
            }
          ]
        },
        {
          "id": "c20d36b7-fe44-45cc-82cd-c4de07b9b69b",
          "name": "createConnection",
          "request": {
            "url": "http://example.com/api/?Action=CreateConnection?bandwidth=bandwidth&connectionName=connectionName&location=location",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Creates a new connection between the customer network and a specific AWS Direct Connect location."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "c9757f91-a339-43c4-8424-0be5118e5984"
            }
          ]
        },
        {
          "id": "3d155bf3-2ebf-482f-b720-76ee1e9295ad",
          "name": "deleteConnection",
          "request": {
            "url": "http://example.com/api/?Action=DeleteConnection?connectionId=connectionId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes the connection."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "91c1697a-7acc-4427-8638-6750e8588ec3"
            }
          ]
        }
      ]
    },
    {
      "name": "Private Virtual Interfaces",
      "item": [
        {
          "id": "99c8b690-73f2-4c93-804a-8deef03bf8e7",
          "name": "allocatePrivateVirtualInterface",
          "request": {
            "url": "http://example.com/api/?Action=AllocatePrivateVirtualInterface?connectionId=connectionId&newPrivateVirtualInterfaceAllocation=newPrivateVirtualInterfaceAllocation&ownerAccount=ownerAccount",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Provisions a private virtual interface to be owned by a different customer."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "d3f9982b-558a-49b3-b104-34af27739797"
            }
          ]
        },
        {
          "id": "1313f53e-436f-4d77-a50d-f5c3a72d9afd",
          "name": "allocatePublicVirtualInterface",
          "request": {
            "url": "http://example.com/api/?Action=AllocatePublicVirtualInterface?connectionId=connectionId&newPublicVirtualInterfaceAllocation=newPublicVirtualInterfaceAllocation&ownerAccount=ownerAccount",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Provisions a public virtual interface to be owned by a different customer."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "d8b80176-9a3a-4682-9587-04e4cda2ddd6"
            }
          ]
        },
        {
          "id": "f357b34e-7055-49e2-80db-5a95f5f39b8a",
          "name": "confirmPrivateVirtualInterface",
          "request": {
            "url": "http://example.com/api/?Action=ConfirmPrivateVirtualInterface?virtualGatewayId=virtualGatewayId&virtualInterfaceId=virtualInterfaceId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Accept ownership of a private virtual interface created by another customer."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "4b26177d-2353-4280-8676-b7a62d603a1e"
            }
          ]
        },
        {
          "id": "f53917cd-2e10-4e93-b613-364fff647192",
          "name": "confirmPublicVirtualInterface",
          "request": {
            "url": "http://example.com/api/?Action=ConfirmPublicVirtualInterface?virtualInterfaceId=virtualInterfaceId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Accept ownership of a public virtual interface created by another customer."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "3c1c5317-1563-4f88-bf25-19ad37061ba1"
            }
          ]
        },
        {
          "id": "05783e39-2fb5-49b9-a5e3-aa327a2ba16f",
          "name": "createPrivateVirtualInterface",
          "request": {
            "url": "http://example.com/api/?Action=CreatePrivateVirtualInterface?connectionId=connectionId&newPrivateVirtualInterface=newPrivateVirtualInterface",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Creates a new private virtual interface."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "d30fb528-ef9a-4c4c-bf12-962df10b7533"
            }
          ]
        },
        {
          "id": "8dd8d529-ee69-432a-8023-9b4169ad232e",
          "name": "createPublicVirtualInterface",
          "request": {
            "url": "http://example.com/api/?Action=CreatePublicVirtualInterface?connectionId=connectionId&newPublicVirtualInterface=newPublicVirtualInterface",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Creates a new public virtual interface."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "327868f9-76b2-4974-9cf4-30082fdcd167"
            }
          ]
        }
      ]
    },
    {
      "name": "BGP Peer",
      "item": [
        {
          "id": "c58351ce-70e7-49ce-a8e1-bac84985b04f",
          "name": "createBGPPeer",
          "request": {
            "url": "http://example.com/api/?Action=CreateBGPPeer?newBGPPeer=newBGPPeer&virtualInterfaceId=virtualInterfaceId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Creates a new BGP peer on a specified virtual interface."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "380432f7-29a9-4130-80f0-ab814e01e132"
            }
          ]
        },
        {
          "id": "f5d853f8-0385-4c99-b966-816021353c4f",
          "name": "deleteBGPPeer",
          "request": {
            "url": "http://example.com/api/?Action=DeleteBGPPeer?asn=asn&customerAddress=customerAddress&virtualInterfaceId=virtualInterfaceId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes a BGP peer on the specified virtual interface that matches the specified customer address and ASN."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "25c0b325-20b9-4ec3-a08e-4b83b697854f"
            }
          ]
        }
      ]
    },
    {
      "name": "Interconnects",
      "item": [
        {
          "id": "666148e2-15bc-4c6c-bcf8-b697739d238b",
          "name": "createInterconnect",
          "request": {
            "url": "http://example.com/api/?Action=CreateInterconnect?bandwidth=bandwidth&interconnectName=interconnectName&location=location",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Creates a new interconnect between a AWS Direct Connect partner's network and a specific AWS Direct Connect location."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "04b8b8c1-3a6d-4baa-9188-e53299f9c32e"
            }
          ]
        },
        {
          "id": "cdf8b460-3dc2-4823-ba88-24e4b65f915e",
          "name": "deleteInterconnect",
          "request": {
            "url": "http://example.com/api/?Action=DeleteInterconnect?interconnectId=interconnectId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes the specified interconnect."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "c2f56811-52bb-4d28-b26d-9a9967d5f2a5"
            }
          ]
        }
      ]
    }
  ]
}