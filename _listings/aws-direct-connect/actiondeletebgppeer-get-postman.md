{
  "info": {
    "name": "AWS Direct Connect API Delete B G P Peer",
    "_postman_id": "d5578158-b9a7-459a-81b9-19746bc46f2f",
    "description": "Deletes a BGP peer on the specified virtual interface that matches the specified customer address and ASN.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Connections",
      "item": [
        {
          "id": "ed088f8e-a884-4d32-b6eb-81ed5e535de0",
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
              "id": "afd3c3f8-ca21-47c0-98f4-6504af5f15f6"
            }
          ]
        },
        {
          "id": "1292213f-3b15-4703-9af7-58a889eb7d3f",
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
              "id": "8a9332c3-00c5-44fd-a933-9163c5a4d873"
            }
          ]
        },
        {
          "id": "a8567336-8a2d-46ae-9b94-b33281e49d2d",
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
              "id": "4b2d3e77-1514-4b23-87e3-093f35e181a7"
            }
          ]
        }
      ]
    },
    {
      "name": "Private Virtual Interfaces",
      "item": [
        {
          "id": "f424db46-89ea-48a6-879a-59ccd76fb72c",
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
              "id": "6ac8ca11-6848-4c4a-bd75-51c2c8b334e0"
            }
          ]
        },
        {
          "id": "5fc5d51d-cb49-4aeb-a05b-ac89a3b58c34",
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
              "id": "6f8a4f51-45ef-4506-92cf-4614fc26f051"
            }
          ]
        },
        {
          "id": "1ce92a22-1335-40fb-be93-6e2db7fa3e3a",
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
              "id": "bf7bedeb-f7fa-4873-a7ea-e372a84b79da"
            }
          ]
        },
        {
          "id": "07873701-848f-47d0-9ad2-1e2bea1c18ba",
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
              "id": "29b51481-9843-42d0-9a96-b244633eb93d"
            }
          ]
        },
        {
          "id": "afed1b14-7b82-4234-8eb3-ed725d46a490",
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
              "id": "365c12b8-4bca-4dd8-849a-f51bfc292564"
            }
          ]
        },
        {
          "id": "c2bef880-0176-4371-a7f4-a3cc36302987",
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
              "id": "282ca332-d5bc-457f-b725-7ea79fce96c8"
            }
          ]
        }
      ]
    },
    {
      "name": "BGP Peer",
      "item": [
        {
          "id": "eae87e7b-8ed9-453c-bd09-62e045ba4a49",
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
              "id": "7f83f007-e164-49fb-b9fc-51de40f3a5d0"
            }
          ]
        },
        {
          "id": "5adbce2e-76eb-4539-8443-90db1aa96eb7",
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
              "id": "d0f7de82-e4c0-40f1-9f6c-8260b097a0ac"
            }
          ]
        }
      ]
    },
    {
      "name": "Interconnects",
      "item": [
        {
          "id": "dc386ea7-e3f8-4eae-8f91-891e425b68b0",
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
              "id": "0dd06a66-144a-46c5-b29d-e62f26d7c00e"
            }
          ]
        }
      ]
    }
  ]
}