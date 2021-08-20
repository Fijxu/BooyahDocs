# Followers

Request Method: GET

* */users/`userID`/followers/* = Get the last 100 followers of the channel with info about the users.
  * Response Example:

     ```js
     {
    "cursor": 12345678, // Unknown ID, It means I don't know where it comes from
    "follower_list": [{
        "uid": userID,
        "nickname": "Nickname",
        "nickname_next_update_time": 2592000, // Unix time // If the value is 2592000, it means the user has not changed nickname
        "thumbnail": "https://resmambet-a.akamaihd.net/mambet-storage/Channel/Avatar/userID/userID.avatar",
        "gender": 0,
        "gender_next_update_time": 0,
        "age": 0,
        "birthday": 0,
        "birthday_next_update_time": 0,
        "platform": 0,
        "following_count": 0,
        "follower_count": 0
    }
     ```

* */users/`userID`/followers/count* = Get the follower count of channelID
  * Response Example:

     ```js
     {"count":1337} // Follower Count
     ```
  