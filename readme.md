# Burin Choomnuan

**Senior Principal Engineer at NewsCorp Australia: ClojureDart, AI, full-stack.**

Two decades in software, and I have moved with the landscape: Java → Ruby → Clojure →
ClojureScript → and most recently ClojureDart for mobile and desktop. Over the past year
a tiny team and I have shipped a fleet of production ClojureDart apps for iOS, Android
and macOS, alongside Clojure backends and ClojureScript SPAs that share a single mental
model end to end.

My current interest is where functional programming meets AI-assisted development:
building maintainable agentic workflows in Clojure, and sharing the patterns and pitfalls
a small team learns by shipping at pace. When I'm not coding I'm writing experience
reports for developers who appreciate the art of elegant, productive engineering.

🗣️ **Speaking at [Clojure/Conj 2026](https://2026.clojure-conj.org/speakers)**, and
generally available to talk about ClojureDart, MCP/agent tooling, and using LLMs in real
engineering workflows. [Get in touch](https://linkedin.com/in/burinc).

[![Website](https://img.shields.io/badge/blog-b12n.net-2e6176?style=flat-square)](https://b12n.net)
[![Articles](https://img.shields.io/badge/Clojure_Civitas-11_articles-aadd52?style=flat-square)](https://clojurecivitas.org/Burin_Choomnuan.html)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-burinc-0a66c2?style=flat-square)](https://linkedin.com/in/burinc)
[![X](https://img.shields.io/badge/X-@agilecreativity-000?style=flat-square)](https://x.com/agilecreativity)

---

## 🎤 Speaking

### 🔜 [Clojure/Conj 2026](https://2026.clojure-conj.org/speakers) · Charlotte, NC
**Production ClojureDart for iOS, Android, and macOS**
📅 Friday, October 2 · 9:30–10:10 AM · Room W207CD

> Over the past twelve months a tiny team has used ClojureDart (Clojure compiled to Dart,
> running on Flutter) to build more than a dozen production apps: a document scanner with
> on-device OpenCV, a transit tracker with realtime GTFS, a venture-capital deck triager
> with on-device LLM evaluation, a notes app with on-device sentence embeddings, a
> marketplace, an encyclopedia, a financial charting app, and more. This experience report
> distills the patterns that survived the trip from prototype to production: a
> single-atom-plus-`:watch` architecture that replaces Riverpod and BLoC, a curated catalog
> of cljd-flutter pitfalls, and a reusable scaffold for new apps.

*My second year on the Conj stage.*

### 📺 [Clojure/Conj 2025](https://www.youtube.com/watch?v=jWkEKdp0gqk) · Charlotte, NC · Nov 2025
**From Scripts to Buy-In: How Small Clojure Wins Create Big Opportunities**

> How small, high-impact Clojure automation (AWS workflows, replacing clunky Postman
> processes, automating Okta SSO) builds the credibility that earns you bigger Clojure
> opportunities at work.

**[▶ Watch the talk](https://www.youtube.com/watch?v=jWkEKdp0gqk)** ·
[📝 My recap from Charlotte](https://www.linkedin.com/feed/update/urn:li:activity:7395774856686030848/)

### Meetups

| Talk | Venue | Date |
|---|---|---|
| **Three native Clojures, one C game library**<br/><sub>Lightning talk to a room of typed-FP regulars (Haskell, OCaml, Rust), showing the same raylib examples running under three different Clojures: [Jolt](https://jlt-commons.github.io/raylib-jlt/) on Chez Scheme, [jank](https://raylib-jnk.b12n.app) via C++/LLVM, and [JVM Clojure](https://raylib-clj.b12n.app) over Panama. `bb run-all` kept a real window cycling through the gallery in the background for the whole talk. The question that came up: why write it in Jolt when Chez Scheme is right there? Because Jolt reads like Clojure (vectors, lists, sets, maps), so there was no learning curve to cross first.</sub> | FP-SYD<br/><sub>Microsoft, North Sydney</sub> | Aug 2026 |
| **[raylib, driven from Lisp](https://www.02ship.com/blog/02ship-sydney-meetup-august-11-recap)**<br/><sub>Open-mic demo of raylib (a C game library) driven from Lisp, across all three suites: [Jolt](https://github.com/jlt-commons/raylib-jlt) on Chez Scheme, [jank](https://github.com/burinc/b12n-raylib-jnk) via C++/LLVM, and [JVM Clojure](https://github.com/burinc/b12n-raylib-clj) over Panama, plus the screen-capture and UI-automation tooling built to record their demo GIFs instead of testing by hand. All three suites are open source now; the capture tooling is still unreleased.</sub> | 02Ship Sydney Meetup<br/><sub>Level 2, 63 Dixon St, Haymarket</sub> | Aug 2026 |
| **[Three lenses, one mess: logic programming for the rest of us](https://www.linkedin.com/feed/update/urn:li:activity:7473516198232547329/)**<br/><sub>One RBAC authorization bug through three lenses, all in plain Clojure data: Prolog for role inheritance, Z3/SMT-LIB for conflicting constraints, a Mermaid-to-Prolog translation for reachability. Live REPL demo, closing on exposing solvers as LLM tools over MCP, where not hallucinating is the whole advantage. 📊 [Slides](https://github.com/burinc/burinc/blob/master/slides/three-lenses-one-mess.pdf)</sub> | FP-SYD<br/><sub>Microsoft, North Sydney</sub> | Jun 2026 |
| **[Supercharging Lisp with AI: Rapid Feedback Loops with Clojure and Claude Code](https://luma.com/yt0jierk)**<br/><sub>Lightning talk to a room of 100+ builders. The demo ran on [ClojureDart](https://github.com/Tensegritics/ClojureDart), Clojure compiled to Dart on Flutter, with a live REPL plugged straight into the running widget tree. That's the loop that lets Claude Code edit, hot-reload and assert against live UI in milliseconds instead of minutes.</sub> | AI SYD<br/><sub>Vercel × Relevance AI, Surry Hills</sub> | Apr 2026 |
| **The Anthropic Claude Ecosystem**<br/><sub>66 slides end to end: `~/.claude` as a personal AI config layer, Claude Code across CLI/IDE/desktop/CI, the agentic loop, MCP hosts and servers, and Agent Skills' three-level progressive disclosure. 📊 [Slides](https://b12n.net/slides/?pres=mastering-claude-code&slide=1) · [PDF](https://github.com/burinc/presentations/blob/main/20260223-vibe-code-meetup/mastering-claude-code-vibe-code-meetup.pdf)</sub> | Vibe Code Meetup<br/><sub>Sydney</sub> | Feb 2026 |
| **Clojure for Java Developers: Building MCP Servers Without the Java Pain**<br/><sub>Cut a 350+ line Spring AI MCP server with 15+ annotations down to 180 lines with zero annotations, keeping full enterprise capability.</sub> | Sydney JVM Community<br/><sub>Canva HQ, Sydney</sub> | Jul 2025 |
| **Clojure for the Type-Loving Functional Programmer**<br/><sub>What Clojure offers a typed-FP audience, beyond the dynamic typing and the parens.</sub> | FP-SYD | Jul 2025 |
| **[Java/Spring Boot Troubleshooting on Steroids with Clojure REPL](https://github.com/SydneyJavaMeetup/meetup-22-spring-ai-debugging)**<br/><sub>Debugging Spring Boot from a Clojure REPL, set directly against traditional remote debugging in IntelliJ. Live coding on a sample app: debug, explore and modify at runtime with no restart and no redeploy.</sub> | Sydney Java Meetup #22<br/><sub>Infomedia, Sydney</sub> | Mar 2025 |
| **Bridging Two Worlds: Leveraging Lisp-like Tools to Work with Python**<br/><sub>Scripting, extending and manipulating Python from Clojure with Basilisp and libpython-clj.</sub> | SYDJANGO | Dec 2024 |
| **Overview of Clojure for FP**<br/><sub>Live demos: libpython-clj via OpenCV, GraalVM via Babashka, AWS automation with the Cognitect AWS library, `whisper.clj` transcription, plus Rama and Jank.</sub> | FP-SYD | Aug 2024 |

### 🎙️ Interview

**[Clojure Corner: Interview with Burin Choomnuan](https://youtu.be/bQSQua46cdc)** ·
Flexiana, on Clojure, tooling, and building things in the open.

### 🤝 Community

I co-host **[Gen AI Enthusiasts (AI Users)](https://www.meetup.com/genai_enthusiasts_aiusers-online/)**,
a 2,000+ member online generative-AI community running fortnightly sessions on prompt
engineering, AI tooling and news, and practical LLM use.

---

## ✍️ Writing

I write at **[Clojure Civitas](https://clojurecivitas.org/Burin_Choomnuan.html)**, where
11 articles so far are mostly browser-native ClojureScript with [Scittle](https://github.com/babashka/scittle):

| Article | Date |
|---|---|
| [Making Fun Games with Clojure + Raylib](https://clojurecivitas.org/scicloj/clojure_jam/proposal/games_with_clojure.html) | Feb 2026 |
| [Clojure Conj 2025: Two Lies and a Truth Trivia](https://clojurecivitas.org/scittle/conj_2025/trivia_slideshow.html) | Nov 2025 |
| [Browser-Native PDF Viewer with ClojureScript & Scittle](https://clojurecivitas.org/scittle/pdf/pdf_viewer.html) | Nov 2025 |
| [Web Audio API Playground with ClojureScript & Scittle](https://clojurecivitas.org/scittle/audio/audio_playground.html) | Nov 2025 |
| [Build Galaga with ClojureScript & Scittle](https://clojurecivitas.org/scittle/games/galaga.html) | Nov 2025 |
| [Build Asteroids with ClojureScript & Scittle](https://clojurecivitas.org/scittle/games/asteroids_article.html) | Nov 2025 |
| [Build a Memory Game with ClojureScript & Scittle](https://clojurecivitas.org/scittle/games/memory_game_article.html) | Nov 2025 |
| [Browser-Native QR Code Scanner with Scittle](https://clojurecivitas.org/scittle/qrcode/qr_code_scanner.html) | Nov 2025 |
| [Free Weather Data with the National Weather Service API](https://clojurecivitas.org/scittle/weather/weather_nws_integration.html) | Nov 2025 |
| [Python + ClojureScript: Pyodide Integration with Scittle](https://clojurecivitas.org/scittle/pyodide/pyodide_integration.html) | Nov 2025 |
| [Building Browser-Native Presentations with Scittle](https://clojurecivitas.org/scittle/presentations/browser_native_slides.html) | Nov 2025 |

Plus **[b12n.net](https://b12n.net)** ("Lisp's Revenge"), my own blog, built with
Clojure/Cryogen, where I keep browser-native slide decks:
[Mastering Claude Code](https://b12n.net/slides/?pres=mastering-claude-code&slide=1) ·
[Diagrams as Text](https://b12n.net/slides/?pres=mermaid-diagrams&slide=1)

---

## 🛠️ What I build

**ClojureDart in production.** More than a dozen apps for iOS, Android and macOS in the
past year: on-device OpenCV document scanning, realtime GTFS transit tracking, on-device
LLM evaluation and sentence embeddings, charting, marketplaces. Most deployed internally,
several bound for the app stores. That's the
[Conj 2026 talk](https://2026.clojure-conj.org/speakers).

**Lisp against the C ABI.** Three suites of [raylib](https://www.raylib.com/) demos written
in three different Clojures, each one reaching the same C game library the way its own host
actually allows.

[**raylib-jlt**](https://github.com/jlt-commons/raylib-jlt): 119 examples in
[Jolt](https://github.com/jolt-lang/jolt), native Clojure on Chez Scheme. They call the
real `libraylib` directly over its C ABI through `jolt.ffi`: no wrapper library, no
codegen, no C shim. 42 shapes, 23 core, 16 in 3D, 10 games, 10 shaders, 9 generative,
5 text, 4 textures.
📖 [Docs & full gallery](https://jlt-commons.github.io/raylib-jlt/)

<table>
<tr>
<td align="center"><img src="https://raw.githubusercontent.com/jlt-commons/raylib-jlt/main/docs/demos/tetris.gif" width="240" alt="Tetris"><br><sub><code>bb tetris</code></sub></td>
<td align="center"><img src="https://raw.githubusercontent.com/jlt-commons/raylib-jlt/main/docs/demos/space-invaders.gif" width="240" alt="Space Invaders"><br><sub><code>bb space-invaders</code></sub></td>
<td align="center"><img src="https://raw.githubusercontent.com/jlt-commons/raylib-jlt/main/docs/demos/boids.gif" width="240" alt="Boids flocking"><br><sub><code>bb boids</code></sub></td>
</tr>
<tr>
<td align="center"><img src="https://raw.githubusercontent.com/jlt-commons/raylib-jlt/main/docs/demos/waving-cubes.gif" width="240" alt="Waving cubes in 3D"><br><sub><code>bb waving-cubes</code></sub></td>
<td align="center"><img src="https://raw.githubusercontent.com/jlt-commons/raylib-jlt/main/docs/demos/point-cloud.gif" width="240" alt="Rotating point cloud"><br><sub><code>bb point-cloud</code></sub></td>
<td align="center"><img src="https://raw.githubusercontent.com/jlt-commons/raylib-jlt/main/docs/demos/rlgl-solar-system.gif" width="240" alt="Solar system in rlgl"><br><sub><code>bb rlgl-solar-system</code></sub></td>
</tr>
</table>

> The interesting part is the ABI. raylib passes structs *by value* everywhere and Chez's
> `foreign-procedure` cannot, so each struct gets the treatment its size actually earns:
> `Color` rides in one register as a packed `:uint`, `Camera2D`/`Camera3D` go by pointer,
> and `Vector2`/`Vector3` geometry is drawn through rlgl's scalar immediate mode.

[**b12n-raylib-jnk**](https://github.com/burinc/b12n-raylib-jnk): 212 of the 217 *official*
raylib examples, ported to [jank](https://jank-lang.org): Clojure compiled to a real native
binary through C++/LLVM. The `shaders`, `textures`, `audio` and `text` categories are complete.
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
> to the C++ compiler, and raylib becomes ordinary interop: `cpp/BeginDrawing`,
> `cpp/RAYWHITE`, `(cpp/Camera3D (cpp/Vector3 ...) ...)`. The by-value structs that cost Jolt
> a hand-written marshalling strategy are just constructor calls. No binding DSL, no
> generated shim.

[**b12n-raylib-clj**](https://github.com/burinc/b12n-raylib-clj): 113 examples in JVM
Clojure, over [coffi](https://github.com/IGJoshua/coffi) and JDK 22+'s Panama Foreign
Function &amp; Memory API. 37 core, 28 shapes, 25 models, 9 games, plus audio, text,
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
> description, so the by-value `Color` that Jolt hand-packs into a `:uint` is just a
> `{:r 255 :g 0 :b 0 :a 255}` map here, serialized from a `defalias` layout. The seam
> shows where raylib mutates through a pointer: those calls allocate in a
> `confined-arena`, and the arena's lifetime is the one thing the abstraction will not
> hide from you.

Three hosts, one C library: Chez Scheme, C++/LLVM, and the JVM. Reading the same example
three ways is the clearest map I know of where each runtime puts the boundary.

**Desktop GUI, the Replicant way.** [**glitter**](https://github.com/jlt-commons/glitter) is a
GTK4 renderer for [Jolt](https://github.com/jolt-lang/jolt) that follows
[Replicant](https://github.com/cjohansen/replicant)'s model rather than React's: one
application-state atom, a pure `state -> hiccup` view function, top-down re-render on every
change, and event handlers that are *data*: `[[:action/inc]]`, not closures. No
component-local state anywhere. 43 widget tags so far; the six demos below are two basics
plus four [7GUIs](https://eugenkiss.github.io/7guis/tasks/) tasks.
📖 [Docs &amp; guide](https://jlt-commons.github.io/glitter/)

<table>
<tr>
<td align="center"><img src="https://raw.githubusercontent.com/jlt-commons/glitter/main/docs/demos/counter.gif" width="240" alt="Counter demo"><br><sub><code>jolt counter</code></sub></td>
<td align="center"><img src="https://raw.githubusercontent.com/jlt-commons/glitter/main/docs/demos/todo.gif" width="240" alt="Todo task board"><br><sub><code>jolt todo</code></sub></td>
<td align="center"><img src="https://raw.githubusercontent.com/jlt-commons/glitter/main/docs/demos/crud.gif" width="240" alt="7GUIs CRUD task"><br><sub><code>jolt crud</code></sub></td>
</tr>
<tr>
<td align="center"><img src="https://raw.githubusercontent.com/jlt-commons/glitter/main/docs/demos/flights.gif" width="240" alt="7GUIs Flight Booker task"><br><sub><code>jolt flights</code></sub></td>
<td align="center"><img src="https://raw.githubusercontent.com/jlt-commons/glitter/main/docs/demos/temperature.gif" width="240" alt="7GUIs Temperature Converter task"><br><sub><code>jolt temperature</code></sub></td>
<td align="center"><img src="https://raw.githubusercontent.com/jlt-commons/glitter/main/docs/demos/timer.gif" width="240" alt="7GUIs Timer task"><br><sub><code>jolt timer</code></sub></td>
</tr>
</table>

**Immediate-mode GUI, the other shape.** [**raygui-jlt**](https://github.com/jlt-commons/raygui-jlt)
is glitter's opposite number: no retained widget tree at all, just
[raygui](https://github.com/raysan5/raygui), raylib's companion GUI library, called
straight over its C ABI through `jolt.ffi`, one shared bindings namespace under a suite of
small programs. raygui ships as a header only, so there is no library to install: the repo
vendors `raygui.h` and compiles its own. 24 examples across 7 groups (basics, inputs,
collections, containers, dialogs, color and styling), each with a committed screenshot.
📖 [Docs &amp; full gallery](https://jlt-commons.github.io/raygui-jlt/)

<table>
<tr>
<td align="center"><img src="https://raw.githubusercontent.com/jlt-commons/raygui-jlt/main/docs/demos/style-selector.png" width="240" alt="Six vendored .rgs style themes"><br><sub><code>bb style-selector</code></sub></td>
<td align="center"><img src="https://raw.githubusercontent.com/jlt-commons/raygui-jlt/main/docs/demos/color-picker.png" width="240" alt="RGB color picker with an alpha bar"><br><sub><code>bb color-picker</code></sub></td>
<td align="center"><img src="https://raw.githubusercontent.com/jlt-commons/raygui-jlt/main/docs/demos/floating-window.png" width="240" alt="Two draggable floating windows"><br><sub><code>bb floating-window</code></sub></td>
</tr>
<tr>
<td align="center"><img src="https://raw.githubusercontent.com/jlt-commons/raygui-jlt/main/docs/demos/sliders.png" width="240" alt="Slider, slider bar and their value cells"><br><sub><code>bb sliders</code></sub></td>
<td align="center"><img src="https://raw.githubusercontent.com/jlt-commons/raygui-jlt/main/docs/demos/list-view-ex.png" width="240" alt="List view reporting focus and scroll"><br><sub><code>bb list-view-ex</code></sub></td>
<td align="center"><img src="https://raw.githubusercontent.com/jlt-commons/raygui-jlt/main/docs/demos/icon-buttons.png" width="240" alt="The embedded 1-bit icon pack on buttons"><br><sub><code>bb icon-buttons</code></sub></td>
</tr>
</table>

> The whole binding rides one signature: a bounding `Rectangle` passed **by value**,
> application state through a pointer, an `int` result; 61 functions, nearly all shaped the
> same, no callbacks and no retained state to own. So the lifetimes almost vanish: a single
> module-level scratch `Rectangle`, rewritten before each control, means no example allocates
> one inside a frame. `GuiScrollPanel` is the lone exception: two rectangles in one call,
> where Clojure's left-to-right evaluation would let the second clobber the first, so it gets
> a buffer of its own. Screenshots rather than GIFs here, deliberately: synthetic clicks do
> not actuate a raylib window at all, so a recording could never show a button being pressed.

**The same suite, a different Clojure.** [**raygui-jnk**](https://github.com/burinc/raygui-jnk)
is raygui-jlt's twin in [jank](https://jank-lang.org), which compiles Clojure through C++ and
LLVM rather than Chez Scheme. Same 24 examples, same names, same descriptions, so the two ports
read as one library seen through two implementations. What differs sits underneath: jank reaches
raygui as C++ rather than over an FFI, and the binding ships as an installable package. raygui
was not available to jank before this, which is why the sibling
[b12n-raylib-jnk](https://github.com/burinc/b12n-raylib-jnk) substituted keyboard controls in
seventeen of its examples. Those can be real controls now, on one dependency line, with no
vendored copy and no build script of your own.
📖 [Docs &amp; full gallery](https://raygui-jnk.b12n.app/)

<table>
<tr>
<td align="center"><img src="https://raw.githubusercontent.com/burinc/raygui-jnk/main/docs/demos/tab-bar.png" width="240" alt="Tabs with close requests"><br><sub><code>bb tab-bar</code></sub></td>
<td align="center"><img src="https://raw.githubusercontent.com/burinc/raygui-jnk/main/docs/demos/color-picker-hsv.png" width="240" alt="The HSV picker and panel"><br><sub><code>bb color-picker-hsv</code></sub></td>
<td align="center"><img src="https://raw.githubusercontent.com/burinc/raygui-jnk/main/docs/demos/scroll-panel.png" width="240" alt="A scroll panel over oversized content"><br><sub><code>bb scroll-panel</code></sub></td>
</tr>
<tr>
<td align="center"><img src="https://raw.githubusercontent.com/burinc/raygui-jnk/main/docs/demos/gui-state.png" width="240" alt="Forced states, alpha and lock"><br><sub><code>bb gui-state</code></sub></td>
<td align="center"><img src="https://raw.githubusercontent.com/burinc/raygui-jnk/main/docs/demos/custom-input-box.png" width="240" alt="A hand-built input dialog over a panel"><br><sub><code>bb custom-input-box</code></sub></td>
<td align="center"><img src="https://raw.githubusercontent.com/burinc/raygui-jnk/main/docs/demos/spinner-value-box.png" width="240" alt="Spinner and value box, clamped and typed"><br><sub><code>bb spinner-value-box</code></sub></td>
</tr>
</table>

> Jolt hands raygui a `Rectangle` by value. jank cannot, because no native value crosses a jank
> function boundary at all, so the whole shape inverts. Every wrapper takes `x y w h` as plain
> numbers and builds its `Rectangle` inside its own body, never accepting or returning one, and
> application state lives in boxed cells allocated before the frame loop. A closure counts as a
> boundary too, so `loop`/`recur` does work that `doseq` cannot. 53 of raygui's 61 functions are
> bound that way; most of the rest are font and icon-file calls the six vendored `.rgs` themes
> make unnecessary, since each one carries its own embedded font. The six examples above are
> deliberately different ones from raygui-jlt's, so between the two sections all 7 groups show.

**The same model, on native macOS.** [**glitter-uikit**](https://github.com/jlt-commons/glitter-uikit)
keeps glitter's model exactly as it is and swaps the toolkit underneath it: one
application-state atom, a pure `state -> hiccup` view, handlers as data, but every widget is a
real AppKit `NSView` rather than a GTK one. It began as a port of
[glimmer-uikit](https://github.com/jolt-lang/glimmer-uikit), the AppKit renderer for glitter's
Reagent-style sibling, so both models sit in the same code and the contrast is easy to read.
19 widget tags so far, with the same `:hbox`/`:vbox` sugar, and
[7GUIs](https://eugenkiss.github.io/7guis/tasks/) tasks 1 through 6 all ship. That is one further
than glitter itself gets, so Circle Drawer had nothing to port from and its model is original here.
📖 [Docs &amp; guide](https://jlt-commons.github.io/glitter-uikit/)

<table>
<tr>
<td align="center"><img src="https://raw.githubusercontent.com/jlt-commons/glitter-uikit/main/docs/demos/counter.gif" width="240" alt="Counter demo in a native AppKit window"><br><sub><code>bb counter</code></sub></td>
<td align="center"><img src="https://raw.githubusercontent.com/jlt-commons/glitter-uikit/main/docs/demos/widgets.gif" width="240" alt="Every registered widget tag in one window"><br><sub><code>bb widgets</code></sub></td>
<td align="center"><img src="https://raw.githubusercontent.com/jlt-commons/glitter-uikit/main/docs/demos/todo.gif" width="240" alt="Todo task board"><br><sub><code>bb todo</code></sub></td>
</tr>
<tr>
<td align="center"><img src="https://raw.githubusercontent.com/jlt-commons/glitter-uikit/main/docs/demos/crud.gif" width="240" alt="7GUIs CRUD task"><br><sub><code>bb crud</code></sub></td>
<td align="center"><img src="https://raw.githubusercontent.com/jlt-commons/glitter-uikit/main/docs/demos/flights.gif" width="240" alt="7GUIs Flight Booker task"><br><sub><code>bb flights</code></sub></td>
<td align="center"><img src="https://raw.githubusercontent.com/jlt-commons/glitter-uikit/main/docs/demos/timer.gif" width="240" alt="7GUIs Timer task"><br><sub><code>bb timer</code></sub></td>
</tr>
</table>

> The split earns its keep in the demos. `set-temperature`, `parse-date` and `get-view-state` come
> over from glitter untouched, because they are pure Clojure with no toolkit anywhere in them, so
> only the view and `-main` had to change. Styling is where the two renderers stop agreeing. AppKit
> has no CSS classes and no inline style property, so `:class` and `:style` are still accepted and
> diffed by `glitter.core`, then land here as honest no-ops. Circle Drawer asked for two things the
> renderer did not have yet. `+[NSEvent mouseLocation]` hands back a `CGPoint` by value and no
> scalar message send can carry a struct, so the FFI layer grew struct-by-value sends.
> `NSStackView` also lays children out in order with no way to place one freely, so the `:canvas`
> tag is an `NSButton` whose layer holds the circles. Those circles are `CALayer`s rather than
> views, and a layer takes no part in hit-testing, which leaves a click free to reach the canvas
> under a circle and keeps hit-testing a pure function over the model.

**And then teaching it.** [**b12n-gamedev-course**](https://github.com/burinc/b12n-gamedev-course)
is what those 419 raylib examples were for: a free course that teaches Lisp and game
programming as one thing, not "game dev, incidentally in Lisp." Six phases take you from
never having written a line of Lisp to a capstone, and every lesson builds a real, playable
game that teaches a Lisp idiom at the same time. Phase 3 is the one only those three raylib
suites make possible: port a game you wrote across all three, and watch the boundary to C
move under it.
📖 [Read the course](https://lisp-gamedev.b12n.app/)

<table>
<tr>
<td align="center"><img src="https://raw.githubusercontent.com/burinc/b12n-gamedev-course/main/docs/demos/pong.gif" width="240" alt="Pong"><br><sub>Lesson 1: Pong</sub></td>
<td align="center"><img src="https://raw.githubusercontent.com/burinc/b12n-gamedev-course/main/docs/demos/breakout.gif" width="240" alt="Breakout"><br><sub>Lesson 2: Breakout</sub></td>
<td align="center"><img src="https://raw.githubusercontent.com/burinc/b12n-gamedev-course/main/docs/demos/snake.gif" width="240" alt="Snake"><br><sub>Lesson 3: Snake</sub></td>
</tr>
<tr>
<td align="center"><img src="https://raw.githubusercontent.com/burinc/b12n-gamedev-course/main/docs/demos/space-invaders.gif" width="240" alt="Space Invaders"><br><sub>Lesson 4: Space Invaders</sub></td>
<td align="center"><img src="https://raw.githubusercontent.com/burinc/b12n-gamedev-course/main/docs/demos/tetris.gif" width="120" alt="Tetris"><br><sub>Lesson 5: Tetris</sub></td>
<td align="center"><img src="https://raw.githubusercontent.com/burinc/b12n-gamedev-course/main/docs/demos/flappy-bird.gif" width="240" alt="Flappy Bird"><br><sub>Lesson 6: Flappy Bird</sub></td>
</tr>
</table>

> Those are the course's own games, running from its `exercises/` code on its own vendored
> engine: the thing a student actually ends up with, not a borrowed screenshot. Lessons are
> CC BY-SA 4.0 and the code EPL-2.0, so teaching from it at a meetup or a classroom needs
> nothing from me. Phases 0 to 3 stand on the three raylib suites today; the later phases
> open up as the remaining sibling repos do.

**Clojure meets AI.** Agentic workflows, MCP servers, and LLM-driven developer tooling are
where most of my time goes now. A lot of that work is private for the moment, so the
patterns tend to surface in talks and articles before the code does.

**Public bits:** [b12n-gamedev-course](https://github.com/burinc/b12n-gamedev-course) ·
[raylib-jlt](https://github.com/jlt-commons/raylib-jlt) · [b12n-raylib-jnk](https://github.com/burinc/b12n-raylib-jnk) · [b12n-raylib-clj](https://github.com/burinc/b12n-raylib-clj) ·
[glitter](https://github.com/jlt-commons/glitter) (Replicant-style GTK4 for Jolt) ·
[glitter-gl](https://github.com/jlt-commons/glitter-gl) (OpenGL geometry and shaders for it) ·
[glitter-uikit](https://github.com/jlt-commons/glitter-uikit) (the same model, on native macOS AppKit) ·
[raygui-jlt](https://github.com/jlt-commons/raygui-jlt) (immediate-mode GUI for Jolt) ·
[raygui-jnk](https://github.com/burinc/raygui-jnk) (the same suite, for jank) ·
[dartclojure.el](https://github.com/burinc/dartclojure.el)
(Dart/Flutter → ClojureDart, in Emacs) · [viip](https://github.com/burinc/viip) ·
[Clojars](https://clojars.org/users/agilecreativity) ·
[RubyGems](https://rubygems.org/profiles/agilecreativity)

---

## 🌱 Open source

### jlt-commons

I started [**jlt-commons**](https://github.com/jlt-commons) in August 2026, a
community-led home for [Jolt](https://github.com/jolt-lang/jolt) libraries and tooling.
Jolt is young, so most of its ecosystem is still one person's side project, and a side
project stops the month its author gets busy. The org gives that work somewhere to land,
and gives anyone who wants to help a place to do it that is not someone else's personal
account.

There are two ways in. Adoption is for a project whose maintainer can no longer look
after it. We ask the current owner first, every time, and prefer a transfer over a fork
so the stars and the issue history come along. Incubation is for new work, whether that
is a port of a Clojure library people already rely on or something the core team would
rather not own. The bar is a real gap and someone willing to maintain it, which is
deliberately low while the language is this young.

It is not an official Jolt project. The language and the libraries its core team
maintains live in [jolt-lang](https://github.com/jolt-lang).

What is there so far:

- [**raylib-jlt**](https://github.com/jlt-commons/raylib-jlt), the 119 raylib examples
  above, and the first thing I moved across from my own account. Its
  [docs](https://jlt-commons.github.io/raylib-jlt/) moved with it, off my own hosting
  and onto the org's.
- [**raygui-jlt**](https://github.com/jlt-commons/raygui-jlt), the immediate-mode GUI
  suite, transferred the same day and onto the same
  [docs setup](https://jlt-commons.github.io/raygui-jlt/).
- [**glitter**](https://github.com/jlt-commons/glitter), the GTK4 renderer above, with
  [**glitter-gl**](https://github.com/jlt-commons/glitter-gl) for OpenGL geometry and
  shaders and [**glitter-uikit**](https://github.com/jlt-commons/glitter-uikit) for the
  same model on native macOS AppKit. All three went across together and publish at
  [jlt-commons.github.io](https://jlt-commons.github.io/glitter/).
- [**docs-engine**](https://github.com/jlt-commons/docs-engine), the generator behind
  every project's documentation. A project writes markdown and a short config file, and
  gets syntax highlighting, mermaid diagrams and a theme that follows the reader's
  light or dark setting, without maintaining any of that itself.
- [**meta**](https://github.com/jlt-commons/meta), the governance and the proposal
  queue, kept short enough that people will actually read it.

If you maintain something in Jolt and would rather it outlived your own free time, or
you want to build something and would rather not do it alone, the
[proposal queue](https://github.com/jlt-commons/meta) is open.

### Upstream

Most recent is [**jolt-lang/jolt**](https://github.com/jolt-lang/jolt/commits?author=burinc)
itself, with 15 commits across July and August 2026 to the Clojure-on-Chez-Scheme host: `:string`
carrying NULL in both directions through the FFI, fiber-parking for subprocess pipe I/O, and
a cross-compilation path (`tarm64osx` → `ta6osx` via Chez xpatch, macOS → Linux via `zig cc`)
with a CI cross-smoke workflow behind it. It is the runtime under
[raylib-jlt](https://github.com/jlt-commons/raylib-jlt),
[raygui-jlt](https://github.com/jlt-commons/raygui-jlt), [glitter](https://github.com/jlt-commons/glitter)
and [glitter-uikit](https://github.com/jlt-commons/glitter-uikit), so the patches tend to fall out of
building on it.

Longer-running: contributions to [babashka/process](https://github.com/babashka/process/commits?author=agilecreativity),
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
> is my original account, from before I found Clojure, and a lot of my older OSS commits live
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
