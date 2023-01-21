# Awesome List Updates on Jan 19, 2016

7 awesome lists updated today.

[🏠 Home](/README.md) · [🔍 Search](https://www.trackawesomelist.com/search/) · [🔥 Feed](https://www.trackawesomelist.com/rss.xml) · [📮 Subscribe](https://trackawesomelist.us17.list-manage.com/subscribe?u=d2f0117aa829c83a63ec63c2f&id=36a103854c) · [❤️  Sponsor](https://github.com/sponsors/theowenyoung)



## [1. Vim Galore](/content/mhinz/vim-galore/README.md)

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

## [2. Awesome Npm](/content/sindresorhus/awesome-npm/README.md)

### Articles

*   [Unix philosophy and Node.js](http://blog.izs.me/post/48281998870/unix-philosophy-and-nodejs) - Write programs that do one thing and do it well.

## [3. Awesome Courses](/content/prakhar1989/awesome-courses/README.md)

### Courses / Machine Learning

*   [CVX 101](https://class.stanford.edu/courses/Engineering/CVX101/Winter2014/info) **Convex Optimization** *Stanford University* <img src="https://assets-cdn.github.com/images/icons/emoji/unicode/1f4bb.png" width="20" height="20" alt="Assignments" title="Assignments" /> <img src="https://assets-cdn.github.com/images/icons/emoji/unicode/1f4dd.png" width="20" height="20" alt="Lecture Notes" title="Lecture Notes" /> <img src="https://assets-cdn.github.com/images/icons/emoji/unicode/1f4da.png" width="20" height="20" alt="Readings" title="Readings" />
    *   The course concentrates on recognizing and solving convex optimization problems that arise in applications.  Topics addressed include the following.  Convex sets, functions, and optimization problems.  Basics of convex analysis.  Least-squares, linear and quadratic programs, semidefinite programming, minimax, extremal volume, and other problems.  Optimality conditions, duality theory, theorems of alternative, and applications.  Interior-point methods.  Applications to signal processing, statistics and machine learning, control and mechanical engineering, digital and analog circuit design, and finance.
    *   [Textbook](http://web.stanford.edu/\~boyd/cvxbook/)
    *   [Lectures and Assignments](https://class.stanford.edu/courses/Engineering/CVX101/Winter2014/courseware/7206c57866504e83821d00b5d3f80793/)

## [4. Awesome Webaudio](/content/notthetup/awesome-webaudio/README.md)

### Packages / Apps

*   [Molgav (⭐2)](https://github.com/surikov/molgav) - Musical Step Sequencer for melodies exchange.

## [5. Awesome Elixir](/content/h4cc/awesome-elixir/README.md)

### Caching

*   [elixir\_locker (⭐14)](https://github.com/tsharju/elixir_locker) - Locker is an Elixir wrapper for the locker Erlang library that provides some useful libraries that should make using locker a bit easier.

### HTTP

*   [fuzzyurl (⭐19)](https://github.com/gamache/fuzzyurl.ex) - An Elixir library for parsing, constructing, and wildcard-matching URLs. Also available for [Ruby (⭐13)](https://github.com/gamache/fuzzyurl.rb) and [JavaScript (⭐4)](https://github.com/gamache/fuzzyurl.js).

## [6. Awesome Stock Resources](/content/neutraltone/awesome-stock-resources/README.md)

### Photography / CC0-license

*   [Pexels](https://www.pexels.com/) - 20 new high-quality photos daily.

### Photography / Custom License / Usage

*   [Pic Jumbo](https://picjumbo.com/) - [:copyright:](https://picjumbo.com/faq-and-terms/) Totally free photos for your commercial & personal works.

### Photography / Unspecified License

*   [Refe Real Life Photos](http://getrefe.tumblr.com) - Free real life photos from [REFE](http://getrefe.com/).

### Icons / Icon Fonts

*   [Weather Icons](https://erikflowers.github.io/weather-icons/) - Weather Icons is the only icon font and CSS with 222 weather themed icons.

### Paid Resources / Icons Packages and Collections

*   [Stocksy](https://www.stocksy.com/) - "Cliché-free" Photos.

### How to Share / Icons Packages and Collections

*   [Share on Facebook](https://www.facebook.com/sharer/sharer.php?s=100\&p\[url]=https://github.com/neutraltone/awesome-stock-resources\&p\[images]\[0]=\&p\[title]=Awesome%20Stock%20Resources\&p\[summary]=)
*   [Share on LinkedIn](https://www.linkedin.com/shareArticle?mini=true\&url=https://github.com/neutraltone/awesome-stock-resources\&title=Awesome%20Stock%20Resources\&summary=\&source=)

## [7. Awesome Datascience](/content/academic/awesome-datascience/README.md)

### Facebook Accounts / Book Deals (Affiliated) 🛍

*   [Veri Bilimi Istanbul](https://www.facebook.com/groups/veribilimiistanbul/)

---

- Prev: [Jan 20, 2016](/content/2016/01/20/README.md)
- Next: [Jan 18, 2016](/content/2016/01/18/README.md)