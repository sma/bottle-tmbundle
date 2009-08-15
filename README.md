TextMate Bundle for Bottle
==========================

[Bottle][bottle] is a the Python-based micro web framework.

It provides a new Python mode with special highlight support for routes and
some predefined snippets to creates routes and validators faster.

It provides a new HTML mode with highlighting support for Bottle templates.

[bottle]: http://bottle.paws.de/

Installation
------------

    mkdir -p ~/Library/Application\ Support/TextMate/Bundles/
    cd ~/Library/Application\ Support/TextMate/Bundles
    git clone git://github.com/sma/bottle-tmbundle.git Bottle.tmbundle
    osascript -e 'tell app "TextMate" to reload bundles'
