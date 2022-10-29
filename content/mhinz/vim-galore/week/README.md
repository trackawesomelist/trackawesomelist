# Track Vim Galore Updates Weekly

:mortar_board: All things Vim!

[🏠 Home](/README.md) · [🔍 Search](https://www.trackawesomelist.com/search/) · [🔥 Feed](https://www.trackawesomelist.com/mhinz/vim-galore/week/rss.xml) · [📮 Subscribe](https://trackawesomelist.us17.list-manage.com/subscribe?u=d2f0117aa829c83a63ec63c2f&id=36a103854c) · [😺 mhinz/vim-galore](https://github.com/mhinz/vim-galore) · ⭐ 15K · 🏷️ Editors

[ [Daily](/content/mhinz/vim-galore/README.md) / Weekly / [Overview](/content/mhinz/vim-galore/readme/README.md) ]

## [Oct 01 - Oct 07, 2018](/content/2018/40/README.md)

### Additional resources / Screencasts

*   [vimcasts.org](http://vimcasts.org/episodes/archive)
*   [By wincent](https://www.youtube.com/channel/UCXPHFM88IlFn68OmLwtPmZA)
*   [By Derek Wyatt](http://derekwyatt.org/vim/tutorials/index.html)

## [Apr 09 - Apr 15, 2018](/content/2018/15/README.md)

### Ranges

*   Most commands act only on the current line by default. Notable exceptions are
    `:write` and `:global` which act on all lines.

## [Jan 15 - Jan 21, 2018](/content/2018/3/README.md)

### True colors / Small intro

*   The first line should be the same for most people and denotes the `$TERM` to
    be used *within* tmux.
*   The second line adds the tmux-specific `Tc` (true color) capability to the
    other terminfo entries of `xterm-256color`. Obviously this assumes that the
    user is using `TERM=xterm-256color` *outside* of tmux.
*   Read `:h 'termguicolors'`.
*   Put `set termguicolors` in your vimrc.
*   Make sure your colorscheme has color definitions for GUIs. (It should contain
    lines with `guifg` and `guibg`.)
*   Make sure your terminal emulator of choice supports true colors.
*   Using tmux? Configure it to add the `Tc` capability.

## [Nov 06 - Nov 12, 2017](/content/2017/45/README.md)

### Quickfix and location lists

*   There is only one quickfix list. There can be multiple location lists; one per
    window.
*   They use slightly different commands for navigation.

## [Jun 26 - Jul 02, 2017](/content/2017/26/README.md)

### Getting help offline

*   VimL functions end in `()`, e.g. `:h reverse()`
*   commands start with `:`, e.g. `:h :echo`

## [Apr 17 - Apr 23, 2017](/content/2017/16/README.md)

### Backup files

*   **Copying**
    1.  A full copy of the original file is created and used as backup.
    2.  The original file gets emptied and then filled with the content of the
        Vim buffer.
*   **Renaming**
    1.  The original file is renamed to the backup file.
    2.  The content of the Vim buffer gets written to a new file with the name of
        the original file.

## [Jan 02 - Jan 08, 2017](/content/2017/1/README.md)

### Vim distributions / Screencasts

*   [spacevim (⭐19k)](https://github.com/SpaceVim/SpaceVim)

## [Aug 01 - Aug 07, 2016](/content/2016/31/README.md)

### Function search undo / Screencasts

*   A search pattern in a command (`/`, `:substitute`, ...) changes the "last used
    search pattern". (It's saved in the `/` register; print it with `:echo @/`).
*   A simple text change can be redone with `.`. (It's saved in the `.` register;
    print it with `:echo @.`).

## [Mar 07 - Mar 13, 2016](/content/2016/10/README.md)

### Cscope

*   Where is this symbol defined?
*   Where is this symbol used?
*   What is this global symbol's definition?
*   Where did this variable get its value?
*   Where is this function in the source files?
*   What functions call this function?
*   What functions are called by this function?
*   Where does the message "out of space" come from?
*   Where is this source file in the directory structure?
*   What files include this header file?

## [Jan 18 - Jan 24, 2016](/content/2016/3/README.md)

### Ranges

*   Many commands take ranges.
*   An address denotes a certain line.
*   A range is either a single address or a pair of addresses separated by either
    `,` or `;`.
*   Ranges tell commands which lines to act on.

### Macros

*   Start recording by typing `q` followed by the register, e.g. `q`. (The
    command-line will signify this via "recording @q".)
*   Stop recording by hitting `q` once again.
*   Execute the macro via `[count]@q`.
*   Repeat the last used macro via `[count]@@`.

### Getting help offline (alternative)

*   Options are enclosed in single quotes. So you would use `:h 'list'` to go to
    the help topic for the list option. If you only know, you are looking for a
    certain option, you can also do `:h options.txt` to open the help page which
    describes all option handling and then you can search using regular
    expressions e.g. `/width`. Certain options have their own namespace, e.g. `:h
    cpo-a`, `:h cpo-A`, `:h cpo-b`, and so on.
*   Normal mode commands are just that. Use `:h gt` to go to the help page for
    the "gt" command.
*   Regexp items always start with "/", so `:h /\+` takes you to the help item
    for the "+" quantifier in Vim regexes. If you need to know anything about
    regular expressions, start reading at `:h pattern.txt`.
*   Key combinations. They usually start with a single letter indicating the mode
    for which they can be used. E.g. `:h i_CTRL-X` takes you to the family of
    CTRL-X commands for insert mode which can be used to auto complete different
    things. Note that certain keys will always be written the same, e.g. Control
    will always be CTRL. Note, for normal mode commands, the "n" is left away,
    e.g. `:h CTRL-A`. In contrast, `:h c_CTRL-R` will describe what CTRL-R does
    when entering commands in the command line and `:h v_Ctrl-A` talks about
    incrementing numbers in visual mode and `:h g_CTRL-A` talks about the g<C-A>
    command (thus you have to press "g" then <Ctrl-A>). Here the "g" stand for
    the normal command "g" which always expect a second key before doing
    something similar to the commands starting with "z".
*   Registers always start with "quote" so use `:h quote` to find out about the
    special ":" register.
*   Vim script (VimL) is available at `:h eval.txt`. Certain aspects of the
    language are available at `:h expr-X` where 'X' is a single letter, e.g. `:h
    expr-!` will take you to the topic describing the '!' (Not) operator for
    VimL. Also important, see `:h function-list` to find a short description of
    all functions available.
*   Mappings are talked about in the help page `:h map.txt`. Use `:h mapmode-i`
    to find out about the `:imap` command. Also use `:map-topic` to find out
    about certain subtopics particular for mappings (e.g. `:h :map-local` for
    buffer-local mappings or `:h map_bar` for how the '|' is handled in mappings.
*   Command definitions are talked about at `:h command-*`, so use :h command-bar
    to find out about the '!' argument for custom commands.
*   Window management commands always start with CTRL-W, so you find the
    corresponding help at `:h CTRL-W_*` (e.g. `:h CTRL-W_p` for switch to the
    previously accessed window). You can also access `:h windows.txt` and read
    your way through, if you are looking for window handling command.
*   Ex commands always start with ":", so `:h :s` covers the ":s" command.
*   Use CTRL-D after typing a topic and let Vim try to complete to all available
    topics.
*   Use `:helpgrep` to search in all help pages (usually also includes help
    pages by installed plugins). See `:h :helpgrep` for how to use it. Once you
    have searched for a topic, all matches are available in the quickfix (or
    location) window which can be opened with `:copen` or `:lopen`. There you
    can also use `/` to further filter the matches.
*   `:h helphelp` contains some information on how to use the help.
*   The user manual. This describes help topics for beginners in a rather
    friendly way. Start at `:h usr_toc.txt` to find the table of content (as you
    might have guessed). Skimming over that help to find certain topics, .e.g
    you will find an entry "Digraphs" and "Entering special characters" in
    chapter 24 (so use `:h usr_24.txt` to go to that particular help page).
*   Highlighting groups always start with `hl-*`. E.g. `:h hl-WarningMsg` talks
    about the "WarningMsg" highlighting group.
*   Syntax highlighting is namespaced to ":syn-topic", e.g. `:h :syn-conceal`
    talks about the conceal argument for the :syn command.
*   Quickfix commands usually start with ":c", while location list commands
    usually start with ":l".
*   `:h BufWinLeave` talks about the BufWinLeave autocmd. Also, `:h
    autocommands-events` talks about all possible events.
*   Startup arguments always start with "-", so `:h -f` takes you to the help of
    the "-f" command switch of Vim.
*   Compiled extra features always start with "+", so `:h +conceal` talks about
    the conceal support.
*   Error codes can be looked up directly in the help. `:h E297` takes you
    exactly to the description of the error message. Sometimes however, those
    error codes are not described, but rather are listed at the Vim command that
    usually causes this. E.g. `:h hE128` takes you directly to the `:function`
    command.
*   Documentation for included syntax files is usually available at `:h
    ft-*-syntax`. E.g. `:h ft-c-syntax` talks about the C syntax file and the
    options it provides. Sometimes, additional sections for omni completion (`:h
    ft-php-omni`) or filetype plugins (`:h ft-tex-plugin`) are available.

## [Jan 11 - Jan 17, 2016](/content/2016/2/README.md)

### Cheatsheets

*   <http://people.csail.mit.edu/vgod/vim/vim-cheat-sheet-en.png>
*   <https://cdn.shopify.com/s/files/1/0165/4168/files/preview.png>
*   <http://michael.peopleofhonoronly.com/vim/vim_cheat_sheet_for_programmers_screen.png>
*   <http://www.rosipov.com/images/posts/vim-movement-commands-cheatsheet.png>

## [Jan 04 - Jan 10, 2016](/content/2016/1/README.md)

### Getting help offline

*   options are enclosed in single quotes, e.g. `:h 'textwidth'`

### Vim distributions / Screencasts

*   [cream](http://cream.sourceforge.net)
*   [janus](https://github.com/carlhuda/janus.git)
*   [spf13 (⭐15k)](https://github.com/spf13/spf13-vim)

### Delays when using escape key in terminal / Screencasts

*   `<esc>` is used a lot for returning to normal mode or quitting an action.
*   Cursor keys are encoded using escape sequences.
*   Vim expects <kbd>Alt</kbd> (also called *Meta key*) to send a proper 8-bit
    encoding with the high bit set, but many terminal emulators don't support it
    (or don't enable it by default) and send an escape sequence instead.