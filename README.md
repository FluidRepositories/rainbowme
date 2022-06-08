# rainbowme
A short and simple text rainbowifier CLI for Discord chats

## Why
For centuries (ok not literally), Discord chats have been lackluster of a specific type of pizzazz. Then Discord rolled out support for ANSI formatting. But the general public does not use it, and most people don't know what that even is. Thus, I make a simple CLI for generating some epic rainbow text you can paste right into Discord, in seconds.

## Discord mobile woes
At the moment of writing this readme, Discord mobile does NOT support ANSI formatting. This cannot be fixed by anyone other than Discord themselves. Users on mobile will see all of the formatting characters and will think that you're having a stroke.

## Usage
`python rainbowme.py hello world!`
Or if you want to specify a background color:
`python rainbowme.py hello world! -bg white`
Or if you want to specify a style for the text:
`python rainbowme.py hello world! -style underline`
You can even add all that together too:
`python rainbowme.py hello world! -bg white -style underline`
