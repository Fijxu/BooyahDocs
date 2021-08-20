# Liked Games - Unknown

Request Method: GET

* */users/`userID`/liked-games* = Get the channels followed by this user
  * Response Example:

     ```js
     {"count":1337} // Follower Count
     ```

Request Method: DELETE

* */users/`userID`/liked-games/{gameid}* = Get the channels followed by this user
  * Response Example:

     ```js
     {"count":1337} // Follower Count
     ```

Request Method: GET

* */users/`userID`/liked-games/{gameid}* = Get the channels followed by this user
  * Response Example:

     ```js
     {"count":1337} // Follower Count
     ```

Request Method: POST

* */users/`userID`/liked-games/{gameid}/{token}* = Get the channels followed by this user
  * Response Example:

     ```js
     {"count":1337} // Follower Count
     ```
