# Cash Coins

* */api/v3/users/`userID`/cash-coins* = Some thing about cashout and money in the account
  * Response Example:
  
    ```js
    {
        "cash_coin": "0.00",
        "currency": "USD",
        "currency_amount": "0",
        "currency_exchange_rate": "0.0035",
        "min_currency_amount": "40.00",
        "max_currency_amount": "5000.00",
        "withdraw_sub_code": 400005,
        "withdraw_sub_msg": "You need to apply for a minimum amount of 40.00USD to cashout",
        "withdraw_sub_title": "Lower than minimum amount"
    }
    ```
