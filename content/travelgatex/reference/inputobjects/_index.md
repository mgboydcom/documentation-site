{
  "title": "Input objects",
  "pagetitle": null,
  "description": "",
  "weight": 5,
  "icon": null,
  "alwaysopen": false
}
Input Objects is an abstract type that includes a set of fields that can be used together to make a query. 

For example the `HotelCriteriaSearchInput` lists which fields must be completed to filter search results for a hotel booking. In this case, it is mandatory to include: 
- Check-in date
- Check-out date
- The number of hotel options you want to receive
- The number of rooms needed. 
There are also non-mandatory fields that can be included such as currency (for returning hotel prices), and the nationality of traveler.

Each `Input Object` is described in the same way:
- A short definition of the `Input Object` 
- An interactive GraphQL schema definition
- A list of which fields are used by this `Input Object` (remember, in GraphQL, ‘!’ indicates mandatory fields. Some interfaces have all fields mandatory and some have a mix of mandatory and optional fields)
- Where possible, we are adding examples of how to use this object in your queries.

{{% alert theme="info" %}}You can update any page of our documentation by clicking on ‘Edit page’ and sending a pull request or by making a comment on the page. Our average turnaround for responding to pull requests or comments is less than 24 hours.{% /alert %}}
