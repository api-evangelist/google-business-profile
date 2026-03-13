# Google Business Profile API

The Google Business Profile API provides an interface for managing business location information on Google. It enables developers to programmatically manage accounts, locations, reviews, media, posts, and more.

## APIs

- **Google Business Profile API** - Manage business location information including accounts, locations, reviews, media, and local posts.

## Base URL

```
https://mybusiness.googleapis.com/v4
```

## Key Endpoints

- **List Accounts** - `GET /accounts` - List all accounts
- **List Locations** - `GET /accounts/{accountId}/locations` - List business locations
- **Get Location** - `GET /accounts/{accountId}/locations/{locationId}` - Get location details
- **List Reviews** - `GET /accounts/{accountId}/locations/{locationId}/reviews` - List reviews
- **Reply to Review** - `PUT /accounts/{accountId}/locations/{locationId}/reviews/{reviewId}/reply` - Reply to a review
- **List Local Posts** - `GET /accounts/{accountId}/locations/{locationId}/localPosts` - List local posts

## Artifacts

- [APIs.yml](apis.yml) - APIs.json index
- [OpenAPI](openapi/openapi.yml) - OpenAPI 3.1.0 specification
- [JSON Schema](json-schema/Location.json) - JSON Schema (draft 2020-12) for Location
- [JSON-LD Context](json-ld/context.jsonld) - JSON-LD context mapping

## Resources

- [Getting Started](https://developers.google.com/my-business/content/get-started)
- [API Reference](https://developers.google.com/my-business/reference/rest)

## Maintainers

- **Kin Lane** - kin@apievangelist.com
