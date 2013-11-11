# Snippets

Snippets inject text templates at the cursor location when the trigger keystrokes are entered. 

Press _Tab_ to move between text-entry-points inside the injected text, or press _Esc_ to finish text-entry mode.

### Module

    Snippet             Trigger keystrokes
    --------------------------------------
    defmodule-do-end    dme{Tab}
    import              im{Tab}
    import-only         io{Tab}
    alias-as            aa{Tab}

### Module methods

    Snippet             Trigger keystrokes
    --------------------------------------
    def-do-end          df{Tab}
    def-do:             df:{Tab}
    def-when-do-end     dwdo{Tab}
    def-when-do:        dwd:{Tab}

    defp-do-end         dp{Tab}
    defp-do:            dp:{Tab}

### Anonymous functions

    Snippet             Trigger keystrokes
    --------------------------------------
    anon-fn-1           fn{Tab}
    anon-fn-2           f&{Tab}

### Macros

    Snippet             Trigger keystrokes
    --------------------------------------
    defmacro-do-end     dmo{Tab}
    defmacrop-do-end    dmp{Tab}

### Blocks

    Snippet             Trigger keystrokes
    --------------------------------------
    do-end              do{Tab}
    do:                 d:{Tab}

### Control flow

    Snippet             Trigger keystrokes
    --------------------------------------
    if-do-else-end      if{Tab}
    case-do-end         cs{Tab}
    cond do-end         cd{Tab}
    arrow               ->{Tab}

### Documentation

    Snippet             Trigger keystrokes
    --------------------------------------
    doc                 dc{Tab}
    mdoc                mdc{Tab}


