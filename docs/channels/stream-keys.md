# Stream Keys

Request Method: POST

* */users/`userID`/coins* = Get info about your streamkey and stream server
  * Response Example:

    ```json
    {
        "url": "rtmp://rtpmip:1935/live",
        "stream_key": "12345678?token=56lenghttoken",
        "speed_test_url": "http://rtpmip:1935/speedtest"
    }
    ```
