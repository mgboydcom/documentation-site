{
  "title": "DestinationType",
  "description": "",
  "weight": 1,
  "fields": null,
  "deprecatedFields": null,
  "requireby": [
    {
      "name": "DestinationData",
      "description": "Information about destinantion",
      "url": "/travelgatex/reference/objects/destinationdata"
    }
  ],
  "enumValues": [
    {
      "name": "ZONE",
      "description": "Zone",
      "isDeprecated": false,
      "deprecationReason": null
    },
    {
      "name": "CITY",
      "description": "City",
      "isDeprecated": false,
      "deprecationReason": null
    }
  ],
  "operator": "enum",
  "typename": "DestinationType"
}
Indicates the type of destination
## GraphQL Schema definition

{{% graphql-schema-enum %}}

## Require by

{{% graphql-require-by %}}
