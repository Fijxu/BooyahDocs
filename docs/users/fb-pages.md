# FB Pages - Public

Request Method: GET

* */users/`userID`/fb/pages* = Get the linked facebook page in the user channel
  * Response Example (if the user don't has a facebook page linked):

     ```js
    {
    "code": 400,
    "message": "facebook link not found"
    }
     ```
  