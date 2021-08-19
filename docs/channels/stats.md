# Stats

Request Method: GET

* *channels/`userID`/stats* = Get accounts accounts you have blocked
  * Response Example:

    ```json
    {
        "new_followers": 17,
        "stream_stats": {
            "minutes_streamed": 212,
            "minutes_watched": 195,
            "unique_viewers": 282,
            "total_viewers": 282,
            "average_viewers": 0.9952830188679245,
            "peak_viewers": 4,
            "peak_viewers_time": 1628844360,
            "received_gift_value": 0,
            "received_ticket": 0,
            "average_logged_in_booyah_ccu": 0.9198113207547169,
            "stream_days": 0
        },
        "highlight_stats": {
            "count": 0,
            "average_duration": 0,
            "total_views": 0,
            "total_minutes_watched": 0,
            "total_likes": 0
        },
        "clip_stats": {
            "count": 0,
            "average_duration": 0,
            "total_views": 0,
            "total_minutes_watched": 0,
            "total_likes": 0
        }
    }
    ```
