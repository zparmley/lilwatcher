# lilwatcher

Just a simple watcher script, which requires 'watch' https://github.com/mikeal/watch/

Resolves PWD wherever it is run from, and fires off a command when a file in the watched directory changes

## Installation

Place the file in a directory included in your path, give write permissions, then run from any directory ala:
	lilwatcher "rsync ~/development/world_domination skynet-1:stage_one/"