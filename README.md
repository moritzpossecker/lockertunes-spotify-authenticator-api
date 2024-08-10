# lockertunes-spotify-athenticator-api
This repository is responsible for getting `access_token`'s using the spotify [Authorization Code with PKCE Flow](https://developer.spotify.com/documentation/web-api/tutorials/code-pkce-flow).
The Client is not communicating directly with the spotify api to store the `SPOTIFY_CLIENT_ID` and the `SPOTIFY_CLIENT_SECRET` in the backend of the application.

## How to set up
Simply create a `.env`-File in this directory. It should then look like this:
```javascript
SPOTIFY_CLIENT_ID='client_id'
SPOTIFY_CLIENT_SECRET='client_secret'
```