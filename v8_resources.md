# v8 resources

## Total

1. [official blog](https://v8.dev/blog)
2. [v8-perf](https://github.com/thlorenz/v8-perf)
3. [learning-v8](https://github.com/danbev/learning-v8)
4. [awesome-browser-exploit](https://github.com/Escapingbug/awesome-browser-exploit)
5. [browser-pwn](https://github.com/m1ghtym0/browser-pwn)

## Fundamental

### Article

1. [JavaScript engine fundamentals: Shapes and Inline Caches](https://mathiasbynens.be/notes/shapes-ics)
2. [JavaScript engine fundamentals: optimizing prototypes](https://mathiasbynens.be/notes/prototypes#tradeoffs)
3. [What's up with monomorphism?](https://mrale.ph/blog/2015/01/11/whats-up-with-monomorphism.html)
4. [ECMA Standard](https://tc39.es/ecma262/#sec-intro)

### Vedio

1. [V8 - the Chrome Engine at GDD 2008 in London](https://www.youtube.com/watch?v=lZnaaUoHPhs)
2. [JavaScript Engines: The Good Parts™ - Mathias Bynens & Benedikt Meurer - JSConf EU 2018](https://www.youtube.com/watch?time_continue=1389&v=5nmpokoRaZI&feature=emb_logo)
3. [A Tale of Types, Classes, and Maps by Benedikt Meurer · JSCamp Barcelona 2018](https://www.youtube.com/watch?time_continue=3&v=IFWulQnM5E0&feature=emb_logo)

## Garbage-Collection

### Article

1. [A tour of V8: Garbage Collection](http://jayconrod.com/posts/55/a-tour-of-v8-garbage-collection)

    these three papers are chinese version:

    * [Node.js内存管理和V8垃圾回收机制](https://juejin.im/post/5d1b69b051882579d428d458)
    * [V8 之旅： 垃圾回收器](http://newhtml.net/v8-garbage-collection/)
    * [浅谈V8引擎中的垃圾回收机制](https://segmentfault.com/a/1190000000440270)
    
2. [memory management](http://www.memorymanagement.org/)

3. [V8 Garbage Collector](https://github.com/thlorenz/v8-perf/blob/master/gc.md#orinoco-garbage-collector)

4. [JavaScript Garbage Collection Improvements - Orinoco](https://blog.risingstack.com/javascript-garbage-collection-orinoco/)

5. [Jank Busters Part One](https://v8.dev/blog/jank-busters)

6. [Jank Busters Part Two: Orinoco](https://v8.dev/blog/orinoco)

7. [Orinoco: young generation garbage collection](https://v8.dev/blog/orinoco-parallel-scavenger)

8. [Trash talk: the Orinoco garbage collector](https://v8.dev/blog/trash-talk)

### Vedio

1. [Orinoco: The new V8 Garbage Collector Peter Marshall](https://www.youtube.com/watch?time_continue=14&v=Scxz6jVS4Ls&feature=emb_logo)

## IR

### Article

1. [Sea of Nodes](https://darksi.de/d.sea-of-nodes/)

### Sliede

1. [Turbofan IR](https://docs.google.com/presentation/d/1Z9iIHojKDrXvZ27gRX51UxHD-bKf1QcPzSijntpMJBM/edit#slide=id.p)

### Paper

1. [A Simple Graph-Based Intermediate Representation](https://grothoff.org/christian/teaching/2007/3353/papers/click95simple.pdf)

## TurboFan

### Article

1. [An Introduction to Speculative Optimization in V8](https://ponyfoo.com/articles/an-introduction-to-speculative-optimization-in-v8)
2. [An internship on laziness: lazy unlinking of deoptimized functions](https://v8.dev/blog/lazy-unlinking)--[silde 5](https://docs.google.com/presentation/d/1AVu1wiz6Deyz1MDlhzOWZDRn6g_iFkcqsGce1F23i-M/edit#slide=id.p)
3. [Ignition and TurboFan Compiler Pipeline](https://github.com/thlorenz/v8-perf/blob/master/compiler.md)

### Vedio

1. [MNUG 2017.03.23 TurboFan: A new code generation architecture for V8](https://www.youtube.com/watch?v=M1FBosB5tjM)--[slide 2](https://docs.google.com/presentation/d/1_eLlVzcj94_G4r9j9d_Lj5HRKFnq6jgpuPJtnmIBs88/edit#slide=id.p)
2. [Benedikt Meurer: A Tale of TurboFan: Four years that changed V8 forever](https://www.youtube.com/watch?v=cvybnv79Sek)--[slide 1](https://docs.google.com/presentation/d/1UXR1H2elTdAYJJ0Eed7lUctCVUserav9sAYSidxp8YE/edit#slide=id.p)

### Slide

1. [A Tale of TurboFan-Four years that changed V8 forever](https://docs.google.com/presentation/d/1UXR1H2elTdAYJJ0Eed7lUctCVUserav9sAYSidxp8YE/edit#slide=id.p)
2. [TurboFan: A new code generation architecture for V8](https://docs.google.com/presentation/d/1_eLlVzcj94_G4r9j9d_Lj5HRKFnq6jgpuPJtnmIBs88/edit#slide=id.p)
3. [TurboFan JIT Design](https://docs.google.com/presentation/d/1sOEF4MlF7LeO7uq-uThJSulJlTh--wgLeaVibsbb3tc/edit#slide=id.p)
4. [Deoptimization in V8](https://docs.google.com/presentation/d/1Z6oCocRASCfTqGq1GCo1jbULDGS-w-nzxkbVF7Up0u0/edit#slide=id.p)
5. [An internship on laziness](https://docs.google.com/presentation/d/1AVu1wiz6Deyz1MDlhzOWZDRn6g_iFkcqsGce1F23i-M/edit#slide=id.p)

## Tools

1. [esprima](https://github.com/jquery/esprima): tool for building JavaScript ast
2. [jit.js](https://github.com/indutny/jit.js): generate and execute machine code in JavaScript
3. [polyfill](https://github.com/inexorabletash/polyfill): A polyfill, or polyfiller, is a piece of code (or plugin) that provides the technology that you, the developer, expect the browser to provide *natively*. Flattening the API landscape if you will.


