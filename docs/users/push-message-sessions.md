# Push Message Sessions

* */api/v3/users/`userID`/push-message-sessions* = Get some things about the notificactions
  * Response Example:

    ```json
    {
    "read_msg_id": "20randomnumbersherex", // Some random numbers with id
    "unread_msg_count": 0, // Unreaded notifications
    "latest_msg_id": "20randomnumbersherex" // Latest id of msg
    }
    ```
