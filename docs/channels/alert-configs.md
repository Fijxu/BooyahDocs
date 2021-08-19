# Alert Config

Request Method: GET

* */channels/`userID`/alert-config* = Get alert configuration of a channel

  * Response Example:

    ```json
    {
        "alert_config": {
            "channel_id": 12345678,
            "is_chat_list_open": true,
            "is_loot_drop_winner_open": false,
            "is_new_follower_open": true,
            "is_free_gift_open": true,
            "coin_gift": 0,
            "gift_ranking": 0,
            "is_latest_gifter_open": false,
            "is_hosting_open": true,
            "alert_box_url": "https://booyah.live/standalone/chatroom/chat-alert?room_id=12345678&uid=12345678&token=246lenghttoken",
            "gift_ranking_url": "https://booyah.live/standalone/chatroom/ranking-alert?room_id=12345678&uid=12345678&token=246lenghttoken",
            "chat_list_url": "https://booyah.live/standalone/chatroom/chat-list?room_id=12345678&uid=12345678&token=246lenghttoken",
            "create_time": 1627944417,
            "update_time": 1628724488
        },
        "banner_alert_new_follower_config": {
            "message_template": "{username} started following you!",
            "layout_id": "customize_3",
            "alert_duration": 2,
            "font_size": 14,
            "custom_img_url": "https://resmambet-a.akamaihd.net/mambet-storage/Web/ChatAlert/12345678/image-1628724059089",
            "custom_img_name": "ff.gif"
        },
        "gift_ranking_common_config": {
            "background_transparency": 15,
            "font_size": 12
        }
    }
    ```