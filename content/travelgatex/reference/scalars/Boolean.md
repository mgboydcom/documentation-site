{
  "title": "Boolean",
  "description": "",
  "weight": 1,
  "fields": null,
  "deprecatedFields": null,
  "requireby": [
    {
      "name": "AccessData",
      "description": "",
      "url": "/travelgatex/reference/objects/accessdata"
    },
    {
      "name": "SupplierData",
      "description": "",
      "url": "/travelgatex/reference/objects/supplierdata"
    },
    {
      "name": "Provider",
      "description": "Temporary type to use only during SQL server's lifetime",
      "url": "/travelgatex/reference/objects/provider"
    },
    {
      "name": "PageInfo",
      "description": "",
      "url": "/travelgatex/reference/objects/pageinfo"
    },
    {
      "name": "ClientFilter",
      "description": "",
      "url": "/travelgatex/reference/inputobjects/clientfilter"
    },
    {
      "name": "ClientData",
      "description": "",
      "url": "/travelgatex/reference/objects/clientdata"
    },
    {
      "name": "OrganizationData",
      "description": "",
      "url": "/travelgatex/reference/objects/organizationdata"
    },
    {
      "name": "GroupCommonData",
      "description": "",
      "url": "/travelgatex/reference/interfaces/groupcommondata"
    },
    {
      "name": "GroupData",
      "description": "",
      "url": "/travelgatex/reference/objects/groupdata"
    },
    {
      "name": "Member",
      "description": "",
      "url": "/travelgatex/reference/objects/member"
    },
    {
      "name": "RoleData",
      "description": "",
      "url": "/travelgatex/reference/objects/roledata"
    },
    {
      "name": "HotelData",
      "description": "Hotel data",
      "url": "/travelgatex/reference/objects/hoteldata"
    },
    {
      "name": "DestinationData",
      "description": "Information about destinantion",
      "url": "/travelgatex/reference/objects/destinationdata"
    },
    {
      "name": "HotelSettingsInput",
      "description": "Settings that you can edit for this avail. Values are loaded by default in our Back Office.",
      "url": "/travelgatex/reference/inputobjects/hotelsettingsinput"
    },
    {
      "name": "SettingsBaseInput",
      "description": "Contains the time out and business rules of a supplier or an access.",
      "url": "/travelgatex/reference/inputobjects/settingsbaseinput"
    },
    {
      "name": "Room",
      "description": "Contains the room information of the option returned.",
      "url": "/travelgatex/reference/objects/room"
    },
    {
      "name": "Price",
      "description": "Price indicates the value of the room/option.\nSupplements and/or surcharges could be or not included into the price, will be verified with the nodes Supplements/Surcharges.",
      "url": "/travelgatex/reference/objects/price"
    },
    {
      "name": "Priceable",
      "description": "",
      "url": "/travelgatex/reference/interfaces/priceable"
    },
    {
      "name": "Markup",
      "description": "Informs markup applied over supplier price.",
      "url": "/travelgatex/reference/objects/markup"
    },
    {
      "name": "Bed",
      "description": "Contains information about a bed.",
      "url": "/travelgatex/reference/objects/bed"
    },
    {
      "name": "Supplement",
      "description": "Supplement that it can be or its already added to the option returned. Contains all the information about the supplement.",
      "url": "/travelgatex/reference/objects/supplement"
    },
    {
      "name": "Surcharge",
      "description": "Surcharge that it can be or it is already added to the option returned. Contains all the information about the surcharge.",
      "url": "/travelgatex/reference/objects/surcharge"
    },
    {
      "name": "CancelPolicy",
      "description": "Contains information about a cancel policy.",
      "url": "/travelgatex/reference/objects/cancelpolicy"
    },
    {
      "name": "StatsFilterInput",
      "description": "Filters needed to do a search.\nUsers (List of users), Suppliers (List of suppliers), ServiceApis (List of service apis), From (Start date of search - YYYY-MM-DD HH:mm:ss), To (End date of search - YYYY-MM-DD HH:mm:ss)",
      "url": "/travelgatex/reference/inputobjects/statsfilterinput"
    },
    {
      "name": "OperationDetailed",
      "description": "",
      "url": "/travelgatex/reference/objects/operationdetailed"
    },
    {
      "name": "Mutation",
      "description": "Mutations are operations that change or update data in the server.",
      "url": "/travelgatex/reference/schema/mutation"
    },
    {
      "name": "AccessInput",
      "description": "Access input",
      "url": "/travelgatex/reference/inputobjects/accessinput"
    },
    {
      "name": "CreateClientInput",
      "description": "",
      "url": "/travelgatex/reference/inputobjects/createclientinput"
    },
    {
      "name": "UpdateClientInput",
      "description": "",
      "url": "/travelgatex/reference/inputobjects/updateclientinput"
    },
    {
      "name": "DeltaPriceInput",
      "description": "Input delta price, indicates price variation permitted by the client",
      "url": "/travelgatex/reference/inputobjects/deltapriceinput"
    },
    {
      "name": "SupplierGroup",
      "description": "group related to a supplier",
      "url": "/travelgatex/reference/objects/suppliergroup"
    },
    {
      "name": "ConnectUser",
      "description": "data related to a connect user and its groups",
      "url": "/travelgatex/reference/objects/connectuser"
    },
    {
      "name": "ConnectUserGroup",
      "description": "group related to a connect user",
      "url": "/travelgatex/reference/objects/connectusergroup"
    },
    {
      "name": "AccessConfigurationInput",
      "description": "The information required to access the supplier's system.",
      "url": "/travelgatex/reference/inputobjects/accessconfigurationinput"
    },
    {
      "name": "AccessConnectUserInput",
      "description": "Connect user input for data access management API",
      "url": "/travelgatex/reference/inputobjects/accessconnectuserinput"
    },
    {
      "name": "ConnectUserGroupInput",
      "description": "group related to a connect user",
      "url": "/travelgatex/reference/inputobjects/connectusergroupinput"
    },
    {
      "name": "AccessSupplierInput",
      "description": "Supplier input for data access management API",
      "url": "/travelgatex/reference/inputobjects/accesssupplierinput"
    },
    {
      "name": "SupplierGroupInput",
      "description": "group related to a supplier",
      "url": "/travelgatex/reference/inputobjects/suppliergroupinput"
    },
    {
      "name": "IdAccessConfigurationInput",
      "description": "",
      "url": "/travelgatex/reference/inputobjects/idaccessconfigurationinput"
    },
    {
      "name": "MappeaXAddOrganizationInput",
      "description": "# AddOrganization",
      "url": "/travelgatex/reference/inputobjects/mappeaxaddorganizationinput"
    },
    {
      "name": "MappeaXEditOrganizationInput",
      "description": "# EditOrganization",
      "url": "/travelgatex/reference/inputobjects/mappeaxeditorganizationinput"
    },
    {
      "name": "LegacyData",
      "description": "The URI type represents a URI values. A good example mith be an Hotel Image URL.\nIn queries or mutations, URI fields have to be specified in RFC 3986, RFC 3987, and RFC 6570 (level 4) compliant URI string format with enclosing double quotes: \"http:\\www.travelgatex.com\".",
      "url": "/travelgatex/reference/objects/legacydata"
    }
  ],
  "enumValues": null,
  "operator": "scalar",
  "typename": "Boolean"
}
The `Boolean` scalar type represents `true` or `false`.
## GraphQL Schema definition

{{% graphql-schema-scalar %}}

## Require by

{{% graphql-require-by %}}
