# v8 resources

## Total

* [v8-official blog](https://v8.dev/blog)
* [v8-official-document-blog](https://v8.dev/docs)
* [v8-perf](https://github.com/thlorenz/v8-perf)
* [learning-v8](https://github.com/danbev/learning-v8)
* [v8-internals](https://github.com/lazyparser/v8-internals)
* [V8 / Chrome Architecture Reading List - For Vulnerability Researchers](https://zon8.re/posts/v8-chrome-architecture-reading-list-for-vulnerability-researchers/)
* [v8 git update](https://chromium.googlesource.com/v8/v8.git/+log)

## Fundamental

### Article

* [JavaScript engine fundamentals: Shapes and Inline Caches](https://mathiasbynens.be/notes/shapes-ics)
* [JavaScript engine fundamentals: optimizing prototypes](https://mathiasbynens.be/notes/prototypes#tradeoffs)
* [What's up with monomorphism?](https://mrale.ph/blog/2015/01/11/whats-up-with-monomorphism.html)
* [Elements kinds in V8](https://v8.dev/blog/elements-kinds)--[vedio](https://www.youtube.com/watch?time_continue=11&v=m9cTaYI95Zc&feature=emb_logo)--[slide](https://slidr.io/mathiasbynens/v8-internals-for-javascript-developers#1)
* [A tour of V8: object representation](http://jayconrod.com/posts/52/a-tour-of-v8--object-representation)
* [Fast properties in V8](https://v8.dev/blog/fast-properties)

### Slide

* [V8 internals for JavaScript developers](https://slidr.io/mathiasbynens/v8-internals-for-javascript-developers#1)
* [Demystifying v8 and JavaScript Performance](http://thlorenz.com/talks/demystifying-v8/talk.pdf)

### Vedio

* [V8 - the Chrome Engine at GDD 2008 in London](https://www.youtube.com/watch?v=lZnaaUoHPhs)
* [JavaScript Engines: The Good Parts™ - Mathias Bynens & Benedikt Meurer - JSConf EU 2018](https://www.youtube.com/watch?time_continue=1389&v=5nmpokoRaZI&feature=emb_logo)
* [A Tale of Types, Classes, and Maps by Benedikt Meurer · JSCamp Barcelona 2018](https://www.youtube.com/watch?time_continue=3&v=IFWulQnM5E0&feature=emb_logo)
* [Mathias Bynens - V8 internals for JavaScript developers](https://www.youtube.com/watch?time_continue=11&v=m9cTaYI95Zc&feature=emb_logo)
* [V8 and How It Listens to You](https://www.youtube.com/watch?v=u7zRSm8jzvA)
* [V8 internals for JavaScript developers](https://slidr.io/mathiasbynens/v8-internals-for-javascript-developers#1)
* [Parsing JavaScript - better lazy than eager?](https://www.youtube.com/watch?v=Fg7niTmNNLg)

## Garbage-Collection

### Article

* [A tour of V8: Garbage Collection](http://jayconrod.com/posts/55/a-tour-of-v8-garbage-collection)

  these three papers are chinese version:

  * [Node.js内存管理和V8垃圾回收机制](https://juejin.im/post/5d1b69b051882579d428d458)
  * [V8 之旅： 垃圾回收器](http://newhtml.net/v8-garbage-collection/)
  * [浅谈V8引擎中的垃圾回收机制](https://segmentfault.com/a/1190000000440270)

* [memory management](http://www.memorymanagement.org/)

* [V8 Garbage Collector](https://github.com/thlorenz/v8-perf/blob/master/gc.md#orinoco-garbage-collector)

* [JavaScript Garbage Collection Improvements - Orinoco](https://blog.risingstack.com/javascript-garbage-collection-orinoco/)

* [Jank Busters Part One](https://v8.dev/blog/jank-busters)

* [Jank Busters Part Two: Orinoco](https://v8.dev/blog/orinoco)

* [Orinoco: young generation garbage collection](https://v8.dev/blog/orinoco-parallel-scavenger)

* [Trash talk: the Orinoco garbage collector](https://v8.dev/blog/trash-talk)

### Vedio

* [Orinoco: The new V8 Garbage Collector Peter Marshall](https://www.youtube.com/watch?time_continue=14&v=Scxz6jVS4Ls&feature=emb_logo)

## CodeStubAssembler Related

### Article

* [Taming architecture complexity in V8 — the CodeStubAssembler](https://v8.dev/blog/csa)
* [CodeStubAssembler builtins](https://v8.dev/docs/csa-builtins)
* [V8 Torque user manual](https://v8.dev/docs/torque)

### Slide

* [CodeStubAssembler: Redux](https://docs.google.com/presentation/d/1u6bsgRBqyVY3RddMfF1ZaJ1hWmqHZiVMuPRw_iKpHlY/edit#slide=id.p)

## Ignition

### Article

* [Ignition](https://v8.dev/docs/ignition)
* [Firing up the Ignition interpreter](https://v8.dev/blog/ignition-interpreter)
* [Understanding V8’s Bytecode](https://medium.com/dailyjs/understanding-v8s-bytecode-317d46c94775)

### Slide

* [Ignition: An Interpreter for V8 [BlinkOn]](https://docs.google.com/presentation/d/1OqjVqRhtwlKeKfvMdX6HaCIu9wpZsrzqpIVIwQSuiXQ/edit#slide=id.ge4ef702cb_2_20)--[vedio](https://www.youtube.com/watch?v=r5OWCtuKiAk&feature=youtu.be)
* [V8: Hooking up the Ignition to the Turbofan](https://docs.google.com/presentation/d/1chhN90uB8yPaIhx_h2M3lPyxPgdPmkADqSNAoXYQiVE/edit#slide=id.g1ba7f92079_2_42)
* [Ignition: Jump-starting an Interpreter for V8](https://docs.google.com/presentation/d/1HgDDXBYqCJNasBKBDf9szap1j4q4wnSHhOYpaNy5mHU/edit#slide=id.g1453eb7f19_5_5)

### Vedio

* [BlinkOn 6 Day 1 Talk 2: Ignition - an interpreter for V8](https://www.youtube.com/watch?v=r5OWCtuKiAk&feature=youtu.be)

## IR

### Article

* [Sea of Nodes](https://darksi.de/d.sea-of-nodes/)

### Slide

* [Turbofan IR](https://docs.google.com/presentation/d/1Z9iIHojKDrXvZ27gRX51UxHD-bKf1QcPzSijntpMJBM/edit#slide=id.p)

### Paper

* [A Simple Graph-Based Intermediate Representation](https://grothoff.org/christian/teaching/2007/3353/papers/click95simple.pdf)

## TurboFan

### Article

* [turbofan-official-doc-blog](https://v8.dev/docs/turbofan)
* [Introduction to TurboFan](https://doar-e.github.io/blog/2019/01/28/introduction-to-turbofan/)
* [An Introduction to Speculative Optimization in V8](https://ponyfoo.com/articles/an-introduction-to-speculative-optimization-in-v8)
* [An internship on laziness: lazy unlinking of deoptimized functions](https://v8.dev/blog/lazy-unlinking)--[silde](https://docs.google.com/presentation/d/1AVu1wiz6Deyz1MDlhzOWZDRn6g_iFkcqsGce1F23i-M/edit#slide=id.p)
* [Ignition and TurboFan Compiler Pipeline](https://github.com/thlorenz/v8-perf/blob/master/compiler.md)
* [TurboFan Inlining Heuristics](https://docs.google.com/document/d/1VoYBhpDhJC4VlqMXCKvae-8IGuheBGxy32EOgC2LnT8/edit#heading=h.it7t22cjw7by)
* [TurboFan Inlining](https://docs.google.com/document/d/1l-oZOW3uU4kSAHccaMuUMl_RCwuQC526s0hcNVeAM1E/edit#heading=h.56xkbja466o9)

### Vedio

* [MNUG 2017.03.23 TurboFan: A new code generation architecture for V8](https://www.youtube.com/watch?v=M1FBosB5tjM)--[slide](https://docs.google.com/presentation/d/1_eLlVzcj94_G4r9j9d_Lj5HRKFnq6jgpuPJtnmIBs88/edit#slide=id.p)
* [Benedikt Meurer: A Tale of TurboFan: Four years that changed V8 forever](https://www.youtube.com/watch?v=cvybnv79Sek)--[slide](https://docs.google.com/presentation/d/1UXR1H2elTdAYJJ0Eed7lUctCVUserav9sAYSidxp8YE/edit#slide=id.p)

### Slide

* [A Tale of TurboFan-Four years that changed V8 forever](https://docs.google.com/presentation/d/1UXR1H2elTdAYJJ0Eed7lUctCVUserav9sAYSidxp8YE/edit#slide=id.p)
* [TurboFan: A new code generation architecture for V8](https://docs.google.com/presentation/d/1_eLlVzcj94_G4r9j9d_Lj5HRKFnq6jgpuPJtnmIBs88/edit#slide=id.p)
* [TurboFan JIT Design](https://docs.google.com/presentation/d/1sOEF4MlF7LeO7uq-uThJSulJlTh--wgLeaVibsbb3tc/edit#slide=id.p)
* [Deoptimization in V8](https://docs.google.com/presentation/d/1Z6oCocRASCfTqGq1GCo1jbULDGS-w-nzxkbVF7Up0u0/edit#slide=id.p)
* [An internship on laziness](https://docs.google.com/presentation/d/1AVu1wiz6Deyz1MDlhzOWZDRn6g_iFkcqsGce1F23i-M/edit#slide=id.p)

## Pwn

### Slide

* [Attacking Client-Side JIT Compilers(v2)](https://saelo.github.io/presentations/blackhat_us_18_attacking_client_side_jit_compilers.pdf)--[vedio](https://www.youtube.com/watch?v=A1FWvfkTgY4)
* [A guided tour through Chrome's javascript compiler](https://docs.google.com/presentation/d/1DJcWByz11jLoQyNhmOvkZSrkgcVhllIlCHmal1tGzaw/edit#slide=id.g52a72d9904_4_45)
* [AttackingTurboFan_TyphoonCon_2019](https://doar-e.github.io/presentations/typhooncon2019/AttackingTurboFan_TyphoonCon_2019.pdf)

### Vedio

* [Black Hat USA 2018 - Attacking Client Side JIT Compilers](https://www.youtube.com/watch?v=A1FWvfkTgY4)

### Article

* [Trashing the Flow of Data](https://googleprojectzero.blogspot.com/2019/05/trashing-flow-of-data.html)

## Tools

1. [esprima](https://github.com/jquery/esprima): tool for building JavaScript ast
2. [jit.js](https://github.com/indutny/jit.js): generate and execute machine code in JavaScript
3. [polyfill](https://github.com/inexorabletash/polyfill): A polyfill, or polyfiller, is a piece of code (or plugin) that provides the technology that you, the developer, expect the browser to provide *natively*. Flattening the API landscape if you will.

## Other

* [V8 Bug Tracker](https://bugs.chromium.org/p/chromium/issues/list)
* [Google Groups V8](https://groups.google.com/forum/#!forum/v8-users)

