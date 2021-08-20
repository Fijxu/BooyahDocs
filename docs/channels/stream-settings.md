# Stream Settings

Request Method: GET

* */users/`userID`/stream-settings* = Get info about the stream settings
  * Response Example:

    ```json
    {
        "game_build_id": 100000,
        "title": "ffmpeg and shit!",
        "description": "",
        "resolution": "720p",
        "thumbnail": "",
        "thumbnail_path": "",
        "chat_notification": 1,
        "join_room_notification": 1,
        "new_follower_notification": 1,
        "detect_keyword_notification": 1,
        "send_gift_notification": 1,
        "party_up_notification": 1,
        "msg_mode": 0,
        "add_bgm": 1,
        "voice_command": false,
        "package_name": "",
        "streaming_lang": "en",
        "setting_list": [],
        "tag_uniq": "",
        "stream_start_msg": ""
    }
    ```
