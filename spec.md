# Mario Kart Word - Randomizer

## Problem description

As a player, I want a way to select a number of tracks at random, so the game stays fresh and unpredictable.

I also want a way to select a random "combo" (character + vehicle)

The term "session" will be used to denote one or more tracks selected in order, such that no tracks are repeated until all tracks have already been selected.

A session should start automatically when the randomizer is loaded.

It should be possible to reset a session.

## Technical requirements

- The randomizer must run in a browser, fully client-side, using HTML, CSS and javascript
- The user interface must be mobile friendly and work on both iOS and Android devices
- The state of the randomizer must be persistent across refreshes
- The state must contain an ordered list of tracks already selected

## User interface

The user interface should contain the following
- The ordered history of tracks already selected
- A button to pick the next track at random
- A button to reset the session, clearing the state
- A separate button to pick a random combo, that is displayed in a modal popup that dismisses after clicking outside it. The popup should pick a random combo when opening, and have a button to pick again.

## List of tracks
- Acorn Heights
- Airship Fortress
- Boo Cinema
- Bowser's Castle
- Cheep Cheep Falls
- Choco Mountain
- Crown City
- Dandelion Depths
- Desert Hills
- Dino Dino Jungle
- DK Pass
- DK Spaceport
- Dry Bones Burnout
- Faraway Oasis
- Great ? Block Ruins
- Koopa Troopa Beach
- Mario Bros. Circuit
- Mario Circuit
- Moo Moo Meadows
- Peach Beach
- Peach Stadium
- Rainbow Road
- Salty Salty Speedway
- Shy Guy Bazaar
- Sky-High Sundae
- Starview Peak
- Toad's Factory
- Wario Stadium
- Wario's Galleon
- Whistlestop Summit

## List of characters
- Mario
- Luigi
- Peach
- Bowser
- Yoshi
- Toad
- Daisy
- Rosalina
- Donkey Kong
- Wario
- Koopa Troopa
- Pauline
- Waluigi
- Toadette
- Baby Mario
- Baby Luigi
- Baby Peach
- Baby Daisy
- Baby Rosalina
- Bowser Jr.
- Lakitu
- King Boo
- Shy Guy
- Birdo
- Dry Bones
- Wiggler
- Hammer Bro
- Chargin' Chuck
- Nabbit
- Monty Mole
- Goomba
- Piranha Plant
- Pianta
- Spike
- Dolphin
- Cow
- Pokey
- Para-Biddybud
- Penguin
- Sidestepper
- Snowman
- Cataquack
- Fish Bone
- Peepa
- Swoop
- Stingby
- Rocky Wrench
- Coin Coffer
- Cheep Cheep
- Conkdor

## List of vehicles
- Standard Kart
- Plushbuggy
- Zoom Buggy
- Rally Kart
- Baby Blooper
- Chargin' Truck
- Blastronaut III
- Roadster Royale
- Carpet Flyer
- Billdozer
- Big Horn
- Hot Rod
- Snowmobile
- Frog Kart
- Old Timey
- Toy Truck
- Green Saucer
- Pipe Frame
- B Dasher
- Tiny Titan / Rally Romper
- Bumble V
- Cloud 9
- Biddybuggy
- Standard Bike
- Cute Scoot
- Rally Bike
- Mach Rocket
- W-Twin Chopper
- Fin Twin
- Mario Bros. Bike
- Radio Bike
- Train Bike
- R. O. B. Bike
- Dolphin Dasher
- Bowser Bruise
- Funky Dorrie
- Lobster
- Trike
- ATV Ski
- ATV Tread