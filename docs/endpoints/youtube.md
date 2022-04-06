# YouTube API

Requests can be made to the YouTube API using the following URL format: `https://api.statify.live/youtube/ChannelIDHere`

The api will either return a 404 if the user is not found, or a 200 with the data.

an example JSON response is given here for `https://api.statify.live/youtube/UCh--dzF5q_VM5HCrRJN1t2w`:

```json
{
    "code": 200,
    "data": {
        "id": "UCh--dzF5q_VM5HCrRJN1t2w",
        "subs": "4",
        "views": "16",
        "videos": "67",
        "username": "FRCat",
        "description": "",
        "avatar": "https://yt3.ggpht.com/N9lRih0ldMnuvE_jdvV9BAgmBR5Hk-Ta2UOlKEXnhp4yf3zod09bfVxREOQPTlXpQ4C1P2AZCQ=s800-c-k-c0x00ffffff-no-rj"
    }
}
```

### Data returned

-   HTTP Response Code
-   Data
    -   ID
    -   Subs
    -   Views
    -   Videos
    -   Username
    -   Description
    -   Avatar
