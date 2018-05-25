**!> This is BETA API and might not work as expected.**

# List Favorites 

This API allows you to list all favorites

## Request Method 
GET

## Endpoint
https://api.vrchat.cloud/api/1/favorites/

## Requires Authentication
Yes

## Parameters

Field | Type | Optional | Description
------|------|----------|------------
type | `TypeOptions` | Yes | The type

## Returns 

Array of:

Field | Type | Description
------|------|------------
id | string | Favorite ID
type | `TypeOptions` | The type added
favoriteId | string | The Object Id
tags | array | Unknown

### TypeOptions

    - world
    - friend
    - avatar


**!>** Type `friend` does not work on this endpoint and are told to use `user`, but are pretty sure it will be friend once it is out of beta.