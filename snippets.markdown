# Snippets

Snippets inject text at the cursor location when the trigger-keystrokes are entered. 

Tab between text-entry points inside the injected text, or hit Esc to finish text-entry



### Module

    Snippet             Trigger-keystrokes
    --------------------------------------
    defmodule-do-end    dme{Tab}

### Module methods

    Snippet             Trigger-keystrokes
    --------------------------------------
    def-do-end          df{Tab}
    def-do:             df:{Tab}
    def-when-do-end     dwdo{Tab}
    def-when-do:        dwd:{Tab}

    defp-do-end         dp{Tab}
    defp-do:            dp:{Tab}

### Anonymous functions

    Snippet             Trigger-keystrokes
    --------------------------------------
    fn                  fn{Tab}
    anonf               f&{Tab}

### Macros

    Snippet             Trigger-keystrokes
    --------------------------------------
    defmacro-do-end     dmo{Tab}
    defmacrop-do-end    dmp{Tab}

### Blocks

    Snippet             Trigger-keystrokes
    --------------------------------------
    do-end              do{Tab}
    do:                 d:{Tab}

### Documentation

    Snippet             Trigger-keystrokes
    --------------------------------------
    doc                 dc{Tab}
    mdoc                mdc{Tab}


