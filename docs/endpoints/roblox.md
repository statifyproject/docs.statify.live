# Roblox API

Requests can be made to the Roblox API using the following URL format: `https://api.statify.live/roblox/UsernameHere`

The api will either return a 404 if the user is not found, or a 200 with the data.

an example JSON response is given here for `https://api.statify.live/roblox/SomeAspy`:

```json
{
    "code": 200,
    "data": {
        "username": "SomeAspy",
        "online": false,
        "id": 26131041,
        "followers": 1371,
        "friends": 146,
        "avatar": "https://www.roblox.com/headshot-thumbnail/image?userId=26131041&width=420&height=420&format=png"
    }
}
```

### Data returned

-   HTTP Response Code
-   Data
    -   Username
    -   Online status
    -   ID
    -   Follower count
    -   Friend count
    -   Avatar
