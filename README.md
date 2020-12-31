# reflectwalk

reflectwalk is a Go library for "walking" a value in Go using reflection,
in the same way a directory tree can be "walked" on the filesystem. Walking
a complex structure can allow you to do manipulations on unknown structures
such as those decoded from JSON.

## Fork changes

Currently, this fork adds a minor enhancement to help track the depth of the structure being walked.
