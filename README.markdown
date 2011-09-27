# RubyDebug TextMate Bundle

## Installation

    mkdir -p ~/Library/Application\ Support/TextMate/Bundles/
    cd ~/Library/Application\ Support/TextMate/Bundles/
    git clone git://github.com/DMajrekar/RubyDebug-tmbundle.git Ruby\ Debug.tmbundle
    osascript -e 'tell app "TextMate" to reload bundles'

## Snippets

### debug

Prints the current filename and line number to STDOUT

### debugc

Prints the current filename and line number with an additional argument to STDOUT

### debugt

Prints the current filename and line number with the current Kernel trace to STDOUT

### ldebug

Logs the current file, line number and additional argument to logger.debug

## Contributors

* DMajrekar
* turbogeek421