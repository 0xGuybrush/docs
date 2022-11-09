---
id: health
title: Server health
slug: /api/health
---

# Show Server Status

Ping the server and see if it is alive and ready for requests.

**URL** : `/health`

**Method** : `GET`

## Example

`curl "https://sourcify.dev/server/health" `

## Success Response

**Code** : `200 OK`

**Text** : `Alive and kicking!`