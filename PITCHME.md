# RAFAŁ POCZTARSKI <br> <img src="rsp-gravatar-s800-200-bq95-circle.png"> <br> WebAssembly System Interface

---

# WebAssembly System Interface

Czyli jak WASM i WASI zmieni sposób, <br> w jaki myślimy o bezpieczeństwie aplikacji.

---

# <a class="black" href="https://pocztarski.com/">Rafał Pocztarski</a>

Możecie mnie znać ze Stack Overflow

[<img alt="rsp on Stack Overflow" src="https://stackexchange.com/users/flair/303952.png" height="116">](https://stackoverflow.com/users/613198/rsp)

# <a class="black" href="https://pocztarski.com/">pocztarski.com</a>

<small>(oraz Medium, Quora, Wikipedia, etc.)</small>

---

# Slajdy

<big><big> <a class="black" href="https://pocztarski.com/wba">pocztarski.com/wba</a> </big></big>

---

# <small>The future of computing</small>

<i class="w300">"If WASM + WASI existed in 2008, we wouldn't have needed to created Docker. That's how important it is. <b class="w900">Webassembly on the server is the future of computing.</b> A standardized system interface was the missing link. Let's hope WASI is up to the task!"</i>

<b class="w900">Solomon Hykes</b>, founder and CTO of <b class="w900">Docker</b><br><i class="w100">March, 2019 [on Twitter](https://twitter.com/solomonstre/status/1111004913222324225)</i>

---

# Rys historyczny

---

# ~2000
<small>
[MicroEssays on Capability Theory](http://cap-lore.com/)
<br><br>
[Capability Theory by Sound Bytes](http://cap-lore.com/CapTheory/)
<br><br>
[Computer Security, the Very Idea](http://cap-lore.com/Dual.html)
<br><br>
[GNOSIS - A Prototype Operating System for the 1990's](http://cap-lore.com/CapTheory/upenn/Gnosis/Gnosis.html) (1979)
<br><br>
[The KeyKOS Architecture](http://cap-lore.com/CapTheory/upenn/OSRpaper.html) (1985)
<br><br>
[KeyKOS - A Secure, High-Performance Environment for S/370 ](http://cap-lore.com/CapTheory/upenn/Key370/Key370.html) (1988)
<br><br>
[The KeyKOS Nanokernel Architecture](http://cap-lore.com/CapTheory/upenn/NanoKernel/NanoKernel.html) (1992)

<small>

---

# <small>Norman Hardy<br><small>[cap-lore.com](http://cap-lore.com/)</small></small>

# <small>Mark S. Miller<br><small>[erights.org](https://erights.org/)</small></small>

# <small>Jonathan S. Shapiro<br><small>[cs.jhu.edu/~shap](https://www.cs.jhu.edu/~shap/)</small></small>

---

<small>

# Gerald Sussman

# Hal Abelson

# Alan Kay

# David West

</small>

---

<small style="text-transform: none !important;">

# <span style="text-transform: none !important;">GNOSIS (1970s)</span>

# <span style="text-transform: none !important;">KeyKOS (1980s)</span>

# <span style="text-transform: none !important;">EROS (1990s)</span>

# <span style="text-transform: none !important;">CapROS (early 2000s)</span>

# <span style="text-transform: none !important;">Coyotos (mid 2000s)</span>

</small>

---

# JavaScript

ECMA-262

ES1 (1997)<br>
ES2 (1998)<br>
ES3 (1999)<br>
<s>ES4 (2003)</s><br>
ES5 (2009)<br>
ES6 (2015)

---

# 2009

[Changes to JavaScript, Part 1: EcmaScript 5](https://www.youtube.com/watch?v=Kq4FpMe6cRs)

---

# <small>Mark S. Miller</small>

[Remaining Hazards and Mitigating Patterns for Secure Mashups in EcmaScript 5](https://www.youtube.com/watch?v=Gpm6yVCrh0s) (2017)

[Mark Miller interview MS-Channel-9 How SES works](https://www.youtube.com/watch?v=UfsmRZi7R18) (2017)

[Securing EcmaScript, presentation to Node Security](https://www.youtube.com/watch?v=9Snbss_tawI) (2018)

[Making JavaScript Safe and Secure | Mark S. Miller from Agoric explaining SES](https://www.youtube.com/watch?v=o7xK5qxgvZM) (2019)

[SES Compartments - Mark Miller](https://www.youtube.com/watch?v=krElhDx3uig) (2020)

---

# <small>Lin Clark<br><small>[hacks.mozilla.org/author/lclarkmozilla-com](https://hacks.mozilla.org/author/lclarkmozilla-com/)</small></small>

# <small>Steve Klabnik<br><small>[steveklabnik.com](https://steveklabnik.com/)</small></small>

---

# WebAssembly

[webassembly.org](https://webassembly.org/)

[w3.org/community/webassembly](https://www.w3.org/community/webassembly/)

[webassembly.github.io/spec/core](https://webassembly.github.io/spec/core/)

---

# WASI

[https://wasi.dev/](https://wasi.dev/)

[github.com/WebAssembly/WASI](https://github.com/WebAssembly/WASI)

---

# Bytecode Alliance

[bytecodealliance.org](https://bytecodealliance.org/)

---

# TC39

Ecma International

"We develop the JavaScript (formally, ECMAScript) specification on GitHub"

[tc39.es](https://tc39.es/)

---

# W3C

[w3.org/community/webassembly](https://www.w3.org/community/webassembly/)

[webassembly.github.io/spec](https://webassembly.github.io/spec/)

[github.com/WebAssembly](https://github.com/WebAssembly)

[github.com/WebAssembly/proposals](https://github.com/WebAssembly/proposals)

---

# Artykuły
<small>
[WebAssembly Interface Types: Interoperate with All the Things!](https://hacks.mozilla.org/2019/08/webassembly-interface-types/)<br>by Lin Clark, Mozilla Hacks, 2019
<br><br>
[Standardizing WASI: A system interface to run WebAssembly outside the web](https://hacks.mozilla.org/2019/03/standardizing-wasi-a-webassembly-system-interface/)<br>by Lin Clark, Mozilla Hacks, 2019
<br><br>
[Announcing the Bytecode Alliance: Building a secure by default, composable future for WebAssembly](https://hacks.mozilla.org/2019/11/announcing-the-bytecode-alliance/)<br>by Lin Clark, Mozilla Hacks, 2019
<br><br>
[Understanding WebAssembly text format](https://developer.mozilla.org/en-US/docs/WebAssembly/Understanding_the_text_format) on MDN
<br><br>
[Writing WebAssembly By Hand](https://blog.scottlogic.com/2018/04/26/webassembly-by-hand.html) by Colin Eberhardt
<br><br>
[WebAssembly Text Format](https://webassembly.org/docs/text-format/) in WebAssembly docs

</small>

---

# Wykłady
<small>
[From Electron, to Wasm, to Rust (Aaand Back to Electron)](https://www.youtube.com/watch?v=lLzFJenzBng) by Irina Shestak, RustConf 2019
<br><br>
[WebAssembly for Web Developers](https://www.youtube.com/watch?v=njt-Qzw0mVY) by Surma Surma and Deepti Gandluri, Google I/O 2019
<br><br>
[HTTP/3 - HTTP over QUIC is the next generation](https://www.youtube.com/watch?v=idViw4anA6E) by Daniel Stenberg, Full Stack Fest 2019
<br><br>
[Bringing WebAssembly outside the web with WASI](https://www.youtube.com/watch?v=fh9WXPu0hw8) by Lin Clark, Full Stack Fest 2019
<br><br>
[WebAssembly on the Server](https://www.youtube.com/watch?v=A9SydP1CcZU) by Zack Bloom, Cloudflare 2019

</small>

---

# Więcej wykładów
<small>
[Build the future of the web with WebAssembly and more](https://www.youtube.com/watch?v=BnYq7JapeDA), Google I/O 2018
<br><br>
[Speed, Speed, Speed: JavaScript vs C++ vs WebAssembly](https://www.youtube.com/watch?v=uMuYaES4W3o) by Franziska Hinkelmann, CovalenceConf 2019
<br><br>
[WebAssembly beyond the Web](https://www.youtube.com/watch?v=YhNkspvw37w) by Lin Clark and Till Schneidereit, WebAssembly Munich Meetup 2019
(slabsze)
<br><br>
[An Introduction to WebAssembly](https://www.youtube.com/watch?v=vChLD1VytOE) by Guy Royse, Devoxx Belgium 2019
technical
<br><br>
[Wasm The Future](https://www.youtube.com/watch?v=G-ThBWLxwuA) by Alex Danilo, Melbourne GDG Devfest 2018
technical

</small>

---

# WASM + nie-JS
<small>
[Rust, WebAssembly, and the future of Serverless](https://www.youtube.com/watch?v=CMB6AlE1QuI) by Steve Klabnik, Full Stack Fest 2019
<br><br>
[SPA Revolution with WebAssembly and ASP.NET Blazor](https://www.youtube.com/watch?v=kTBW94GcRJY) by Rainer Stropek, TechDays Stockholm 2019
<br><br>
[WASM: Bringing Go to the Browser (and Beyond!)](https://www.youtube.com/watch?v=oVzFNktAkvA) by Gabbi Fisher, GothamGo 2019
<br><br>
[WASM matter?](https://www.youtube.com/watch?v=eJMT1aImS9Q) by Russell Keith-Magee, PyCon AU 2019)

</small>

---

# DENO

[deno.land](https://deno.land/)

[github.com/denoland/deno](https://github.com/denoland/deno)

---

# JavaScript

`[1, 1, 1].map(parseInt)`

[tc39.es](https://tc39.es/)

[github.com/tc39](https://github.com/tc39)

</small>

---

# TypeScript

`[1, 1, 1].map(parseInt) as any`

[typescriptlang.org](https://www.typescriptlang.org/)

[github.com/microsoft/TypeScript](https://github.com/microsoft/TypeScript)

---

# AssemblyScript

`store<i32>(offset + ((width * y + x) << 2), ~vi << 24 | vi << 8);`

[assemblyscript.org](https://www.assemblyscript.org/)

[github.com/AssemblyScript](https://github.com/AssemblyScript)

---

# Rust

[rust-lang.org](https://www.rust-lang.org/)

[github.com/rust-lang](https://github.com/rust-lang/rust)

---

# C / C++

[emscripten.org](https://emscripten.org/)

[github.com/emscripten-core](https://github.com/emscripten-core)

---

# Languages<small><br>compiled to WebAssembly</small>

<small>
<span class="egg"><s>Unmaintained</s></span>,
<span class="egg">Work in progress</span>,
<span class="hatching_chick">Unstable but usable</span>,
<span class="hatched_chick">Stable for production usage</span>:
<br><br>
<span class="hatched_chick">.Net</span>,
<span class="hatched_chick">AssemblyScript</span>,
<span class="egg">Astro</span>,
<span class="hatched_chick">Brainfuck</span>,
<span class="hatched_chick">C</span>,
<span class="hatched_chick">C#</span>,
<span class="hatched_chick">C++</span>,
<span class="hatched_chick">Clean</span>,
<span class="egg">Co</span>,
<span class="hatched_chick">COBOL</span>,
<span class="hatching_chick">D</span>,
<span class="hatching_chick">Eel</span>,
<span class="hatching_chick">Elixir</span>,
<span class="hatching_chick">F#</span>,
<span class="egg">Faust</span>,
<span class="egg">Forest</span>,
<span class="hatched_chick">Forth</span>,
<span class="hatched_chick">Go</span>,
<span class="egg">Grain</span>,
<span class="egg">Haskell</span>,
<span class="hatching_chick">Java</span>,
<span class="hatching_chick">JavaScript</span>,
<span class="egg">Julia</span>,
<span class="hatching_chick">Idris</span>,
<span class="hatching_chick">Kotlin/Native</span>,
<span class="egg">Kou</span>,
<span class="hatched_chick">Lobster</span>,
<span class="hatched_chick">Lua</span>,
<span class="hatching_chick">Lys</span>,
<span class="hatched_chick">Never</span>,
<span class="egg">Nim</span>,
<span class="egg">Ocaml</span>,
<span class="hatching_chick">Perl</span>,
<span class="hatching_chick">PHP</span>,
<span class="egg">Plorth</span>,
<span class="hatching_chick">Poetry</span>,
<span class="hatching_chick">Python</span>,
<span class="hatching_chick">Prolog</span>,
<span class="hatching_chick">Ruby</span>,
<span class="hatched_chick">Rust</span>,
<span class="hatching_chick">Scheme</span>,
<span class="hatching_chick">Scopes</span>,
<span class="hatching_chick"><s>Speedy.js</s></span>,
<span class="hatching_chick">Swift</span>,
<span class="hatching_chick"><s>Turboscript</s></span>,
<span class="hatched_chick">TypeScript</span>,
<span class="hatched_chick">Wah</span>,
<span class="hatching_chick">Walt</span>,
<span class="hatching_chick">Wam</span>,
<span class="egg"><s>Wracket</s></span>,
<span class="hatched_chick">Zig</span>.
<br><br>
Source: [Awesome WebAssembly Languages](https://github.com/appcypher/awesome-wasm-langs)

</small>

---

# WASM Playgrounds

[ast.run](http://ast.run/)

[webassembly.studio](https://webassembly.studio/)
<!-- [WasmExplorer](https://mbebenita.github.io/WasmExplorer/) -->

---

# RAFAŁ POCZTARSKI

<!-- <small> -->

  <a class="black" href="https://twitter.com/pocztarski" target="_blank"><i class="fab fa-twitter"></i> Twitter: @pocztarski</a>
<br>
  <a class="black" href="https://medium.com/@pocztarski" target="_blank"><i class="fab fa-medium-m"></i> Medium: @pocztarski</a>
<br>
  <a class="black" href="https://www.facebook.com/pocztarski" target="_blank"><i class="fab fa-facebook-f"></i> Facebook: @pocztarski</a>
<br>
  <a class="black" href="https://angel.co/pocztarski" target="_blank"><i class="fab fa-angellist"></i> AngelList: @pocztarski</a>
<br>
  <a class="black" href="https://www.linkedin.com/in/pocztarski" target="_blank"><i class="fab fa-linkedin"></i> LinkedIn: @pocztarski</a>
<br>
  <a class="black" href="https://stackoverflow.com/users/613198/rsp" target="_blank"><i class="fab fa-stack-overflow"></i> Stack Overflow: rsp</a>
<br>
  <a class="black" href="https://crossweb.pl/en/profile/rafal-pocztarski/29326/" target="_blank"><i class="fas fa-hand-point-right"></i> Crossweb: 29326</a>
<br>
  <a class="black" href="https://github.com/rsp" target="_blank"><i class="fab fa-github"></i> GitHub: rsp</a>

<!-- </small> -->





Slajdy: <a class="black" href="https://pocztarski.com/wba">pocztarski.com/wba</a>

## <a class="black" href="https://pocztarski.com/">Rafał Pocztarski</a>

## <a class="black" href="https://pocztarski.com/">pocztarski.com</a>
