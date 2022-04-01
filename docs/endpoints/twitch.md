# Twitch API

Requests can be made to the Twitch API using the following URL format: `https://api.statify.live/twitch/UsernameHere`

The api will either return a 404 if the user is not found, or a 200 with the data.

an example JSON response is given here for `https://api.statify.live/twitch/RTGame`:

```json
{
    "code": 200,
    "data": {
        "username": "RTGame",
        "id": "88547576",
        "views": 18136454,
        "avatar": "https://static-cdn.jtvnw.net/jtv_user_pictures/538b904b-f7c0-4738-b288-bc9d18065245-profile_image-300x300.png",
        "followers": 1077325
    }
}
```

### Data returned

-   HTTP Response Code
-   Data
    -   Username
    -   ID
    -   View Count
    -   Avatar
    -   Followers
