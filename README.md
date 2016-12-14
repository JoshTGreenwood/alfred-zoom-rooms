# Alfred Zoom Rooms

## What does it do?
In my organization, we have many permanent Zoom rooms we jump in and out of throughout the day. We haved named them all so that when I say I'm in "Hamilton", everyone knows I'm talking about the zoom room with id `example-id-123`.  It is cumbersome to remember all of these different ids, so this Alfred workflow allows me to type "zm Hamilton" which opens Zoom, types the corresponding meeting id, and presses join.

## Install

```
git clone https://github.com/joshtgreenwood/alfred-zoom-rooms.git
cd alfred-zoom-rooms
open Zoom.alfredworkflow
```

## Setup
1. Open the workflow in the Alfred Workflow Editor
1. Open the list filter and either manually add entries or drag a CSV file (format: name,subtext,room-number) containing the rooms you care about.

## Usage

```
zm [name]
```

## TODO
* It may or may not be hard coded to 'Free account' need to fix for non free accounts
* Start a new video call if no arguments are given
* Make setup easier

## Credits
Code and ideas borrowed from https://github.com/lnguyen/zoom-alfred
