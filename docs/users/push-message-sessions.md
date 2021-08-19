# Push Message Sessions

Request Method: GET

* */users/`userID`/push-message-sessions* = Get Somethings about the notificactions
  * Response Example:

    ```js
    {
    "read_msg_id": "20randomnumbersherex", // Some random numbers with id
    "unread_msg_count": 0, // Unreaded notifications
    "latest_msg_id": "20randomnumbersherex" // Latest id of msg
    }
    ```
