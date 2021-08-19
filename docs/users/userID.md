# userID

* */api/v3/users/`userID`* = Get info about the userID account
  * Response Example:

    ```js
    {
        "user": {
            "uid": 12345678, // userID
            "nickname": "Fijxu", // Nickname
            "nickname_next_update_time": 1627966320, 
            // The date and time in which the user is available to change their nickname. This can be converted to human time with this Unix command: 
            //"date --date='@1627966320'" Output = Tue Aug  3 12:52:00 AM -04 2021
            "thumbnail": "https://totalyrealurl:)/mambet-storage/Web/Avatar/74290923/image-1625374334547.jpeg", //Profile Picture
            "gender": 0, // Gender of the user, 0 = No gender, 1 = Male, 2 = Female, 3 = Other, 4 = Keep Secret
            //I do not guarantee that these will be the values of the genres, it is only a prediction.
            "gender_next_update_time": 0, // The date and time in which the user is available to change their gender.
            // This can be converted to human time with the same Unix command mentioned before
            "age": 51, // Age of the user (Is 0 if the user has not entered his or her date of birth)
            "birthday": -4406400, // The birthday birth of the user, why this is public?
            "birthday_next_update_time": 1628822959, // The date and time in which the user is available to change their birthday.
            // This can be converted to human time with the same Unix command mentioned before
            "platform": 8, // The login method used by the user
            // none = 0,
            // facebook = 3,
            // vk = 5,
            // line = 6,
            // google = 8,
            // apple = 10,
            // twitter = 11
            "following_count": 5, // Channels this user follows
            "follower_count": 16 // Users who follow this user
        },
        "channel": {
            "channel_id": 12345678, // channelID, is the same as userID
            "chatroom_id": 12345678, // The id of chatroom of this user
            "name": "ffmpeg and shit!", // Title of the stream
            "streaming_lang": "en", // Language of this user
            "description": "", // Description of this channel
            "flag": 16, // wtf is this????????? 
            // From internal files: enableUploadVod = !!(flag & 512); enableHosting = !!(flag & 1024);
            // I think it means that if the user has the flag 512, he is allowed to upload vods, if he has the flag 1024, he can host other streamers.
            // There is also a hidden flag in some streamers which is 5813, 5300, 1716, and other mores, i think a higher flag means higher priority or higher permissions.
            "offline_pic": "", // Ofline picture, like twitch when a streamer is offline
            "thumbnail": "", // Customized thumbnail for the main page
            "create_time": 1625374300, // The date when the account was created
            // This can be converted to human time with the same Unix command mentioned before
            "share_url": "https://booyah.live/channels/12345678", // The share url when a user press the share button 
            "alias": "SomeAlias", // Alias of the user
            // Obvious strings
            "is_streaming": false, 
            "is_verified_streamer": false,
            "is_content_creator": false,
            "is_enable_vod": false,
            "is_enable_download_vod": false,
            "is_enable_long_clip": false,
            // Obvious strings
            "is_enable_lucky_draw": false, // free fire's lucky draw i guess
            "social_links": [] // Social links that the user has posted on his channel
        }
    }
    ```
