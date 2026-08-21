# Burin Choomnuan

**Senior Principal Engineer at NewsCorp Australia — ClojureDart, AI, full-stack.**

Two decades in software, and I have moved with the landscape: Java → Ruby → Clojure →
ClojureScript → and most recently ClojureDart for mobile and desktop. Over the past year
a tiny team and I have shipped a fleet of production ClojureDart apps for iOS, Android
and macOS, alongside Clojure backends and ClojureScript SPAs that share a single mental
model end to end.

My current interest is where functional programming meets AI-assisted development:
building maintainable agentic workflows in Clojure, and sharing the patterns and pitfalls
a small team learns by shipping at pace. When I'm not coding I'm writing experience
reports for developers who appreciate the art of elegant, productive engineering.

🗣️ **Speaking at [Clojure/Conj 2026](https://2026.clojure-conj.org/speakers)** — and
generally available to talk about ClojureDart, MCP/agent tooling, and using LLMs in real
engineering workflows. [Get in touch](https://linkedin.com/in/burinc).

[![Website](https://img.shields.io/badge/blog-b12n.net-2e6176?style=flat-square)](https://b12n.net)
[![Articles](https://img.shields.io/badge/Clojure_Civitas-11_articles-aadd52?style=flat-square)](https://clojurecivitas.org/Burin_Choomnuan.html)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-burinc-0a66c2?style=flat-square)](https://linkedin.com/in/burinc)
[![X](https://img.shields.io/badge/X-@agilecreativity-000?style=flat-square)](https://x.com/agilecreativity)

---

## 🎤 Speaking

### 🔜 [Clojure/Conj 2026](https://2026.clojure-conj.org/speakers) — Charlotte, NC
**Production ClojureDart for iOS, Android, and macOS**
📅 Friday, October 2 · 9:30–10:10 AM · Room W207CD

> Over the past twelve months a tiny team has used ClojureDart (Clojure compiled to Dart,
> running on Flutter) to build more than a dozen production apps — a document scanner with
> on-device OpenCV, a transit tracker with realtime GTFS, a venture-capital deck triager
> with on-device LLM evaluation, a notes app with on-device sentence embeddings, a
> marketplace, an encyclopedia, a financial charting app, and more. This experience report
> distills the patterns that survived the trip from prototype to production: a
> single-atom-plus-`:watch` architecture that replaces Riverpod and BLoC, a curated catalog
> of cljd-flutter pitfalls, and a reusable scaffold for new apps.

*My second year on the Conj stage.*

### 📺 [Clojure/Conj 2025](https://www.youtube.com/watch?v=jWkEKdp0gqk) — Charlotte, NC · Nov 2025
**From Scripts to Buy-In: How Small Clojure Wins Create Big Opportunities**

> How small, high-impact Clojure automation — AWS workflows, replacing clunky Postman
> processes, automating Okta SSO — builds the credibility that earns you bigger Clojure
> opportunities at work.

**[▶ Watch the talk](https://www.youtube.com/watch?v=jWkEKdp0gqk)** ·
[📝 My recap from Charlotte](https://www.linkedin.com/feed/update/urn:li:activity:7395774856686030848/)

### Meetups

| Talk | Venue | Date |
|---|---|---|
| **[raylib, driven from Lisp](https://www.02ship.com/blog/02ship-sydney-meetup-august-11-recap)**<br/><sub>Open-mic demo of raylib — a C game library — driven from [Jolt](https://github.com/jolt-lang/jolt), native Clojure on Chez Scheme, plus the screen-capture and UI-automation tooling built to record demo GIFs instead of testing by hand. The raylib suite is now [b12n-raylib-jlt](https://github.com/burinc/b12n-raylib-jlt), with [jank](https://github.com/burinc/b12n-raylib-jnk) and [JVM](https://github.com/burinc/b12n-raylib-clj) siblings since; the capture tooling is still unreleased.</sub> | 02Ship Sydney Meetup<br/><sub>Level 2, 63 Dixon St, Haymarket</sub> | Aug 2026 |
| **[Three lenses, one mess: logic programming for the rest of us](https://www.linkedin.com/feed/update/urn:li:activity:7473516198232547329/)**<br/><sub>One RBAC authorization bug through three lenses, all in plain Clojure data — Prolog for role inheritance, Z3/SMT-LIB for conflicting constraints, a Mermaid-to-Prolog translation for reachability. Live REPL demo, closing on exposing solvers as LLM tools over MCP, where not hallucinating is the whole advantage.</sub> | FP-SYD<br/><sub>Microsoft, North Sydney</sub> | Jun 2026 |
| **[Supercharging Lisp with AI: Rapid Feedback Loops with Clojure and Claude Code](https://luma.com/yt0jierk)**<br/><sub>Lightning talk to a room of 100+ builders. The demo ran on [ClojureDart](https://github.com/Tensegritics/ClojureDart) — Clojure compiled to Dart on Flutter — with a live REPL plugged straight into the running widget tree. That's the loop that lets Claude Code edit, hot-reload and assert against live UI in milliseconds instead of minutes.</sub> | AI SYD<br/><sub>Vercel × Relevance AI, Surry Hills</sub> | Apr 2026 |
| **The Anthropic Claude Ecosystem**<br/><sub>66 slides end to end: `~/.claude` as a personal AI config layer, Claude Code across CLI/IDE/desktop/CI, the agentic loop, MCP hosts and servers, and Agent Skills' three-level progressive disclosure. 📊 [Slides](https://b12n.net/slides/?pres=mastering-claude-code&slide=1) · [PDF](https://github.com/burinc/presentations/blob/main/20260223-vibe-code-meetup/mastering-claude-code-vibe-code-meetup.pdf)</sub> | Vibe Code Meetup<br/><sub>Sydney</sub> | Feb 2026 |
| **Clojure for Java Developers — Building MCP Servers Without the Java Pain**<br/><sub>Cut a 350+ line Spring AI MCP server with 15+ annotations down to 180 lines with zero annotations, keeping full enterprise capability.</sub> | Sydney JVM Community<br/><sub>Canva HQ, Sydney</sub> | Jul 2025 |
| **Clojure for the Type-Loving Functional Programmer**<br/><sub>What Clojure offers a typed-FP audience, beyond the dynamic typing and the parens.</sub> | FP-SYD | Jul 2025 |
| **[Java/Spring Boot Troubleshooting on Steroids with Clojure REPL](https://github.com/SydneyJavaMeetup/meetup-22-spring-ai-debugging)**<br/><sub>Debugging Spring Boot from a Clojure REPL, set directly against traditional remote debugging in IntelliJ. Live coding on a sample app: debug, explore and modify at runtime with no restart and no redeploy.</sub> | Sydney Java Meetup #22<br/><sub>Infomedia, Sydney</sub> | Mar 2025 |
| **Bridging Two Worlds — Leveraging Lisp-like Tools to Work with Python**<br/><sub>Scripting, extending and manipulating Python from Clojure with Basilisp and libpython-clj.</sub> | SYDJANGO | Dec 2024 |
| **Overview of Clojure for FP**<br/><sub>Live demos: libpython-clj via OpenCV, GraalVM via Babashka, AWS automation with the Cognitect AWS library, `whisper.clj` transcription, plus Rama and Jank.</sub> | FP-SYD | Aug 2024 |

### 🎙️ Interview

**[Clojure Corner — Interview with Burin Choomnuan](https://youtu.be/bQSQua46cdc)** ·
Flexiana — on Clojure, tooling, and building things in the open.

### 🤝 Community

I co-host **[Gen AI Enthusiasts (AI Users)](https://www.meetup.com/genai_enthusiasts_aiusers-online/)**,
a 2,000+ member online generative-AI community running fortnightly sessions on prompt
engineering, AI tooling and news, and practical LLM use.

---

## ✍️ Writing

I write at **[Clojure Civitas](https://clojurecivitas.org/Burin_Choomnuan.html)** —
11 articles, mostly browser-native ClojureScript with [Scittle](https://github.com/babashka/scittle):

| Article | Date |
|---|---|
| [Making Fun Games with Clojure + Raylib](https://clojurecivitas.org/scicloj/clojure_jam/proposal/games_with_clojure.html) | Feb 2026 |
| [Clojure Conj 2025 — Two Lies and a Truth Trivia](https://clojurecivitas.org/scittle/conj_2025/trivia_slideshow.html) | Nov 2025 |
| [Browser-Native PDF Viewer with ClojureScript & Scittle](https://clojurecivitas.org/scittle/pdf/pdf_viewer.html) | Nov 2025 |
| [Web Audio API Playground with ClojureScript & Scittle](https://clojurecivitas.org/scittle/audio/audio_playground.html) | Nov 2025 |
| [Build Galaga with ClojureScript & Scittle](https://clojurecivitas.org/scittle/games/galaga.html) | Nov 2025 |
| [Build Asteroids with ClojureScript & Scittle](https://clojurecivitas.org/scittle/games/asteroids_article.html) | Nov 2025 |
| [Build a Memory Game with ClojureScript & Scittle](https://clojurecivitas.org/scittle/games/memory_game_article.html) | Nov 2025 |
| [Browser-Native QR Code Scanner with Scittle](https://clojurecivitas.org/scittle/qrcode/qr_code_scanner.html) | Nov 2025 |
| [Free Weather Data with the National Weather Service API](https://clojurecivitas.org/scittle/weather/weather_nws_integration.html) | Nov 2025 |
| [Python + ClojureScript: Pyodide Integration with Scittle](https://clojurecivitas.org/scittle/pyodide/pyodide_integration.html) | Nov 2025 |
| [Building Browser-Native Presentations with Scittle](https://clojurecivitas.org/scittle/presentations/browser_native_slides.html) | Nov 2025 |

Plus **[b12n.net](https://b12n.net)** ("Lisp's Revenge"), my own blog — built with
Clojure/Cryogen — where I keep browser-native slide decks:
[Mastering Claude Code](https://b12n.net/slides/?pres=mastering-claude-code&slide=1) ·
[Diagrams as Text](https://b12n.net/slides/?pres=mermaid-diagrams&slide=1)

---

## 🛠️ What I build

**ClojureDart in production.** More than a dozen apps for iOS, Android and macOS in the
past year — on-device OpenCV document scanning, realtime GTFS transit tracking, on-device
LLM evaluation and sentence embeddings, charting, marketplaces. Most deployed internally,
several bound for the app stores. That's the
[Conj 2026 talk](https://2026.clojure-conj.org/speakers).

**Lisp beyond the JVM.** Two suites of [raylib](https://www.raylib.com/) demos written in
two different native Clojures — no JVM in either — each reaching the same C game library
the way its own host actually allows.

[**b12n-raylib-jlt**](https://github.com/burinc/b12n-raylib-jlt) — 75 examples in
[Jolt](https://github.com/jolt-lang/jolt), native Clojure on Chez Scheme. They call the
real `libraylib` directly over its C ABI through `jolt.ffi`: no wrapper library, no
codegen, no C shim. 10 games, 12 in 3D, 32 shapes, 7 generative.
📖 [Docs & full gallery](https://raylib-jlt.b12n.app/)

<table>
<tr>
<td align="center"><img src="https://raw.githubusercontent.com/burinc/b12n-raylib-jlt/main/docs/demos/tetris.gif" width="240" alt="Tetris"><br><sub><code>bb tetris</code></sub></td>
<td align="center"><img src="https://raw.githubusercontent.com/burinc/b12n-raylib-jlt/main/docs/demos/space-invaders.gif" width="240" alt="Space Invaders"><br><sub><code>bb space-invaders</code></sub></td>
<td align="center"><img src="https://raw.githubusercontent.com/burinc/b12n-raylib-jlt/main/docs/demos/boids.gif" width="240" alt="Boids flocking"><br><sub><code>bb boids</code></sub></td>
</tr>
<tr>
<td align="center"><img src="https://raw.githubusercontent.com/burinc/b12n-raylib-jlt/main/docs/demos/waving-cubes.gif" width="240" alt="Waving cubes in 3D"><br><sub><code>bb waving-cubes</code></sub></td>
<td align="center"><img src="https://raw.githubusercontent.com/burinc/b12n-raylib-jlt/main/docs/demos/point-cloud.gif" width="240" alt="Rotating point cloud"><br><sub><code>bb point-cloud</code></sub></td>
<td align="center"><img src="https://raw.githubusercontent.com/burinc/b12n-raylib-jlt/main/docs/demos/rlgl-solar-system.gif" width="240" alt="Solar system in rlgl"><br><sub><code>bb rlgl-solar-system</code></sub></td>
</tr>
</table>

> The interesting part is the ABI. raylib passes structs *by value* everywhere and Chez's
> `foreign-procedure` cannot, so each struct gets the treatment its size actually earns:
> `Color` rides in one register as a packed `:uint`, `Camera2D`/`Camera3D` go by pointer,
> and `Vector2`/`Vector3` geometry is drawn through rlgl's scalar immediate mode.

[**b12n-raylib-jnk**](https://github.com/burinc/b12n-raylib-jnk) — 209 of the 217 *official*
raylib examples, ported to [jank](https://jank-lang.org): Clojure compiled to a real native
binary through C++/LLVM. The `shapes`, `shaders`, `audio` and `text` categories are complete.
📖 [Docs & full gallery](https://raylib-jnk.b12n.app/)

<table>
<tr>
<td align="center"><img src="https://raw.githubusercontent.com/burinc/b12n-raylib-jnk/main/docs/demos/basic-pbr.gif" width="240" alt="Physically based rendering"><br><sub><code>bb basic-pbr</code></sub></td>
<td align="center"><img src="https://raw.githubusercontent.com/burinc/b12n-raylib-jnk/main/docs/demos/magnifying-glass.gif" width="240" alt="Magnifying glass over a texture"><br><sub><code>bb magnifying-glass</code></sub></td>
<td align="center"><img src="https://raw.githubusercontent.com/burinc/b12n-raylib-jnk/main/docs/demos/cel-shading.gif" width="240" alt="Cel-shaded model"><br><sub><code>bb cel-shading</code></sub></td>
</tr>
<tr>
<td align="center"><img src="https://raw.githubusercontent.com/burinc/b12n-raylib-jnk/main/docs/demos/shadowmap-rendering.gif" width="240" alt="Real-time shadow mapping"><br><sub><code>bb shadowmap-rendering</code></sub></td>
<td align="center"><img src="https://raw.githubusercontent.com/burinc/b12n-raylib-jnk/main/docs/demos/spectrum-visualizer.gif" width="240" alt="Audio spectrum visualizer"><br><sub><code>bb spectrum-visualizer</code></sub></td>
<td align="center"><img src="https://raw.githubusercontent.com/burinc/b12n-raylib-jnk/main/docs/demos/animation-blending.gif" width="240" alt="Skeletal animation blending"><br><sub><code>bb animation-blending</code></sub></td>
</tr>
</table>

> Here there is no FFI at all. `(:include "raylib.h")` in the `ns` form hands the real header
> to the C++ compiler, and raylib becomes ordinary interop — `cpp/BeginDrawing`,
> `cpp/RAYWHITE`, `(cpp/Camera3D (cpp/Vector3 ...) ...)`. The by-value structs that cost Jolt
> a hand-written marshalling strategy are just constructor calls. No binding DSL, no
> generated shim.

[**b12n-raylib-clj**](https://github.com/burinc/b12n-raylib-clj) — 78 examples in JVM
Clojure, over [coffi](https://github.com/IGJoshua/coffi) and JDK 22+'s Panama Foreign
Function &amp; Memory API. 23 core, 21 in 3D, 15 shapes, 9 games, plus audio, text,
textures and shaders.
📖 [Docs &amp; full gallery](https://raylib-clj.b12n.app/)

<table>
<tr>
<td align="center"><img src="https://raw.githubusercontent.com/burinc/b12n-raylib-clj/main/docs/demos/tetris.gif" width="240" alt="Tetris"><br><sub><code>bb tetris</code></sub></td>
<td align="center"><img src="https://raw.githubusercontent.com/burinc/b12n-raylib-clj/main/docs/demos/asteroids.gif" width="240" alt="Asteroids"><br><sub><code>bb asteroids</code></sub></td>
<td align="center"><img src="https://raw.githubusercontent.com/burinc/b12n-raylib-clj/main/docs/demos/background-scrolling.gif" width="240" alt="Parallax background scrolling"><br><sub><code>bb background-scrolling</code></sub></td>
</tr>
<tr>
<td align="center"><img src="https://raw.githubusercontent.com/burinc/b12n-raylib-clj/main/docs/demos/basic-lighting.gif" width="240" alt="Shader-based dynamic lighting"><br><sub><code>bb basic-lighting</code></sub></td>
<td align="center"><img src="https://raw.githubusercontent.com/burinc/b12n-raylib-clj/main/docs/demos/solar-system.gif" width="240" alt="Orbiting solar system in 3D"><br><sub><code>bb solar-system</code></sub></td>
<td align="center"><img src="https://raw.githubusercontent.com/burinc/b12n-raylib-clj/main/docs/demos/lorenz-attractor.gif" width="240" alt="Lorenz attractor"><br><sub><code>bb lorenz-attractor</code></sub></td>
</tr>
</table>

> This is the one where the runtime does the marshalling for you. A binding is a single
> `defcfn` naming the C symbol and its types, and Panama builds the downcall from that
> description — so the by-value `Color` that Jolt hand-packs into a `:uint` is just a
> `{:r 255 :g 0 :b 0 :a 255}` map here, serialized from a `defalias` layout. The seam
> shows where raylib mutates through a pointer: those calls allocate in a
> `confined-arena`, and the arena's lifetime is the one thing the abstraction will not
> hide from you.

Three hosts, one C library: Chez Scheme, C++/LLVM, and the JVM — reading the same example
three ways is the clearest map I know of where each runtime puts the boundary.

**Clojure meets AI.** Agentic workflows, MCP servers, and LLM-driven developer tooling are
where most of my time goes now. A lot of that work is private for the moment — so the
patterns tend to surface in talks and articles before the code does.

**Public bits:** [b12n-raylib-jlt](https://github.com/burinc/b12n-raylib-jlt) · [b12n-raylib-jnk](https://github.com/burinc/b12n-raylib-jnk) · [b12n-raylib-clj](https://github.com/burinc/b12n-raylib-clj) ·
[dartclojure.el](https://github.com/burinc/dartclojure.el)
(Dart/Flutter → ClojureDart, in Emacs) · [viip](https://github.com/burinc/viip) ·
[Clojars](https://clojars.org/users/agilecreativity) ·
[RubyGems](https://rubygems.org/profiles/agilecreativity)

---

## 🌱 Open source

Contributions to [babashka/process](https://github.com/babashka/process/commits?author=agilecreativity),
[bhauman/clojure-mcp](https://github.com/bhauman/clojure-mcp/commits?author=burinc),
[zero-one-group/geni](https://github.com/zero-one-group/geni/commits?author=agilecreativity),
[BrunoBonacci/graalvm-clojure](https://github.com/BrunoBonacci/graalvm-clojure/commits?author=agilecreativity),
[yogthos/Selmer](https://github.com/yogthos/Selmer/commits?author=agilecreativity),
[clojure-emacs/clomacs](https://github.com/clojure-emacs/clomacs/commits?author=agilecreativity),
[dundalek/closh](https://github.com/dundalek/closh/commits?author=agilecreativity),
[juxt/mach](https://github.com/juxt/mach/commits?author=agilecreativity),
[apache/incubator-mxnet](https://github.com/apache/incubator-mxnet/commits?author=agilecreativity),
and [others](https://github.com/agilecreativity).

> 📌 **Two handles, one person.** [@agilecreativity](https://github.com/agilecreativity)
> is my original account, from before I found Clojure — a lot of my older OSS commits live
> there. [@burinc](https://github.com/burinc) is where I work now.

---

## 📫 Elsewhere

| | |
|---|---|
| 🌐 Blog | [b12n.net](https://b12n.net) |
| 💼 LinkedIn | [in/burinc](https://linkedin.com/in/burinc) |
| 🐦 X | [@agilecreativity](https://x.com/agilecreativity) |
| ✍️ Articles | [Clojure Civitas](https://clojurecivitas.org/Burin_Choomnuan.html) |
| 🐙 GitHub | [@burinc](https://github.com/burinc) · [@agilecreativity](https://github.com/agilecreativity) |

<sub>Lisp · Clojure · ClojureDart · Emacs · and a stubborn belief that small tools compound.</sub>
