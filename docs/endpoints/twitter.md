# Twitter API

Requests can be made to the Twitter API using the following URL format: `https://api.statify.live/twitter/UsernameHere`

The api will either return a 404 if the user is not found, or a 200 with the data.

an example JSON response is given here for `https://api.statify.live/twitter/RTGameCrowd`:

```json
{
    "code": 200,
    "data": {
        "username": "RTGameCrowd",
        "id": "2174756820",
        "followers": 282831,
        "following": 1025,
        "tweets": 9518,
        "verified": true,
        "avatar": "https://pbs.twimg.com/profile_images/1396202246963089409/FvIU61hb_normal.jpg"
    }
}
```

### Data returned

-   HTTP Response Code
-   Data
    -   Username
    -   ID
    -   Followers
    -   Following
    -   Tweet count
    -   Verified
    -   Avatar
