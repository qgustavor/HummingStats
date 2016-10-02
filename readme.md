# HummingStats

Hummingbird offers a public API where is possible to get some public info about
the users, like who they love and how much anime they watched. This project is
about collecting those data and publishing statistics.

Collected data:

* Usernames\*
* Waifu / Husbando
* Anime watched in minutes
* Adult content preference
* Language preference

\* For now no stats are generated and published using this data, also I don't want
to generate rankings for users.

The data is being collected using the API since 09/09/2016 (curious that is not
possible to mistake month and day) and may not reflect the actual state of the
website. The API is being queried 24/7 since this day, but in a slow rate to
avoid any problems to Hummingbird, also giving contact information in the
user-agent string in all requests if needed.

I think the developers can easily implement a official stats page, but they're
too focused on the next version of Hummingbird, so I wanted to make a not
official one *for science*.
