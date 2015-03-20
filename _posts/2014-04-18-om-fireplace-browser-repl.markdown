---
title: "Connecting to browser-repl with vim-fireplace"
tags: clojurescript om vim fireplace repl workflow
---
**Updated 2015-03-18**: Things haved changed a lot since a year ago, the [basic-tutorial][om-basic-tutorial] has been updated to use [figwheel][figwheel] instead, not to mention that there is [chestnut][chestnut] available as well.

--- 

**tldr;** [om-fireplace-brepl][om-fireplace-brepl] is a lein template that scaffolds an enviroment for you to start using [Om][om] with [fireplace][vim-fireplace] and browser-repl.

I am trying to learn how to use the infamous Clojurescript [Om library][om]by following the [basic tutorial][om-basic-tutorial], but it is based on using [LightTable][lighttable] as the IDE. But since I am a VIM user and already using [fireplace][vim-fireplace], I worked out how to connect to the broser-repl with fireplace.

The end result is [this lein template][om-fireplace-brepl]. Hope someone would find it useful.


[om]: https://github.com/omcljs/om
[om-basic-tutorial]: https://github.com/omcljs/om/wiki/Basic-Tutorial
[lighttable]: https://lighttable.com
[vim-fireplace]: https://github.com/tpope/vim-fireplace
[om-fireplace-brepl]: https://github.com/epak/om-fireplace-brepl
[figwheel]: https://github.com/bhauman/lein-figwheel
[chestnut]: https://github.com/plexus/chestnut
