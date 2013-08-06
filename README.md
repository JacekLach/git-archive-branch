git-archive-branch
==================

Archive a git branch by prefixing it with ',,'


The ',,' prefix is chosen so that archived branches show up as very first in
git branch list (thus scrolling out of view and not hiding any real branches).
'__' doesn't do that, '--' is illegal.

Why not delete the branch? Because branch names / branch history are incredibly useful
information if you ever have to go back and figure out what the bigger idea behind a commit was.
