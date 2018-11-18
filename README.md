# [Svelte/Sapper community map](https://mindrones.github.io/svelte-sapper-community/)

Map of the [[https://svelte.technology|Svelte]]/[[https://sapper.svelte.technology/|Sapper]] community.

## How to add/remove yourself to the map

If you want to add/remove yourself please edit [this csv](https://github.com/mindrones/svelte-sapper-community/blob/gh-pages/community.csv) and send a PR.

Fields:
- `name`: your real name (optional)
- `nickname`: kinda mandatory as it appears as a label when hovering on markers
- `lat`: mandatory
- `lon`: mandatory
- `url1`: url (example: https://twitter.com/mindrones)
- `urltext1`: text for url1 (example: twitter)
- `url2`: url
- `urltext2`: text for url2

For optional fields just use an empty string: for example if you don't want to use your real name, use:

`,myNickname,0,0,http://twitter.com/myNickname,twitter`.

## How to find your location

You can use https://www.openstreetmap.org.

Search for a location and/or navigate the map: you'll see that the URL contains a string like `#map=19/51.50464/-0.10426`: its format is `#map={zoom}/{lat}/{lon}`, so you can just copy the last two numbers.
