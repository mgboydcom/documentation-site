+++
title = "The Basics"
description = ""
weight = 2
alwaysopen = false
+++

## Become a TravelgateX Partner

The first step towards building your next travel API is to become a TravelgateX registered partner. 

At this moment, please [contact us](mailto:sales@travelgatex.com) in order to become a partner.

We will be publishing a registration website so each developer can register for an account with us. Please bear with us.

## Create your API key

To communicate with the GraphQL server, you'll need an access token with the right scopes.

This access token could be an [API Key](/admin/security/authentication/#api-keys) or a [JSON Web Token](/admin/security/authentication/#json-web-tokens), and the correct way to send it to GraphQL server is via HTTP Header:

* API key: `"Authorization: Apikey xxxxxxxxx"`
* JWT: `"Authorization: Bearer xxxxxxxxx"`

Follow the steps in [Creating an access token](/admin/security/authentication/#creating-an-access-token) to create a token.

### GraphQL Endpoint
One of the great things we love about GraphQL is that there's only one single endpoint. Use this endpoint for all operations you want to perform: 

{{% alert theme="warning" %}}https://api.travelgatex.com{{% /alert %}} 

## Making Requests

Because GraphQL operations consist of multiple operations and schemas, we recommend using the Explorer to make GraphQL calls.
There are some alternatives to use GraphQL builtin explorer like GraphQL Playground. You can also use cURL or any other HTTP-speaking library.

{{% alert theme="danger" %}}All **LIVE** traffic **MUST** enable GZIP compression in the HTTP header{{% /alert %}} 

```html
Accept-Encoding: gzip
```

To query GraphQL using cURL, make a POST request with a JSON payload. The payload must contain a string called query:

```bash
curl -X\
   POST\
   -H "Content-Type: application/json" \
   -H "Authorization: Apikey q8ggxpoVDW76Kw918hwnnRvxlZmAP2QZ"  \
   --data '{"query":"{searchStatusService{code description}}"}' \
   --compressed \
   https://api.travelgatex.com
```


## Debugging requests

{{% alert theme="danger" %}}**TODO: Falta chicha!!**{{% /alert %}}

## API Call Limits

{{% alert theme="danger" %}}**TODO: Falta chicha!!**{{% /alert %}}

## Product Specific Quick Start

Although there's only one endpoint, our GraphQL API models all the products and services we offer. Please navigate to the desired product documentation in order to start building your app.

- [ConnectX Hotel](/connectx/hotel/): Next generation hotel search & booking API.
- [ConnectX Flights](/connectx/flight): Next generation _NDC compliant_ flight search & booking API.
- Stats: All the requests sent and received, their response times and status codes.
- Insights: Become a true data-first decision maker by leveraging our rich Insights API. All the requests, all the searches, everything you've made with us available here.
- Mappea: Collaborative Hotel Mapping. Use this API to map your suppliers or to make that everything you have mapped is accurate.

## Get Engaged

You are not alone! The API is designed to be very intuitive and easy to read. Nevertheless, although we strive to keep things simple, some concepts can be confusing and we understand learning a new API can be overwhelming. There are many ways of getting help. The [Playground](https://api.travelgatex.com) contains the API's documentation. As an alternative you can get help from the community or raise a ticket and our support staff will be delighted to solve any doubts, complaints or suggestions you might have.

### Documentation
Documentation is generated from GraphQL schema.You can use multiple columns and keyboard-based navigation via the [Playground](https://api.travelgatex.com)

{{<figure src="/images/graphql_playground.gif" link="https://api.travelgatex.com"  alt="travelgateX Schema Documenation">}}

### Community

We use [discourse](www.discourse.org) to run our community forum. It's completely free and you can access it [here](discourse.travelgatex.com). Please use your own travelgatex.com username and password in order to log in discourse.

### Jira Service Desk

Our Customer Care Team runs the show using Jira Service Desk. Please raise any questions, complaints, suggestions or any other issues [here](https://xmltravelgate.atlassian.net/servicedesk/customer/portal/7).

The login has been given to you together in the welcome pack. Let us know if you haven't received it or can't find it so we can send it to your email address.
