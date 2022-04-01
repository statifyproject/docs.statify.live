# Steam API

Requests can be made to the Steam API using the following URL format: `https://api.statify.live/steam/UsernameHere`

The api will either return a 404 if the user is not found, or a 200 with the data.

an example JSON response is given here for `https://api.statify.live/steam/SomeAspy`:

```json
{
    "code": 200,
    "data": {
        "username": "SomeAspy",
        "id64": "76561198344459333",
        "displayName": "SomeAspy",
        "realName": "Aiden",
        "countryCode": "US",
        "stateCode": "MA",
        "rawOnlineState": 0,
        "avatar": "https://steamcdn-a.akamaihd.net/steamcommunity/public/images/avatars/36/360236e555049f204b12d3a8685a3b9b9764ebfe.jpg",
        "onlineState": "Offline"
    }
}
```

### Data returned

-   HTTP Response Code
-   Data
    -   Username
    -   ID64
    -   Display Name
    -   Real Name
    -   Country Code
    -   State Code
    -   Online state as a number
    -   Avatar
    -   Online state as text
