# Cash Coins - Private Access

Request Method: GET

* */api/v3/users/`userID`/cash-coins* = Get the money balance in your account
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

## Withdrawals

Request Method: GET

* */api/v3/users/`userID`/cash-coins/withdrawals* = Get the withdrawals list in your account (I am not sure)
  * Response Example:
  
    ```js
    {
    "next_cursor": 0,
    "withdrawal_list": []
    }
    ```

Request Method: POST

* */api/v3/users/`userID`/cash-coins/withdrawals* = Get the money balance in your account
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
