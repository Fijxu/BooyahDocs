# Followings

Request Method: GET

* */users/`userID`/followings/* = Get the channels followed by this user
  * Response Example:

     ```js
     {
    "cursor": 0,
    "following_list": [{
        "uid": userID,
        "nickname": "Nickname",
        "nickname_next_update_time": 2592000, // Unix time // If the value is 2592000, it means the user has not changed nickname
        "thumbnail": "https://resmambet-a.akamaihd.net/mambet-storage/Web/Avatar/userID/image-1629340142035.jpeg",
        "gender": 0,
        "gender_next_update_time": 1629263003,
        "age": 0,
        "birthday": 0,
        "birthday_next_update_time": 1629263031,
        "platform": 8, 
        "following_count": 15,
        "follower_count": 39,
        "follow_time": 1629267379,
        "followed_time": 1628928291,
        "notification": 1 // 0 = Notifications about streams disabled, 1 = Notifications enabled
    }
     ```

* */users/`userID`/followings/count* = Get the count of channels followed by this user
  * Response Example:

     ```js
     {"count":1337} // Followings Count
     ```

* */users/`userID`/followings/streams* = ***Pending***
  * Response Example:

     ```js
     Pending
     ```
  