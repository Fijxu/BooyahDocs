# Audience Count (Spectators)

Request Method: GET

* */chatrooms/`userID`/audiences/count* = Get info about the channel chatroom, contains the list of moderators of the channel
  * Response Example:

      ```js
      {
      "ccu": 0,
      "logged_in_ccu": 0,
      "viewer_count": 0
      }
      ```

## Curl Request

```bash
curl 'https://booyah.live/api/v3/chatrooms/12345678/audiences/count' \
  -H 'booyah-session-key: yourbooyahsessionkey'
```
