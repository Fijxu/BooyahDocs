# Blocks - Private

Request Method: GET

* */users/`userID`/blocks* = Get accounts accounts you have blocked
  * Response Example:

    ```js
    {
        "block_list": [{
            "blocked_uid": "12345678", //userID of the blocked user
            "nickname": "Thisismynickname", // Nickanem of the blocked user
            "source": 0 // From booyah files -> // 0: MAMBETTV, 1: YOUTUBE, 3:FACEBOOK
            // MAMBETTV is the old name of booyah
        }]
    }
    ```
