# Discord API

Requests can be made to the Discord API using the following URL format: `https://api.statify.live/discord/ServerInviteHere`

The api will either return a 404 if the server is not found, or a 200 with the data.

an example JSON response is given here `https://api.statify.live/discord/linux`:

```json
{
    "code": 200,
    "data": {
        "invite": "linux",
        "name": "LabsHQ",
        "id": "828936812801425438",
        "splash": "https://cdn.discordapp.com/splashes/828936812801425438/dcaa1f1c0db55a937ef6852f1dcfd081.jpg",
        "icon": "https://cdn.discordapp.com/icons/828936812801425438/a_89235251c465127723ab49b581371646.gif",
        "banner": "https://cdn.discordapp.com/banners/828936812801425438/a675bc8be5f89bd7c8989d6b73b1c994.png",
        "description": "From creators of imgs.today, LabsHQ is managing many bots, and projects",
        "boosts": 14,
        "nsfw": false,
        "members": 224,
        "online": 92
    }
}
```

### Data returned

~ means the data may be excluded if it does not exist

-   HTTP Response Code
-   Data
    -   Invite used to perform lookup
    -   Name
    -   ID
    -   Splash~
    -   Icon~
    -   Banner~
    -   Description~
    -   Boost count
    -   Whether the server is marked NSFW
    -   Member count
    -   Online member count
