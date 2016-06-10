# Timestamplet

A browser bookmarklet to insert the date and time into a text or `textarea` field.

This was first made to easily insert the timestamps into Trello cards, but it
should work with any text fields on any website in any browser!

# Installation

Open `timestamplet.html` in your browser and drag your desired bookmarklet on to
your bookmarks bar. You can even just add them as normal bookmarks, but I suspect
that won't be very convenient.

_Tip:_ If you need more than one on a regular basis, maybe you can organize them into
folders.

# Usage

Simply focus the text box or `textarea` that you're looking at timestamping and click
on the bookmarklet.

_Tip:_ Use a browser extension such as [Shortkeys](https://chrome.google.com/webstore/detail/shortkeys-custom-keyboard/logpjaacgmcbpdkdchjiaagddngobkck?hl=en) to be able to use this with a shortcut, such as `Alt`+`Shift`+`T`.

# Variations

The bookmarklet is available in a few flavors:

1. Inserts the timestamp at at the end of the text in the field.
1. Inserts the timestamp at the beginning of the field.

More flavors are coming soon.

# Tech

The bookmarklets are all written in ES6, but it should be easy to make them work on
older browsers by changing the `let` command to `var`.

# Contributing

Fork, add your own flavors or improevements and send a PR!

# License

MIT. Do whatever you want with this, but do attribute! :-)

