# Daily Logins

* */api/v3/users/`userID`/followers/daily-logins* = Some info about the daily login of YOUR user, you can't view other users daily-login info and streaks
  * Response Example:

     ```js
    {
    "daily_login_list": [{
        "day": 1,
        "reward_type": 0,
        "reward_amount": 25,
        "status": 1,
        "review_time": 1629154508 // Unix time
    }, {
        "day": 2,
        "reward_type": 0,
        "reward_amount": 25,
        "status": 1,
        "review_time": 1629176468 // Unix time
    }, {
        "day": 3,
        "reward_type": 0,
        "reward_amount": 25,
        "status": 1,
        "review_time": 1629259336 // Unix time
    }, {
        "day": 4,
        "reward_type": 0,
        "reward_amount": 50,
        "status": 0
    }, {
        "day": 5,
        "reward_type": 0,
        "reward_amount": 50,
        "status": 0
    }, {
        "day": 6,
        "reward_type": 0,
        "reward_amount": 50,
        "status": 0
    }, {
        "day": 7,
        "reward_type": 2,
        "reward_amount": 1,
        "ff_item_name": "BOOYAH Weapon Loot Crate",
        "ff_item_icon_url": "https://totallyrealurl/booyah/ops_resource/loot_item_pic/loot_crate_booyah_weapon.notapng", 
        // Scuffed url to avoid scrapping
        "status": 0
    }],
    "current_day": 3, // Current day of the daily login streak 
    "current_time": 1629309773, // Unix time
    "next_day_time": 1629331200, // Unix time
    "next_cycle_time": 1629676800 // Unix time
    } 
    ```
