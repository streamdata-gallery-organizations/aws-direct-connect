{
  "info": {
    "name": "AWS Direct Connect API Create B G P Peer",
    "_postman_id": "ef4b0d39-5c7d-4085-8c3c-1cdeeb7e233c",
    "description": "Creates a new BGP peer on a specified virtual interface.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Connections",
      "item": [
        {
          "id": "5fb368d9-b6a9-453b-a4dd-621964c659fb",
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
              "id": "2d4030ee-92b9-42b9-837a-4d20cf8b6190"
            }
          ]
        },
        {
          "id": "5b8ba67a-7643-471f-b961-589f8a0d7a4b",
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
              "id": "baf718a0-8d52-4a8d-8bdb-117b47cda000"
            }
          ]
        }
      ]
    },
    {
      "name": "Private Virtual Interfaces",
      "item": [
        {
          "id": "2b191bb7-57f4-40cf-a283-0f4692ba05e2",
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
              "id": "b797174b-d54d-4046-b502-5f7e8863dab8"
            }
          ]
        },
        {
          "id": "8d51a05b-8097-41f8-ab01-258ec531c100",
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
              "id": "19f9a5b7-5113-4552-864e-f40e34f87a41"
            }
          ]
        },
        {
          "id": "1a33e652-96b4-48f6-b1fc-77ff0a8f5cbc",
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
              "id": "6c3b8773-5b47-42db-8f69-0e7bdc3fd2af"
            }
          ]
        },
        {
          "id": "95b6d1d4-fe21-4897-99da-d87761b31056",
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
              "id": "a155e4d5-cfed-4dce-a9b6-a35a404c4039"
            }
          ]
        }
      ]
    },
    {
      "name": "BGP Peer",
      "item": [
        {
          "id": "9e1e2daa-e509-40a7-8ca8-cc1bbd6dc3be",
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
              "id": "56a18b25-62ec-406e-82e8-61a254a4082f"
            }
          ]
        }
      ]
    }
  ]
}