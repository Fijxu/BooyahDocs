# Playbacks - Public

Request Method: GET

* */users/`userID`/playblacks/count* = Probably the number of times a user has replayed a VOD
  * Response Example:

     ```js
    {
    "total_count": 3,
    "count_by_game": [{
        "game_id": 0,
        "count": 3
    }]
    }
     ```
