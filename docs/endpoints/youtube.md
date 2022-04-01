# YouTube API

Requests can be made to the YouTube API using the following URL format: `https://api.statify.live/youtube/UsernameHere`

The api will either return a 404 if the user is not found, or a 200 with the data.

an example JSON response is given here for `https://api.statify.live/youtube/RTGame`:

```json
{
    "code": 200,
    "data": {
        "channel": "RTGame",
        "id": "UCRC6cNamj9tYAO6h_RXd5xA",
        "avatar": "https://yt3.ggpht.com/lkuVbQ5BgmoWWQvZMS7wv_-ZZ-mIadKZDIEj5PdtAseERS6xPzmUSk9aFR66iTBs1r7gghLpzA=s88-c-k-c0xffffffff-no-rj-mo",
        "subscribers": "2680000",
        "views": "970979372",
        "videos": "772"
    }
}
```

### Data returned

-   HTTP Response Code
-   Data
    -   Name
    -   ID
    -   Avatar
    -   Subscribers
    -   Views
    -   Videos
