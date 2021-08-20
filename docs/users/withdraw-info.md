# Withdraw Info - Private

Request Method: GET

* */users/`userID`/withdraw-info* = Get the info about withdraw iin your account
  * Response Example:

     ```js
    {
    "user_withdraw_info": {
        "uid": userID,
        "region": "US",
        "region_updated": false,
        "phone": "",
        "email": "",
        "id_number": "",
        "id_front_url": "",
        "bank_account": "",
        "bank_book_url": "",
        "home_address": "",
        "pay_pal_email": ""
    }
    }
     ```
