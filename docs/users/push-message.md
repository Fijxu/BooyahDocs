# Push Message - Private

Request Method: GET

* */users/`userID`/push-messages?to_msg_id=&count=20* = Get the list of push messages in your account
  * Response Example: Response to long for be posted here, fetch it yourself

Request Method: GET

## Push Message Sessions

* */users/`userID`/push-messages-sessions* = Get id of the notifications, and the unread count
  * Response Example:

    ```js
    {
    "read_msg_id": "20randomnumbersherex", // Some random numbers with id
    "unread_msg_count": 0, // Unreaded notifications
    "latest_msg_id": "20randomnumbersherex" // Latest id of msg
    }
    ```

Request Method: PATCH

* */users/`userID`/push-message-sessions* = This request is invoked when the user reads the notifications.
  * Request Example:

    ```js
    {
    "read_msg_id":"13667911151371411783"
    }
    ```

  * Response Example:

    ```js
    {
    "read_msg_id": "13667911151371411783",
    "unread_msg_count": 0,
    "latest_msg_id": "13667911151371411783"
    }
    ```
