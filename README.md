# Narsese on Prolog (NP)

This is a SWI-Prolog pack that runs Narsese like OpenNARS

OpenNARS for Prolog is a completely new platform and not branched from the existing OpenNARS codebase. The Narsese in Prolog (NP) system takes the logic and conceptual ideas of OpenNARS, and will be doing event handling and procedural learning much like ANSNA.
 
- LOGICMOO IRC channel #logicmoo on [freenode.net](irc://irc.freenode.net:+6697/logicmoo).
- LOGICMOO Telegram at [https://t.me/LogicMoo](https://t.me/LogicMoo)
- NARS mailing list at https://groups.google.com/forum/?fromgroups#!forum/open-nars
- NARS on IRC channel #nars on freenode.net.



# Installation

Using SWI-Prolog 7.1 or later:

    ?- pack_install('https://github.com/TeamSPoon/narsese.git').



Source code available and pull requests accepted at
http://github.com/TeamSPoon/narsese

```prolog
?- use_module(library(narsese)).
true.

```

# Some TODOs

Document this pack!

Write tests

Untangle the 'pack' install deps 
(Moving predicates over here from logicmoo_base)


# Not _obligated_ to maintain a git fork just to contribute

Dislike having tons of forks that are several commits behind the main git repo?

Be old school - Please ask to be added to TeamSPoon and Contribute directly !

Still, we wont stop you from doing it the Fork+PullRequest method

[BSD 2-Clause License](LICENSE.md)

Copyright (c) 2020, 
TeamSPoon and Douglas Miles <logicmoo@gmail.com> 
All rights reserved.


