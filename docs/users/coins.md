# Coins

* */api/v3/users/`userID`/coins* = Get info about your account coins and tickets count
  * Response Example:

    ```js
    {
        "coin": 0, // Your coins
        "ticket_info": {
            "balance": 1065, // Your tokens
            "sent": 200, // Total tokens spended in streamers or something else
            "received": 0 // Recived tokens 
        }
    }
    ```
