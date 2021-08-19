# Streams

* */channels/`userID`/streams* = Get info about some stream, varies depending on whether streamer is offline or online. This can be used to detect if the streamer is live and send a notification.
  * Response Example if streamer is live:

    ```js
    {
    "game_build_id": 0, // Game/category number
    "snapshot": "https://resmambet-a.akamaihd.net/mambet-storage/Stream/Snapshot/12345678/12345678.jpg",
    "snapshot_webp": "https://resmambet-a.akamaihd.net/mambet-storage/Stream/Snapshot/12345678/12345678.webp",
    "stream_addr_list": [{
        "resolution": "1080p",
        "url_path": "/hls/1000051/12345678.m3u8" // The m3u8 list
    }],
    "mirror_list": [{ // Mirror list
        "name": "centurylink.br.cdn.booyah.live",
        "url_domain": "https://centurylink.br.cdn.booyah.live"
    }, {
        "name": "aws-br.cdn.booyah.live",
        "url_domain": "https://aws-br.cdn.booyah.live"
    }, {
        "name": "akamai2-br.cdn.booyah.live",
        "url_domain": "https://akamai2-br.cdn.booyah.live"
    }, {
        "name": "google-br.cdn.booyah.live",
        "url_domain": "https://google-br.cdn.booyah.live"
    }],
    "default_mirror": "akamai2-br.cdn.booyah.live",
    "viewer_count": 2, // Spectators
    "viewer_count_info": [{
        "platform": "mambettv", // Mambettv = Booyah
        "live_views": 2 
    }],
    "encoder": "Lavf58.76.100", // The encoder being used by the streamer
    // If is "Lavf" , is ffmpeg
    // If is "obs-output module (libobs version 2x.x.x)", is Open Broadcasting Software
    "tag_uniq": "",
    "create_time": 1629322384, // Unix time // Time at which the stremearing started
    "update_time": 1629323357, // Unix time //The time at which the data in this request is updated.
    "source_stream_url_path": "/hls/1000051/12345678.m3u8" // The m3u8 list
    }
    ```

  * Response Example if streamer is offline:

    ```js
    {
    "code": 404, // Error code
    "message": "Stream is not online" //
    }
    ```
