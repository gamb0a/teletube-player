# TeleTube Player
Share your bot, share your music.

Music player controlled by a Telegram bot.

## Quickstart
- make a playlist
- add songs
- create a telegram bot. [see how to do it](https://core.telegram.org/bots#6-botfather)
- write to your bot: `/play $song`
- _optional_: add your bot to a group
- enjoy

## Fully integrated with Telegram Bot
### Commands accepted

`/play` Play or resume the current song

`/play $query` Play the best match from youtube for the `$query` specified

`/shuffle` Shuffles the current playlist (persistent)

`/prev` Play the song before the actual

`/next` Skip the current song

`/skip` Alias for `/next`

`/add $query` Add the best match from youtube to the end of the current playlist for the `$query` specified

`/next $query` Add the best match from youtube after the current song playing for the `$query` specified

`/current` Gives information of the current song playing

`/playlist` Rich menu for the current playlist where the participants of the chat can see and play songs

`/list` Alias for `/playlist`

`/stop` Stop player

`/volume $level` Sets the volume to the level specified by `$level`. Moves from 1 to 100

`/controls` Show buttons on the user's chat to control the player 

`/mute` Mute the current device 

`/unmute` Alias for `/volume 100`
