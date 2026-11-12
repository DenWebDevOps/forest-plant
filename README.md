# forest-plant

A tiny Telegram Mini App: pick what you did, slide how long, and send it to your own bot, which plants a tree in a
self-hosted focus forest.

It is one static page (`index.html`) with no backend and no secrets. The choice goes to the bot through Telegram's
`WebApp.sendData`; the bot checks every field again before planting anything.
