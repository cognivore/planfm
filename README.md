# planfm
Plan.fm is a last.fm scrobbler that launches a target music player with some playlist and scrobbles while the music player is active.

## Use-case

In 2024, scrobbler plugins are largely abandoned for most music players, which means that people who *really like* music (who used to be the major part of the audience of last.fm) miss at least third of the scrobbles.

Instead of refactoring a dozen plugins (some of which is closed-source), we go the other way -- we provide a command a user can call to start listening to an album in their music player of choice and then we check for the spawned player's PID, while sending the user notifications about scrobbling as songs change.

## Supported systems

Windows and Linux.
