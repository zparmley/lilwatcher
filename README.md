# lilwatcher

Just a simple watcher script, which requires 'watch' https://github.com/mikeal/watch/

Resolves PWD wherever it is run from, and fires off a command when a file in the watched directory changes

## Installation

Place the file in a directory included in your path, give write permissions, then run from any directory ala:
<pre>
mekmek:world_domination root$ lilwatcher "rsync ~/development/world_domination skynet-1:stage_one/"
</pre>

Whenever a file inside 'world_domination' (pwd) changes, the rsync command will fire off

Output is console logged