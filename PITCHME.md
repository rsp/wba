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

<i>"If WASM + WASI existed in 2008, we wouldn't have needed to created Docker. That's how important it is. Webassembly on the server is the future of computing. A standardized system interface was the missing link. Let's hope WASI is up to the task!"</i>

<b>Solomon Hykes</b>, founder and CTO of <b>Docker</b><br>March, 2019 [on Twitter](https://twitter.com/solomonstre/status/1111004913222324225)

---

# Rys historyczny

---

# <small>2000</small>

<ul>
<li>[MicroEssays on Capability Theory](http://cap-lore.com/)
<li> [Capability Theory by Sound Bytes](http://cap-lore.com/CapTheory/)
<li> [Computer Security, the Very Idea](http://cap-lore.com/Dual.html)
<li> [GNOSIS - A Prototype Operating System for the 1990's](http://cap-lore.com/CapTheory/upenn/Gnosis/Gnosis.html) (1979)
<li> [The KeyKOS Architecture](http://cap-lore.com/CapTheory/upenn/OSRpaper.html) (1985)
<li> [KeyKOS - A Secure, High-Performance Environment for S/370 ](http://cap-lore.com/CapTheory/upenn/Key370/Key370.html) (1988)
<li> [The KeyKOS Nanokernel Architecture](http://cap-lore.com/CapTheory/upenn/NanoKernel/NanoKernel.html) (1992)
</ul>

---

# <small>Norman Hardy<br><small>[cap-lore.com](http://cap-lore.com/)</small></small>

# <small>Mark S. Miller<br><small>[erights.org](https://erights.org/)</small></small>

# <small>Jonathan S. Shapiro<br><small>[cs.jhu.edu/~shap](https://www.cs.jhu.edu/~shap/)</small></small>

---

# 2009

[Changes to JavaScript, Part 1: EcmaScript 5](https://www.youtube.com/watch?v=Kq4FpMe6cRs)

---

# Mark S. Miller

<ul>
<li>[Remaining Hazards and Mitigating Patterns for Secure Mashups in EcmaScript 5](https://www.youtube.com/watch?v=Gpm6yVCrh0s) (2017)
<li>[Mark Miller interview MS-Channel-9 How SES works](https://www.youtube.com/watch?v=UfsmRZi7R18) (2017)
<li>[Securing EcmaScript, presentation to Node Security](https://www.youtube.com/watch?v=9Snbss_tawI) (2018)
<li>[Making JavaScript Safe and Secure | Mark S. Miller from Agoric explaining SES](https://www.youtube.com/watch?v=o7xK5qxgvZM) (2019)
<li>[SES Compartments - Mark Miller](https://www.youtube.com/watch?v=krElhDx3uig) (2020)
</ul>

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

- [w3.org/community/webassembly](https://www.w3.org/community/webassembly/)
- [webassembly.github.io/spec](https://webassembly.github.io/spec/)
- [github.com/WebAssembly](https://github.com/WebAssembly)
- [github.com/WebAssembly/proposals](https://github.com/WebAssembly/proposals)

---

Artykuły

<small>

[WebAssembly Interface Types: Interoperate with All the Things!](https://hacks.mozilla.org/2019/08/webassembly-interface-types/)<br>by Lin Clark, Mozilla Hacks, 2019

[Standardizing WASI: A system interface to run WebAssembly outside the web](https://hacks.mozilla.org/2019/03/standardizing-wasi-a-webassembly-system-interface/)<br>by Lin Clark, Mozilla Hacks, 2019

[Announcing the Bytecode Alliance: Building a secure by default, composable future for WebAssembly](https://hacks.mozilla.org/2019/11/announcing-the-bytecode-alliance/)<br>by Lin Clark, Mozilla Hacks, 2019

[Understanding WebAssembly text format](https://developer.mozilla.org/en-US/docs/WebAssembly/Understanding_the_text_format) on MDN

[Writing WebAssembly By Hand](https://blog.scottlogic.com/2018/04/26/webassembly-by-hand.html) by Colin Eberhardt

[WebAssembly Text Format](https://webassembly.org/docs/text-format/) in WebAssembly docs

</small>

---

Wykłady

<small>

[From Electron, to Wasm, to Rust (Aaand Back to Electron)](https://www.youtube.com/watch?v=lLzFJenzBng) by Irina Shestak, RustConf 2019

[WebAssembly for Web Developers](https://www.youtube.com/watch?v=njt-Qzw0mVY) by Surma Surma and Deepti Gandluri, Google I/O 2019

[HTTP/3 - HTTP over QUIC is the next generation](https://www.youtube.com/watch?v=idViw4anA6E) by Daniel Stenberg, Full Stack Fest 2019

[Bringing WebAssembly outside the web with WASI](https://www.youtube.com/watch?v=fh9WXPu0hw8) by Lin Clark, Full Stack Fest 2019

[WebAssembly on the Server](https://www.youtube.com/watch?v=A9SydP1CcZU) by Zack Bloom, Cloudflare 2019

---

Więcej wykładów

<small>

[Build the future of the web with WebAssembly and more](https://www.youtube.com/watch?v=BnYq7JapeDA), Google I/O 2018

[Speed, Speed, Speed: JavaScript vs C++ vs WebAssembly](https://www.youtube.com/watch?v=uMuYaES4W3o) by Franziska Hinkelmann, CovalenceConf 2019

[WebAssembly beyond the Web](https://www.youtube.com/watch?v=YhNkspvw37w) by Lin Clark and Till Schneidereit, WebAssembly Munich Meetup 2019
(slabsze)

[An Introduction to WebAssembly](https://www.youtube.com/watch?v=vChLD1VytOE) by Guy Royse, Devoxx Belgium 2019
technical

[Wasm The Future](https://www.youtube.com/watch?v=G-ThBWLxwuA) by Alex Danilo, Melbourne GDG Devfest 2018
technical

</small>

---

# WASM + nie-JS

Wykłady:

- [Rust, WebAssembly, and the future of Serverless](https://www.youtube.com/watch?v=CMB6AlE1QuI) by Steve Klabnik, Full Stack Fest 2019
- [SPA Revolution with WebAssembly and ASP.NET Blazor](https://www.youtube.com/watch?v=kTBW94GcRJY) by Rainer Stropek, TechDays Stockholm 2019
- [WASM: Bringing Go to the Browser (and Beyond!)](https://www.youtube.com/watch?v=oVzFNktAkvA) by Gabbi Fisher, GothamGo 2019
- [WASM matter?](https://www.youtube.com/watch?v=eJMT1aImS9Q) by Russell Keith-Magee, PyCon AU 2019)

---

`[1, 1, 1].map(parseInt)`

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
