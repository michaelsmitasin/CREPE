# CREPE
Community Regular Expression Parser Exchange

We're all spending a bunch of time writing regular expressions for log parsers, this is a place to share and improve on such REs so that we're not all just reinventing the wheel.

Naming convention:

`<application using the RE/parser>:<source of the log messages>:<category of messages>.<regular expression syntax>`

Example:

sumologic:syslog:ssh:.re2

Sumologic is using the regular expression
The logs come from Syslog
The category of logs is SSH
The syntax is RE2
