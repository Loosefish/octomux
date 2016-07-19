# octomux

Wrapper script for reusing tmux sessions.

## Basic Usage

Calling `octomux` for the first time will create new session.
Calling `octomux` again will attach to that session or create a linked session if it's not detached.
Detached linked sessions are removed on start and exit.
This way using `octomux` will always attach you to the *same* session, without having to think about the details.

See `octomux -h` for further options.
