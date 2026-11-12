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

🗣️ **Next up: [AI Engineer Sydney 2026](https://webdirections.org/ai-engineer/speakers/burin-choomnuan/)**
on December 7, fresh off [Clojure/Conj 2026](https://2026.clojure-conj.org/speakers). I'm
generally available to talk about ClojureDart, MCP/agent tooling, and using LLMs in real
engineering workflows. [Get in touch](https://linkedin.com/in/burinc).

**At a glance**

- ☕ **Java inside Jolt.** [champaca](https://github.com/b12n-oss/champaca) runs real Java libraries with no JVM in the process, and Spring Boot and Quarkus apps start on it.
- 🎮 **513 raylib examples in three Clojures**, Jolt, jank and JVM Clojure, plus Pac-Man four ways and 137 scenes on an iPhone.
- 🔧 **Upstream fixes** merged into [cisco/ChezScheme](https://github.com/cisco/ChezScheme/commits?author=burinc) and [atgreen/openldk](https://github.com/atgreen/openldk/commits?author=burinc), and 79 merged pull requests to [Jolt](https://github.com/jolt-lang/jolt/commits?author=burinc).
- 🌱 **[jlt-commons](https://github.com/jlt-commons)**, the community home for Jolt libraries I started in August, now at 44 public repos.
- 🇦🇺 **[clj-aus](https://clj-aus.github.io/)**, Australia's Clojure meetup. [Session two](https://www.meetup.com/clojure-australia/events/317297998/) is online on Tuesday 24 November.

[![Website](https://img.shields.io/badge/blog-b12n.net-2e6176?style=flat-square)](https://b12n.net)
[![Articles](https://img.shields.io/badge/Clojure_Civitas-11_articles-aadd52?style=flat-square)](https://clojurecivitas.org/Burin_Choomnuan.html)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-burinc-0a66c2?style=flat-square)](https://linkedin.com/in/burinc)
[![X](https://img.shields.io/badge/X-@agilecreativity-000?style=flat-square)](https://x.com/agilecreativity)

---


## 🎤 Speaking

- 🔜 **[AI Engineer Sydney 2026](https://webdirections.org/ai-engineer/)** · Hilton Hotel, Sydney · Mon 7 Dec, 4:30 PM<br>
  [209 ports in six days, in a language the model barely knew](https://webdirections.org/ai-engineer/speakers/burin-choomnuan/)
- 📺 **[Clojure/Conj 2026](https://2026.clojure-conj.org/speakers)** · Charlotte, NC · Oct 2026<br>
  Production ClojureDart for iOS, Android, and macOS. The recording is on its way.
- 📺 **[Clojure/Conj 2025](https://www.youtube.com/watch?v=jWkEKdp0gqk)** · Charlotte, NC · Nov 2025<br>
  From Scripts to Buy-In: How Small Clojure Wins Create Big Opportunities. [▶ Watch](https://www.youtube.com/watch?v=jWkEKdp0gqk)

<details>
<summary><b>The three abstracts</b></summary>

### 🔜 [AI Engineer Sydney 2026](https://webdirections.org/ai-engineer/) · Hilton Hotel, Sydney
**[209 ports in six days, in a language the model barely knew](https://webdirections.org/ai-engineer/speakers/burin-choomnuan/)**
📅 Monday, December 7 · 4:30 PM · Software Engineering track

> Jolt and jank are two young Clojure implementations, one running on Chez Scheme and one
> compiling to native code through C++/LLVM. Between them they have almost no public code
> for a model to have learned from. Ask Claude for jank and it confidently writes JVM
> Clojure, and none of that compiles. Over six days in July I ported 209 of raylib's
> official C examples to jank anyway, across 194 commits. Then again in Jolt, and once more
> in JVM Clojure over Panama. That's 422 working examples across three runtimes, every one
> of them driving the same C game library.
>
> This talk is about the harness, because the model was the same model everyone in the room
> already uses. Everything around it is what changed.

Those are the three raylib suites further down this page, and they kept growing after July.
Between them they're at 513 examples now.

### 📺 [Clojure/Conj 2026](https://2026.clojure-conj.org/speakers) · Charlotte, NC · Oct 2026
**Production ClojureDart for iOS, Android, and macOS**

> Over the past twelve months a tiny team has used ClojureDart (Clojure compiled to Dart,
> running on Flutter) to build more than a dozen production apps: a document scanner with
> on-device OpenCV, a transit tracker with realtime GTFS, a venture-capital deck triager
> with on-device LLM evaluation, a notes app with on-device sentence embeddings, a
> marketplace, an encyclopedia, a financial charting app, and more. This experience report
> distills the patterns that survived the trip from prototype to production: a
> single-atom-plus-`:watch` architecture that replaces Riverpod and BLoC, a curated catalog
> of cljd-flutter pitfalls, and a reusable scaffold for new apps.

My second year on the Conj stage, and done now. The recording is still in the publishing
queue, so the link goes here once it's out.

### 📺 [Clojure/Conj 2025](https://www.youtube.com/watch?v=jWkEKdp0gqk) · Charlotte, NC · Nov 2025
**From Scripts to Buy-In: How Small Clojure Wins Create Big Opportunities**

> How small, high-impact Clojure automation (AWS workflows, replacing clunky Postman
> processes, automating Okta SSO) builds the credibility that earns you bigger Clojure
> opportunities at work.

**[▶ Watch the talk](https://www.youtube.com/watch?v=jWkEKdp0gqk)** ·
[📝 My recap from Charlotte](https://www.linkedin.com/feed/update/urn:li:activity:7395774856686030848/)

</details>

<details>
<summary><b>Eleven meetup talks, 2024 to 2026</b></summary>

### Meetups

| Talk | Venue | Date |
|---|---|---|
| **[Three native Clojures, one C game library](https://clj-aus.github.io/)**<br/><sub>The full hour version for clj-aus's first session: the same raylib comparison across [Jolt](https://jlt-commons.github.io/raylib-jlt/), [jank](https://b12n-oss.github.io/raylib-jnk/) and [JVM Clojure](https://b12n-oss.github.io/raylib-clj/), with live demos running the whole time and 20 minutes of questions after. Run online so anyone in the country could join, and the group's opening night drew a solid turnout.</sub> | clj-aus<br/><sub>Online, Australia-wide</sub> | Sep 2026 |
| **Three native Clojures, one C game library**<br/><sub>Lightning talk to a room of typed-FP regulars (Haskell, OCaml, Rust), showing the same raylib examples running under three different Clojures: [Jolt](https://jlt-commons.github.io/raylib-jlt/) on Chez Scheme, [jank](https://b12n-oss.github.io/raylib-jnk/) via C++/LLVM, and [JVM Clojure](https://b12n-oss.github.io/raylib-clj/) over Panama. `bb run-all` kept a real window cycling through the gallery in the background for the whole talk. The question that came up: why write it in Jolt when Chez Scheme is right there? Because Jolt reads like Clojure (vectors, lists, sets, maps), so there was no learning curve to cross first.</sub> | FP-SYD<br/><sub>Microsoft, North Sydney</sub> | Aug 2026 |
| **[raylib, driven from Lisp](https://www.02ship.com/blog/02ship-sydney-meetup-august-11-recap)**<br/><sub>Open-mic demo of raylib (a C game library) driven from Lisp, across all three suites: [Jolt](https://github.com/jlt-commons/raylib-jlt) on Chez Scheme, [jank](https://github.com/b12n-oss/raylib-jnk) via C++/LLVM, and [JVM Clojure](https://github.com/b12n-oss/raylib-clj) over Panama, plus the screen-capture and UI-automation tooling built to record their demo GIFs instead of testing by hand. All three suites are open source now; the capture tooling is still unreleased.</sub> | 02Ship Sydney Meetup<br/><sub>Level 2, 63 Dixon St, Haymarket</sub> | Aug 2026 |
| **[Three lenses, one mess: logic programming for the rest of us](https://www.linkedin.com/feed/update/urn:li:activity:7473516198232547329/)**<br/><sub>One RBAC authorization bug through three lenses, all in plain Clojure data: Prolog for role inheritance, Z3/SMT-LIB for conflicting constraints, a Mermaid-to-Prolog translation for reachability. Live REPL demo, closing on exposing solvers as LLM tools over MCP, where not hallucinating is the whole advantage. 📊 [Slides](https://github.com/burinc/burinc/blob/master/slides/three-lenses-one-mess.pdf)</sub> | FP-SYD<br/><sub>Microsoft, North Sydney</sub> | Jun 2026 |
| **[Supercharging Lisp with AI: Rapid Feedback Loops with Clojure and Claude Code](https://luma.com/yt0jierk)**<br/><sub>Lightning talk to a room of 100+ builders. The demo ran on [ClojureDart](https://github.com/Tensegritics/ClojureDart), Clojure compiled to Dart on Flutter, with a live REPL plugged straight into the running widget tree. That's the loop that lets Claude Code edit, hot-reload and assert against live UI in milliseconds instead of minutes.</sub> | AI SYD<br/><sub>Vercel × Relevance AI, Surry Hills</sub> | Apr 2026 |
| **The Anthropic Claude Ecosystem**<br/><sub>66 slides end to end: `~/.claude` as a personal AI config layer, Claude Code across CLI/IDE/desktop/CI, the agentic loop, MCP hosts and servers, and Agent Skills' three-level progressive disclosure. 📊 [Slides](https://b12n.net/slides/?pres=mastering-claude-code&slide=1) · [PDF](https://github.com/burinc/presentations/blob/main/20260223-vibe-code-meetup/mastering-claude-code-vibe-code-meetup.pdf)</sub> | Vibe Code Meetup<br/><sub>Sydney</sub> | Feb 2026 |
| **Clojure for Java Developers: Building MCP Servers Without the Java Pain**<br/><sub>Cut a 350+ line Spring AI MCP server with 15+ annotations down to 180 lines with zero annotations, keeping full enterprise capability.</sub> | Sydney JVM Community<br/><sub>Canva HQ, Sydney</sub> | Jul 2025 |
| **Clojure for the Type-Loving Functional Programmer**<br/><sub>What Clojure offers a typed-FP audience, beyond the dynamic typing and the parens.</sub> | FP-SYD | Jul 2025 |
| **[Java/Spring Boot Troubleshooting on Steroids with Clojure REPL](https://github.com/SydneyJavaMeetup/meetup-22-spring-ai-debugging)**<br/><sub>Debugging Spring Boot from a Clojure REPL, set directly against traditional remote debugging in IntelliJ. Live coding on a sample app: debug, explore and modify at runtime with no restart and no redeploy.</sub> | Sydney Java Meetup #22<br/><sub>Infomedia, Sydney</sub> | Mar 2025 |
| **Bridging Two Worlds: Leveraging Lisp-like Tools to Work with Python**<br/><sub>Scripting, extending and manipulating Python from Clojure with Basilisp and libpython-clj.</sub> | SYDJANGO | Dec 2024 |
| **Overview of Clojure for FP**<br/><sub>Live demos: libpython-clj via OpenCV, GraalVM via Babashka, AWS automation with the Cognitect AWS library, `whisper.clj` transcription, plus Rama and Jank.</sub> | FP-SYD | Aug 2024 |

</details>

**Interview:** [Clojure Corner](https://youtu.be/bQSQua46cdc) with Flexiana. **Community:** I co-host [Gen AI Enthusiasts](https://www.meetup.com/genai_enthusiasts_aiusers-online/), 2,000+ members online, and help run [clj-aus](https://clj-aus.github.io/).

<details>
<summary><b>More on the interview and the two communities</b></summary>

### 🎙️ Interview

**[Clojure Corner: Interview with Burin Choomnuan](https://youtu.be/bQSQua46cdc)** ·
Flexiana, on Clojure, tooling, and building things in the open.

### 🤝 Community

I co-host **[Gen AI Enthusiasts (AI Users)](https://www.meetup.com/genai_enthusiasts_aiusers-online/)**,
a 2,000+ member online generative-AI community running fortnightly sessions on prompt
engineering, AI tooling and news, and practical LLM use.

I also help run **[clj-aus](https://clj-aus.github.io/)**, Australia's Clojure meetup. It meets
monthly and is built to be national from the start, since one Australian city is thin on its
own and the whole country isn't. The first session in September opened with the raylib
three-Clojures talk above.
**[Session two](https://www.meetup.com/clojure-australia/events/317297998/)** is on Tuesday
24 November, online from 7pm AEDT: a tour of what Jolt can do without a JVM since September,
then Clojure running on a Nintendo Wii, with four games played live. Every session from this
one on carries a lightning-talk slot, and first-time speakers get priority.

</details>

---

## ✍️ Writing

I write at **[Clojure Civitas](https://clojurecivitas.org/Burin_Choomnuan.html)**, where
11 articles so far are mostly browser-native ClojureScript with [Scittle](https://github.com/babashka/scittle):

| Article | Date |
|---|---|
| [Making Fun Games with Clojure + Raylib](https://clojurecivitas.org/scicloj/clojure_jam/proposal/games_with_clojure.html) | Feb 2026 |
| [Clojure Conj 2025: Two Lies and a Truth Trivia](https://clojurecivitas.org/scittle/conj_2025/trivia_slideshow.html) | Nov 2025 |
| [Browser-Native PDF Viewer with ClojureScript & Scittle](https://clojurecivitas.org/scittle/pdf/pdf_viewer.html) | Nov 2025 |

<details>
<summary><b>Eight more articles</b></summary>

| Article | Date |
|---|---|
| [Web Audio API Playground with ClojureScript & Scittle](https://clojurecivitas.org/scittle/audio/audio_playground.html) | Nov 2025 |
| [Build Galaga with ClojureScript & Scittle](https://clojurecivitas.org/scittle/games/galaga.html) | Nov 2025 |
| [Build Asteroids with ClojureScript & Scittle](https://clojurecivitas.org/scittle/games/asteroids_article.html) | Nov 2025 |
| [Build a Memory Game with ClojureScript & Scittle](https://clojurecivitas.org/scittle/games/memory_game_article.html) | Nov 2025 |
| [Browser-Native QR Code Scanner with Scittle](https://clojurecivitas.org/scittle/qrcode/qr_code_scanner.html) | Nov 2025 |
| [Free Weather Data with the National Weather Service API](https://clojurecivitas.org/scittle/weather/weather_nws_integration.html) | Nov 2025 |
| [Python + ClojureScript: Pyodide Integration with Scittle](https://clojurecivitas.org/scittle/pyodide/pyodide_integration.html) | Nov 2025 |
| [Building Browser-Native Presentations with Scittle](https://clojurecivitas.org/scittle/presentations/browser_native_slides.html) | Nov 2025 |

</details>

Plus **[b12n.net](https://b12n.net)** ("Lisp's Revenge"), my own blog, built with
Clojure/Cryogen, where I keep browser-native slide decks:
[Mastering Claude Code](https://b12n.net/slides/?pres=mastering-claude-code&slide=1) ·
[Diagrams as Text](https://b12n.net/slides/?pres=mermaid-diagrams&slide=1)

---

## 🛠️ What I build

<table>
<tr>
<td align="center"><img src="https://raw.githubusercontent.com/b12n-oss/raylib-jank-demo/main/docs/demos/basic-pbr.gif" width="180" alt="Physically based rendering in jank"><br><sub>raylib in jank</sub></td>
<td align="center"><img src="https://raw.githubusercontent.com/jlt-commons/raylib-ios/main/docs/images/kaleidoscope.gif" width="180" alt="Kaleidoscope on an iPhone"><br><sub>Jolt on an iPhone</sub></td>
<td align="center"><img src="https://raw.githubusercontent.com/jlt-commons/glitter/main/docs/demos/todo.gif" width="180" alt="glitter todo board"><br><sub>glitter, GTK4</sub></td>
<td align="center"><img src="https://raw.githubusercontent.com/b12n-oss/raylib-pacman/main/docs/demos/jolt-example.gif" width="180" alt="Pac-Man in Jolt"><br><sub>Pac-Man in Jolt</sub></td>
</tr>
</table>

**ClojureDart in production.** More than a dozen apps for iOS, Android and macOS in the
past year: on-device OpenCV document scanning, realtime GTFS transit tracking, on-device
LLM evaluation and sentence embeddings, charting, marketplaces. Most deployed internally,
several bound for the app stores. That's the
[Conj 2026 talk](https://2026.clojure-conj.org/speakers).

**Clojure meets AI.** Agentic workflows, MCP servers, and LLM-driven developer tooling are
where most of my time goes now. The first piece of that is out:
[**mcp-tkx**](https://github.com/b12n-oss/mcp-tkx) builds Model Context Protocol clients
and servers in Clojure and ClojureScript, across five protocol revisions, and one session
can serve both the handshake era and the newer stateless one at once. Plenty of the rest
is still private, so those patterns tend to surface in talks and articles before the code
does.

Each of the projects below opens with a click.

<details>
<summary><b>Java, with no JVM in the process.</b> champaca, a Java runtime inside Jolt</summary>

[**champaca**](https://github.com/b12n-oss/champaca) is
the newest thing here and by some distance the biggest, at close to 600 commits since it went
up in mid-October. It's a Java runtime that lives inside Jolt, rebuilt from Anthony Green's
[OpenLDK](https://github.com/atgreen/openldk), a Java runtime for Common Lisp. The first time a
method gets called, a translator written in Jolt's Clojure turns its bytecode into Chez Scheme
source, and Chez compiles that to native code. Java objects end up as Chez records in Jolt's own
heap, so calling a Java library from Jolt is an ordinary procedure call with no second runtime
to talk to.

The classes are the JDK's own, read out of `$JAVA_HOME/lib/modules`, and the JDK boots the way
it does on a JVM, module system and all. Thirteen common libraries give the same output they
give on HotSpot, Guava, Jackson, jsoup, H2 and Byte Buddy among them, and Spring Boot 4.1.2 and
Quarkus 3.40.1 applications start. A warm `Hello` takes 0.39 s from exec to exit on an M1 Pro,
against 4.3 s for the first run, because a startup cache keeps whatever the earlier run
compiled. It's experimental and says so at the top of its README. A program can still reach a
JDK native nobody has written yet, JNI libraries aren't there, and a warm start still costs a
few times HotSpot's time and memory.
📖 [Docs & guide](https://b12n-oss.github.io/champaca/) ·
[Limitations](https://github.com/b12n-oss/champaca/blob/main/docs/guide/limitations.md)

> It got here by way of a first attempt.
> [**jolt-openldk**](https://github.com/jlt-commons/jolt-openldk) loads SBCL into the Jolt
> process as a shared library, starts it on a core with OpenLDK already warmed up, and calls
> across through a small C shim. That works, and it's still alpha. But it meant two Lisp runtimes
> sharing one process, and champaca is what happens when you take the translator idea and make
> Chez the only one. Both of them kept running into bugs in OpenLDK itself, and the fixes went
> back upstream, which the Upstream section below has more on.

</details>

<details>
<summary><b>Lisp against the C ABI.</b> 513 raylib examples in Jolt, jank and JVM Clojure</summary>

Three suites of [raylib](https://www.raylib.com/) demos written
in three different Clojures, each one reaching the same C game library the way its own host
actually allows.

Each suite is two repos now. The bindings stay where they started, and the examples moved
out into a `-demo` sibling where every one is its own small runnable project, pinned to the
bindings by one commit.

[**raylib-jlt**](https://github.com/jlt-commons/raylib-jlt): 187 examples in
[Jolt](https://github.com/jolt-lang/jolt), native Clojure on Chez Scheme. They call the
real `libraylib` directly over its C ABI through `jolt.ffi`: no wrapper library, no
codegen, no C shim. 45 shapes, 34 core, 28 textures, 28 in 3D, 20 shaders, 11 games,
10 generative, 8 text, 3 audio. That's up from 119 in September.
📖 [Bindings](https://jlt-commons.github.io/raylib-jlt/) ·
[every example, in raylib-jolt-demo](https://jlt-commons.github.io/raylib-jolt-demo/)

<table>
<tr>
<td align="center"><img src="https://raw.githubusercontent.com/jlt-commons/raylib-jolt-demo/main/docs/demos/tetris.gif" width="240" alt="Tetris"><br><sub><code>bb tetris</code></sub></td>
<td align="center"><img src="https://raw.githubusercontent.com/jlt-commons/raylib-jolt-demo/main/docs/demos/space-invaders.gif" width="240" alt="Space Invaders"><br><sub><code>bb space-invaders</code></sub></td>
<td align="center"><img src="https://raw.githubusercontent.com/jlt-commons/raylib-jolt-demo/main/docs/demos/boids.gif" width="240" alt="Boids flocking"><br><sub><code>bb boids</code></sub></td>
</tr>
<tr>
<td align="center"><img src="https://raw.githubusercontent.com/jlt-commons/raylib-jolt-demo/main/docs/demos/waving-cubes.gif" width="240" alt="Waving cubes in 3D"><br><sub><code>bb waving-cubes</code></sub></td>
<td align="center"><img src="https://raw.githubusercontent.com/jlt-commons/raylib-jolt-demo/main/docs/demos/point-cloud.gif" width="240" alt="Rotating point cloud"><br><sub><code>bb point-cloud</code></sub></td>
<td align="center"><img src="https://raw.githubusercontent.com/jlt-commons/raylib-jolt-demo/main/docs/demos/rlgl-solar-system.gif" width="240" alt="Solar system in rlgl"><br><sub><code>bb rlgl-solar-system</code></sub></td>
</tr>
</table>

> The interesting part is the ABI. raylib passes structs *by value* everywhere and Chez's
> `foreign-procedure` cannot, so each struct gets the treatment its size actually earns:
> `Color` rides in one register as a packed `:uint`, `Camera2D`/`Camera3D` go by pointer,
> and `Vector2`/`Vector3` geometry is drawn through rlgl's scalar immediate mode.

[**raylib-jnk**](https://github.com/b12n-oss/raylib-jnk): 212 of the 217 *official*
raylib examples, ported to [jank](https://jank-lang.org): Clojure compiled to a real native
binary through C++/LLVM, plus one original. The `shaders`, `textures`, `audio` and `text`
categories are complete.
📖 [Bindings guide](https://b12n-oss.github.io/raylib-jnk/) ·
[every example, in raylib-jank-demo](https://b12n-oss.github.io/raylib-jank-demo/)

<table>
<tr>
<td align="center"><img src="https://raw.githubusercontent.com/b12n-oss/raylib-jank-demo/main/docs/demos/basic-pbr.gif" width="240" alt="Physically based rendering"><br><sub><code>bb basic-pbr</code></sub></td>
<td align="center"><img src="https://raw.githubusercontent.com/b12n-oss/raylib-jank-demo/main/docs/demos/magnifying-glass.gif" width="240" alt="Magnifying glass over a texture"><br><sub><code>bb magnifying-glass</code></sub></td>
<td align="center"><img src="https://raw.githubusercontent.com/b12n-oss/raylib-jank-demo/main/docs/demos/cel-shading.gif" width="240" alt="Cel-shaded model"><br><sub><code>bb cel-shading</code></sub></td>
</tr>
<tr>
<td align="center"><img src="https://raw.githubusercontent.com/b12n-oss/raylib-jank-demo/main/docs/demos/shadowmap-rendering.gif" width="240" alt="Real-time shadow mapping"><br><sub><code>bb shadowmap-rendering</code></sub></td>
<td align="center"><img src="https://raw.githubusercontent.com/b12n-oss/raylib-jank-demo/main/docs/demos/spectrum-visualizer.gif" width="240" alt="Audio spectrum visualizer"><br><sub><code>bb spectrum-visualizer</code></sub></td>
<td align="center"><img src="https://raw.githubusercontent.com/b12n-oss/raylib-jank-demo/main/docs/demos/animation-blending.gif" width="240" alt="Skeletal animation blending"><br><sub><code>bb animation-blending</code></sub></td>
</tr>
</table>

> Here there is no FFI at all. `(:include "raylib.h")` in the `ns` form hands the real header
> to the C++ compiler, and raylib becomes ordinary interop: `cpp/BeginDrawing`,
> `cpp/RAYWHITE`, `(cpp/Camera3D (cpp/Vector3 ...) ...)`. The by-value structs that cost Jolt
> a hand-written marshalling strategy are just constructor calls. No binding DSL, no
> generated shim.

[**raylib-clj**](https://github.com/b12n-oss/raylib-clj): 113 examples in JVM
Clojure, over [coffi](https://github.com/IGJoshua/coffi) and JDK 22+'s Panama Foreign
Function &amp; Memory API. 37 core, 28 shapes, 25 models, 9 games, plus audio, text,
textures and shaders.
📖 [Bindings](https://b12n-oss.github.io/raylib-clj/) ·
[every example, in raylib-clj-demo](https://b12n-oss.github.io/raylib-clj-demo/)

<table>
<tr>
<td align="center"><img src="https://raw.githubusercontent.com/b12n-oss/raylib-clj-demo/main/docs/demos/tetris.gif" width="240" alt="Tetris"><br><sub><code>bb tetris</code></sub></td>
<td align="center"><img src="https://raw.githubusercontent.com/b12n-oss/raylib-clj-demo/main/docs/demos/asteroids.gif" width="240" alt="Asteroids"><br><sub><code>bb asteroids</code></sub></td>
<td align="center"><img src="https://raw.githubusercontent.com/b12n-oss/raylib-clj-demo/main/docs/demos/background-scrolling.gif" width="240" alt="Parallax background scrolling"><br><sub><code>bb background-scrolling</code></sub></td>
</tr>
<tr>
<td align="center"><img src="https://raw.githubusercontent.com/b12n-oss/raylib-clj-demo/main/docs/demos/basic-lighting.gif" width="240" alt="Shader-based dynamic lighting"><br><sub><code>bb basic-lighting</code></sub></td>
<td align="center"><img src="https://raw.githubusercontent.com/b12n-oss/raylib-clj-demo/main/docs/demos/solar-system.gif" width="240" alt="Orbiting solar system in 3D"><br><sub><code>bb solar-system</code></sub></td>
<td align="center"><img src="https://raw.githubusercontent.com/b12n-oss/raylib-clj-demo/main/docs/demos/lorenz-attractor.gif" width="240" alt="Lorenz attractor"><br><sub><code>bb lorenz-attractor</code></sub></td>
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

</details>

<details>
<summary><b>The same game, four times.</b> Pac-Man in babashka, JVM Clojure, jank and Jolt</summary>

[**raylib-pacman**](https://github.com/b12n-oss/raylib-pacman)
takes that comparison down to a single program. Pac-Man, written out four times over, once
per runtime, with babashka joining the three above. Same maze, same ghosts keeping their
1980 personalities, same physics. Each copy is a standalone project and nothing is shared
between them, which is the whole point. You can diff the four and see exactly what the
runtime costs you.
📖 [Docs &amp; guide](https://b12n-oss.github.io/raylib-pacman/)

<table>
<tr>
<td align="center"><img src="https://raw.githubusercontent.com/b12n-oss/raylib-pacman/main/docs/demos/babashka-example.gif" width="240" alt="Pac-Man running under babashka"><br><sub><code>bb babashka</code></sub></td>
<td align="center"><img src="https://raw.githubusercontent.com/b12n-oss/raylib-pacman/main/docs/demos/clojure-example.gif" width="240" alt="Pac-Man running under JVM Clojure"><br><sub><code>bb clj</code></sub></td>
</tr>
<tr>
<td align="center"><img src="https://raw.githubusercontent.com/b12n-oss/raylib-pacman/main/docs/demos/jank-example.gif" width="240" alt="Pac-Man running under jank"><br><sub><code>bb jank</code></sub></td>
<td align="center"><img src="https://raw.githubusercontent.com/b12n-oss/raylib-pacman/main/docs/demos/jolt-example.gif" width="240" alt="Pac-Man running under Jolt"><br><sub><code>bb jolt</code></sub></td>
</tr>
</table>

> The game itself barely moves between them. What changes is the drawing layer, and only
> because each FFI carries a different amount across the boundary. A `Color` is four bytes
> passed by value: coffi hands it over as a map, babashka and Jolt pack it into an integer
> because their FFI moves scalars only, and jank will pass one quite happily but will not
> let a function *return* one. `DrawCircleSector` takes its centre by value, so two of the
> four cannot call it at all and build Pac-Man out of rlgl triangles instead. The trap
> worth knowing: raylib measures a sector from 0 = right and the Jolt wrapper from 0 = up,
> and getting that wrong still compiles, still runs, and simply points Pac-Man's mouth a
> quarter turn away from the direction he is walking.

</details>

<details>
<summary><b>Two more, and this time with numbers.</b> lisp-games, timed across the same four runtimes</summary>

[**lisp-games**](https://github.com/b12n-oss/lisp-games)
runs the same experiment on two smaller programs: borkdude's helitorus, which came out of
the babashka/ffi examples, and raylib's own mesh-instancing demo. Neither game is mine.
Each one is a port of somebody else's work, and the credit goes in the commit that adds
the code rather than into a follow-up task.
📖 [Docs &amp; guide](https://b12n-oss.github.io/lisp-games/)

<table>
<tr>
<td align="center"><img src="https://raw.githubusercontent.com/b12n-oss/lisp-games/main/docs/demos/helitorus-babashka.gif" width="240" alt="helitorus running under babashka"><br><sub><code>babashka</code></sub></td>
<td align="center"><img src="https://raw.githubusercontent.com/b12n-oss/lisp-games/main/docs/demos/helitorus-clojure.gif" width="240" alt="helitorus running under JVM Clojure"><br><sub><code>clojure</code></sub></td>
</tr>
<tr>
<td align="center"><img src="https://raw.githubusercontent.com/b12n-oss/lisp-games/main/docs/demos/helitorus-jank.gif" width="240" alt="helitorus running under jank"><br><sub><code>jank</code></sub></td>
<td align="center"><img src="https://raw.githubusercontent.com/b12n-oss/lisp-games/main/docs/demos/helitorus-jolt.gif" width="240" alt="helitorus running under Jolt"><br><sub><code>jolt</code></sub></td>
</tr>
</table>

> Pac-Man compares what each FFI will carry across the boundary. helitorus compares what
> it costs, because it rebuilds and projects the whole surface in Clojure every frame and
> reports compute and draw milliseconds separately. At the default 260 rings all four hold
> the same frame rate, since none of them is the bottleneck yet. Push to 900 and they
> separate: Clojure at 2.4 ms of compute, jank at 4.3, Jolt at 5.0, babashka at 18.0. Two
> of those numbers were badly wrong until an ordering that looked suspicious gave them
> away, which is the half of benchmarking nobody writes up. mesh-instancing measures the
> other axis, one draw call carrying two structs by value and a block of foreign memory.

</details>

<details>
<summary><b>And then on a phone.</b> raylib on a physical iPhone, 137 scenes, no JIT</summary>

[**raylib-ios**](https://github.com/jlt-commons/raylib-ios) puts
raylib and SDL2 on a physical iPhone, driven from the same Jolt. Two things make it work
and neither is obvious. raylib ships no iOS platform layer, so SDL2 compiled for iOS
becomes one, and both link into the executable as static archives. iOS forbids generating
code at run time, which rules out a JIT, so Chez's portable bytecode ships the interpreter
as the app instead and nothing is compiled on the device.

It started at seventeen scenes, running at 52 to 60 fps. Three of them were byte-identical
to files written for Android, sha256 verified, because the scene contract is pure and the
platform never appears in it. The guides are about what the device taught us rather than
what the code implied: calling into C was not the bottleneck, `GetFPS` returns a plausible
wrong number if you call it the obvious way, and one upstream bug report got withdrawn
after hardware contradicted a correct reading of the source.

raylib-ios is just the platform now. The scenes live in
[**raylib-ios-demo**](https://github.com/jlt-commons/raylib-ios-demo), which has grown to 137
of them, one for each desktop demo it was ported from. Every scene builds into an iPhone app
of its own, and a gallery app holds all of them behind a two-level menu.
📖 [Platform docs](https://jlt-commons.github.io/raylib-ios/) ·
[the 137 scenes](https://jlt-commons.github.io/raylib-ios-demo/)

<table>
<tr>
<td align="center"><img src="https://raw.githubusercontent.com/jlt-commons/raylib-ios/main/docs/images/kaleidoscope.gif" width="180" alt="Kaleidoscope"><br><sub>kaleidoscope</sub></td>
<td align="center"><img src="https://raw.githubusercontent.com/jlt-commons/raylib-ios/main/docs/images/spirograph.gif" width="180" alt="Spirograph"><br><sub>spirograph</sub></td>
<td align="center"><img src="https://raw.githubusercontent.com/jlt-commons/raylib-ios/main/docs/images/boids.gif" width="180" alt="Boids flocking"><br><sub>boids</sub></td>
<td align="center"><img src="https://raw.githubusercontent.com/jlt-commons/raylib-ios/main/docs/images/fireworks.gif" width="180" alt="Fireworks"><br><sub>fireworks</sub></td>
</tr>
</table>

That Android sibling is real now too. [**raylib-android**](https://github.com/jlt-commons/raylib-android),
ported by [yogthos](https://github.com/yogthos), runs the same scene contract as native arm64
code with no JVM anywhere in the app. I wired up its docs-engine guide. It hasn't touched real
hardware yet, so there are no screenshots to show for it.

</details>

<details>
<summary><b>Desktop GUI, the Replicant way.</b> glitter, a GTK4 renderer for Jolt</summary>

[**glitter**](https://github.com/jlt-commons/glitter) is a
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

</details>

<details>
<summary><b>Immediate-mode GUI, the other shape.</b> raygui-jlt, 24 examples</summary>

[**raygui-jlt**](https://github.com/jlt-commons/raygui-jlt)
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

</details>

<details>
<summary><b>The same suite, a different Clojure.</b> raygui-jnk, the jank twin</summary>

[**raygui-jnk**](https://github.com/b12n-oss/raygui-jnk)
is raygui-jlt's twin in [jank](https://jank-lang.org), which compiles Clojure through C++ and
LLVM rather than Chez Scheme. Same 24 examples, same names, same descriptions, so the two ports
read as one library seen through two implementations. What differs sits underneath: jank reaches
raygui as C++ rather than over an FFI, and the binding ships as an installable package. raygui
was not available to jank before this, which is why the sibling
[raylib-jnk](https://github.com/b12n-oss/raylib-jnk) substituted keyboard controls in
seventeen of its examples. Those can be real controls now, on one dependency line, with no
vendored copy and no build script of your own.
📖 [Docs &amp; full gallery](https://b12n-oss.github.io/raygui-jnk/)

<table>
<tr>
<td align="center"><img src="https://raw.githubusercontent.com/b12n-oss/raygui-jnk/main/docs/demos/tab-bar.png" width="240" alt="Tabs with close requests"><br><sub><code>bb tab-bar</code></sub></td>
<td align="center"><img src="https://raw.githubusercontent.com/b12n-oss/raygui-jnk/main/docs/demos/color-picker-hsv.png" width="240" alt="The HSV picker and panel"><br><sub><code>bb color-picker-hsv</code></sub></td>
<td align="center"><img src="https://raw.githubusercontent.com/b12n-oss/raygui-jnk/main/docs/demos/scroll-panel.png" width="240" alt="A scroll panel over oversized content"><br><sub><code>bb scroll-panel</code></sub></td>
</tr>
<tr>
<td align="center"><img src="https://raw.githubusercontent.com/b12n-oss/raygui-jnk/main/docs/demos/gui-state.png" width="240" alt="Forced states, alpha and lock"><br><sub><code>bb gui-state</code></sub></td>
<td align="center"><img src="https://raw.githubusercontent.com/b12n-oss/raygui-jnk/main/docs/demos/custom-input-box.png" width="240" alt="A hand-built input dialog over a panel"><br><sub><code>bb custom-input-box</code></sub></td>
<td align="center"><img src="https://raw.githubusercontent.com/b12n-oss/raygui-jnk/main/docs/demos/spinner-value-box.png" width="240" alt="Spinner and value box, clamped and typed"><br><sub><code>bb spinner-value-box</code></sub></td>
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

</details>

<details>
<summary><b>The same model, on native macOS.</b> glitter-uikit, over AppKit</summary>

[**glitter-uikit**](https://github.com/jlt-commons/glitter-uikit)
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

</details>

<details>
<summary><b>And in the terminal.</b> ftxui-jolt, over FTXUI</summary>

[**ftxui-jolt**](https://github.com/jlt-commons/ftxui-jolt) carries the
same reagent-style idea into a text console, over [FTXUI](https://github.com/ArthurSonzogni/FTXUI),
a C++ terminal UI library. Components are plain functions returning hiccup, and FTXUI's own
component tree renders them, so its focus handling, mouse support and event loop all come along
for free. FTXUI already rebuilds its whole tree from scratch on every frame, which is reagent's
model already, so there's no reconciler to write on top of it. Canvas drawing, gradients,
resizable splits and hoverable or floating windows are all in already.
📖 [Repo](https://github.com/jlt-commons/ftxui-jolt)

</details>

<details>
<summary><b>And then teaching it.</b> a free course in Lisp and game programming</summary>

[**b12n-gamedev-course**](https://github.com/burinc/b12n-gamedev-course)
is what those 513 raylib examples were for: a free course that teaches Lisp and game
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

</details>

<details>
<summary><b>The AWS SDK, unmodified.</b> aws-api-jolt</summary>

[**aws-api-jolt**](https://github.com/jlt-commons/aws-api-jolt) runs
the stock Maven release of [cognitect-labs/aws-api](https://github.com/cognitect-labs/aws-api) on
Jolt without forking or patching it. The library supplies the two things Jolt is missing, an HTTP
client and a host-class declaration, and nothing more. Its README is mostly the traps: which
aws-api versions fail on Jolt and why, measured against S3 on a live account, and the one
`tools.logging` placement that makes nine aws-api namespaces blame each other.

</details>

<details>
<summary><b>A different kind of port.</b> ebb, missionary on Jolt's fibers</summary>

[**ebb**](https://github.com/jlt-commons/ebb) carries
[missionary](https://github.com/leonoel/missionary), a functional effect and streaming system,
onto Jolt's Chez Scheme fibers rather than a C library. Every public var of missionary's API is
supported: the three process primitives `sp`, `ap` and `cp`, the propagator and reactor, and
every port and flow operator. The suite runs missionary's own tests almost unedited, 281 tests
and 1187 assertions, 196 of them lifted straight from missionary's own suite, so passing them
means missionary's actual guarantees hold on a different host.
📖 [Docs & guide](https://jlt-commons.github.io/ebb/) ·
[What differs from missionary](https://github.com/jlt-commons/ebb/blob/main/doc/conformance.md)

</details>

<details>
<summary><b>Jolt goes serverless.</b> an AWS Lambda custom runtime</summary>

[**lambda-mvp-jlt**](https://github.com/b12n-oss/lambda-mvp-jlt) runs
[Jolt](https://github.com/jolt-lang/jolt) as an AWS Lambda custom runtime, the same
`provided.al2023` contract that [awslabs/aws-lambda-cpp](https://github.com/awslabs/aws-lambda-cpp)
implements for C++. The loop itself is small: long-poll an invocation, run the handler, then
POST the response back, and the whole thing comes out to about 60 lines of Clojure over Jolt's
own HTTP client. `joltc build` compiles the handler and the runtime loop together into one
`bootstrap` binary, and a `jolt bench` task compares cold and warm boot time across memory tiers
against your own AWS account, because a number from someone else's account never tells you much.

</details>

<details>
<summary><b>And the CI half of that.</b> setup-jolt, a GitHub Action</summary>

[**setup-jolt**](https://github.com/jlt-commons/setup-jolt) is the
GitHub Action nobody had written yet: install jolt on a runner, whether that's Linux x86_64 or
macOS x86_64 and arm64, straight from its prebuilt releases with the published sha256 checked.
[DeLaGuardo/setup-clojure](https://github.com/DeLaGuardo/setup-clojure) already does the same job
for babashka and the Clojure CLI, so this fills the gap it left. It grew out of lambda-mvp-jlt
wanting its own CI to run through `jolt` instead of a separate babashka install, and it turned out
useful enough on its own to split out as its own repo.

</details>

<details>
<summary><b>Every public repo, in one list</b></summary>

[champaca](https://github.com/b12n-oss/champaca) (a Java runtime inside Jolt) ·
[jolt-openldk](https://github.com/jlt-commons/jolt-openldk) (Java libraries from Jolt through OpenLDK on SBCL) ·
[aws-api-jolt](https://github.com/jlt-commons/aws-api-jolt) (cognitect aws-api on Jolt, no fork) ·
[mcp-tkx](https://github.com/b12n-oss/mcp-tkx) (MCP clients and servers,
five protocol revisions) · [b12n-gamedev-course](https://github.com/burinc/b12n-gamedev-course) ·
[raylib-jlt](https://github.com/jlt-commons/raylib-jlt) · [raylib-jnk](https://github.com/b12n-oss/raylib-jnk) · [raylib-clj](https://github.com/b12n-oss/raylib-clj) ·
[raylib-jolt-demo](https://github.com/jlt-commons/raylib-jolt-demo) · [raylib-jank-demo](https://github.com/b12n-oss/raylib-jank-demo) · [raylib-clj-demo](https://github.com/b12n-oss/raylib-clj-demo) (every example, one project each) ·
[raylib-pacman](https://github.com/b12n-oss/raylib-pacman) · [lisp-games](https://github.com/b12n-oss/lisp-games) ·
[raylib-ios](https://github.com/jlt-commons/raylib-ios) · [raylib-ios-demo](https://github.com/jlt-commons/raylib-ios-demo) (137 scenes on an iPhone) ·
[glitter](https://github.com/jlt-commons/glitter) (Replicant-style GTK4 for Jolt) ·
[glitter-gl](https://github.com/jlt-commons/glitter-gl) (OpenGL geometry and shaders for it) ·
[glitter-uikit](https://github.com/jlt-commons/glitter-uikit) (the same model, on native macOS AppKit) ·
[uikit-demo](https://github.com/jlt-commons/uikit-demo) (a small glitter-uikit app with live exchange rates) ·
[glitter-core](https://github.com/jlt-commons/glitter-core) (glitter's reconciler, with no native deps) ·
[nexus-jolt](https://github.com/jlt-commons/nexus-jolt) (cjohansen/nexus, ported to Jolt) ·
[raygui-jlt](https://github.com/jlt-commons/raygui-jlt) (immediate-mode GUI for Jolt) ·
[raygui-jnk](https://github.com/b12n-oss/raygui-jnk) (the same suite, for jank) ·
[lambda-mvp-jlt](https://github.com/b12n-oss/lambda-mvp-jlt) (AWS Lambda custom runtime for Jolt) ·
[lambda-mvp-jnk](https://github.com/b12n-oss/lambda-mvp-jnk) (the same MVP in jank, as a container image) ·
[lambda-mvp-cljs](https://github.com/b12n-oss/lambda-mvp-cljs) (the same MVP in ClojureScript, on nodejs24.x) ·
[lambda-mvp-rst](https://github.com/b12n-oss/lambda-mvp-rst) (the same MVP in Jolt, its JSON built by real Rust via jolt-diplomat) ·
[lambda-mvp-bb](https://github.com/b12n-oss/lambda-mvp-bb) (the same MVP in Babashka, via blambda) ·
[ebb](https://github.com/jlt-commons/ebb) (missionary's effect and streaming system, ported to Jolt) ·
[ftxui-jolt](https://github.com/jlt-commons/ftxui-jolt) (reagent-style terminal UI for Jolt) ·
[setup-jolt](https://github.com/jlt-commons/setup-jolt) (GitHub Action to install jolt) ·
[dartclojure.el](https://github.com/burinc/dartclojure.el)
(Dart/Flutter → ClojureDart, in Emacs) · [viip](https://github.com/burinc/viip) ·
[Clojars](https://clojars.org/users/agilecreativity) ·
[RubyGems](https://rubygems.org/profiles/agilecreativity)

</details>

---

## 🌱 Open source

### jlt-commons

I started [**jlt-commons**](https://github.com/jlt-commons) in August 2026, a
community-led home for [Jolt](https://github.com/jolt-lang/jolt) libraries and tooling.

<details>
<summary><b>Why it exists, how projects join, and what's there so far</b></summary>

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

- [**raylib-jlt**](https://github.com/jlt-commons/raylib-jlt), the raylib bindings and examples
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
- [**ebb**](https://github.com/jlt-commons/ebb), the missionary port above.
  [Docs](https://jlt-commons.github.io/ebb/) publish through the org's own docs-engine.
- [**ftxui-jolt**](https://github.com/jlt-commons/ftxui-jolt), the terminal UI library above.
- [**awesome-jolt**](https://github.com/jlt-commons/awesome-jolt), the curated list for the
  whole ecosystem: language and compiler, official libraries, community projects, tooling
  and docs.
- [**ci-builds**](https://github.com/jlt-commons/ci-builds), fleet CI that builds every
  project against one jolt version and reports pass or fail in a single table. It exists
  because jolt v0.8.0 once reversed an FFI function's argument order, and two projects
  floating on `latest` broke silently.
- Since September: [**raylib-jolt-demo**](https://github.com/jlt-commons/raylib-jolt-demo),
  the 187 examples split out of raylib-jlt, and
  [**raylib-ios**](https://github.com/jlt-commons/raylib-ios) with
  [**raylib-ios-demo**](https://github.com/jlt-commons/raylib-ios-demo) for the iPhone.
  [**aws-api-jolt**](https://github.com/jlt-commons/aws-api-jolt) and
  [**jolt-openldk**](https://github.com/jlt-commons/jolt-openldk) are both from above.
  [**glitter-core**](https://github.com/jlt-commons/glitter-core) and
  [**nexus-jolt**](https://github.com/jlt-commons/nexus-jolt) came out of glitter, because Jolt
  inherits a dependency's native libraries transitively, and glitter-uikit would otherwise
  refuse to load without a GTK it never calls. [**uikit-demo**](https://github.com/jlt-commons/uikit-demo)
  puts glitter-uikit to work on a small app. One window ports *Learning Cocoa*'s 2001 currency
  converter, and another converts against live ECB rates.

The org isn't mostly mine anymore, and that was the point of starting it. It's at 44
public repos now. [yogthos](https://github.com/yogthos) has brought in more than I have
lately: [writ](https://github.com/jlt-commons/writ), a DSL that blocks AI mistakes through
proof, then [ensemble](https://github.com/jlt-commons/ensemble) for Erlang-style actors,
[slipstream](https://github.com/jlt-commons/slipstream) for GPU vector rendering,
[jolt-lsp](https://github.com/jlt-commons/jolt-lsp),
[jolt-nrepl-mcp](https://github.com/jlt-commons/jolt-nrepl-mcp),
[upbge-jolt](https://github.com/jlt-commons/upbge-jolt) and quite a few more, along with the
[raylib-android](https://github.com/jlt-commons/raylib-android) port. A couple are shared work, like
[jolt-metrics](https://github.com/jlt-commons/jolt-metrics), the code-metrics tool.

If you maintain something in Jolt and would rather it outlived your own free time, or
you want to build something and would rather not do it alone, the
[proposal queue](https://github.com/jlt-commons/meta) is open.

</details>

### b12n-oss

[**b12n-oss**](https://github.com/b12n-oss) is where my own open source lands.

<details>
<summary><b>The name, the repos, and why only public ones show</b></summary>

It is a
different thing from jlt-commons above, which is community-led and specific to Jolt. This
one is just mine, and the name is a numeronym for `burinchoomnuan`: the first letter, the
twelve in between, then the last, the same trick as `i18n` and `k8s`.

- [**mcp-tkx**](https://github.com/b12n-oss/mcp-tkx), a Clojure and ClojureScript library
  for building Model Context Protocol clients and servers. Five protocol revisions from
  `2024-11-05` through `2026-07-28`, and a single session can serve both the handshake
  era and the stateless one, so a server does not have to pick a side while its clients
  catch up. The newest revision drops the handshake entirely and replaces
  server-initiated requests with multi round-trip results, which is a real shift if you
  already run a server. It is a fork of [Metosin's
  mcp-toolkit](https://github.com/metosin/mcp-toolkit), with the namespaces deliberately
  unchanged so it stays a drop-in. Runs on the JVM, on Node, and on Babashka.
  [Docs](https://b12n-oss.github.io/mcp-tkx/), EPL-2.0.
- [**raygui-jnk**](https://github.com/b12n-oss/raygui-jnk) and
  [**raylib-jnk**](https://github.com/b12n-oss/raylib-jnk), the jank raygui and raylib
  suites above, moved here from my personal account and off their standalone
  `.b12n.app` domains. [Docs](https://b12n-oss.github.io/raygui-jnk/) and
  [docs](https://b12n-oss.github.io/raylib-jnk/) publish through
  [jlt-commons/docs-engine](https://github.com/jlt-commons/docs-engine).
- [**raylib-clj**](https://github.com/b12n-oss/raylib-clj), the JVM Clojure suite
  above, moved here the same way. Its docs moved off its own `raylib-clj.b12n.app`
  domain too; [docs](https://b12n-oss.github.io/raylib-clj/) publish through
  jlt-commons/docs-engine the same way.
- [**raylib-jank-demo**](https://github.com/b12n-oss/raylib-jank-demo) and
  [**raylib-clj-demo**](https://github.com/b12n-oss/raylib-clj-demo), where those two suites'
  examples went once the binding repos stopped holding them.
- [**raylib-pacman**](https://github.com/b12n-oss/raylib-pacman) and
  [**lisp-games**](https://github.com/b12n-oss/lisp-games), the four-runtime comparisons above.
- [**champaca**](https://github.com/b12n-oss/champaca), the Java runtime inside Jolt, and the
  newest one here. GPLv3 or later with the Classpath Exception, which it inherits from OpenLDK.

Only the public repos show up on this page. A fair number are still private while they get
to a state worth showing, so the list grows as they do.

</details>

### Upstream

Two fixes merged into [cisco/ChezScheme](https://github.com/cisco/ChezScheme/commits?author=burinc), the Scheme that Jolt compiles to, and seven into [atgreen/openldk](https://github.com/atgreen/openldk/commits?author=burinc). In [Jolt](https://github.com/jolt-lang/jolt/commits?author=burinc) itself, 137 commits since July and 79 merged pull requests. Counting wider, 197 pull requests over 52 projects, 170 of them merged.

<details>
<summary><b>What each fix was, project by project</b></summary>

The furthest down the stack I've gone is [**cisco/ChezScheme**](https://github.com/cisco/ChezScheme/commits?author=burinc),
the Scheme that Jolt compiles to. Matthew Flatt merged two of my pull requests there, and
both of them came out of the embedding work further up this page.
[#1076](https://github.com/cisco/ChezScheme/pull/1076) fixes what happens when Chez is embedded
in a process that already handles `SIGSEGV`, the way .NET and Java runtimes do. `Sscheme_init`
used to replace the host's handler, so a null dereference on one of the host's own threads
aborted the whole process even though no Scheme code was running. Now the fault goes back to
the handler that was there first.
[#1091](https://github.com/cisco/ChezScheme/pull/1091) repairs where arm64 puts foreign-procedure
arguments once they spill past the registers onto the stack. I checked 3066 generated C
signatures against clang on macOS arm64, and 650 of them came out wrong before the fix and none
after. Its new tests then failed on every x86_64 job, which turned up a second bug on that side,
where a stack struct of an awkward size like 3, 7 or 13 bytes wrote over the next argument. So
the pull request ended up fixing both architectures. A third one, keeping code in a single
aligned region on Apple arm64, got closed upstream, and the same fix landed in Jolt instead.

[**atgreen/openldk**](https://github.com/atgreen/openldk/commits?author=burinc) got seven pull
requests from me in October, all merged by Anthony Green. They're what fell out of building
jolt-openldk and then champaca on top of it: a JIT-failure loop, JMOD zip offsets, `String`
bytes stored signed the way Java stores them, and enough of `NativeLibraries.load` and zlib's
macOS name for `java.nio.file` to work on a Mac. `Instant.now()` needed
`VM.getNanoTimeAdjustment`, and two threading fixes stopped waiting threads from sleeping
through the wake-up they were waiting for.

[**jolt-lang/jolt**](https://github.com/jolt-lang/jolt/commits?author=burinc) itself is where
most of the volume goes, with 137 commits since July and 79 merged pull requests. The summer
was the FFI and the toolchain: `:string` carrying NULL in both directions, fiber-parking for
subprocess pipe I/O, a cross-compilation path with a CI cross-smoke workflow behind it, shell
completion in zsh, bash and fish, a rolling nightly prerelease, and `jolt build --signable` for
an executable `codesign --verify --strict` will accept. October and November went deeper.
There's a `jolt.debug` namespace that hands you a throwable's frames along with their locals, an
nREPL `*eval-wrapper*` hook, and a `jolt build --target` that compiles for a 32-bit machine's
fixnum width, which is part of how Clojure ended up on a Wii. On top of that came a cheaper
double-to-integer cast that tests the fixnum window inline, plus `java.io.RandomAccessFile`, a
bundled `cheshire.core` and a long tail of JVM behaviours matched one at a time. The dot-form
fix from September needed a second patch from the maintainer for the runtime half, which is
still a fair description of how much of the compiler I have left to learn.

Building on it turns up patches next door too, across the jolt-lang org:
[nrepl](https://github.com/jolt-lang/nrepl/pulls?q=author%3Aburinc) streaming eval output as it
flushes and answering lookup and completion the way editors expect,
[ring-chez-adapter](https://github.com/jolt-lang/ring-chez-adapter/pull/70) verifying client
certificates for mTLS, [http-client](https://github.com/jolt-lang/http-client/pull/44) getting a
working PKCS12 `KeyStore`, [multipart](https://github.com/jolt-lang/multipart/pull/3) finding its
boundary in linear time, and older ones in
[xml](https://github.com/jolt-lang/xml/pull/2), [glimmer](https://github.com/jolt-lang/glimmer/pull/5)
and [jolt-diplomat](https://github.com/jolt-lang/jolt-diplomat/pull/1).

Counting wider: across public repositories outside my own accounts and organizations,
[@burinc](https://github.com/burinc) has 197 pull requests over 52 projects, 170 of them
merged. That number needs some unpacking before it means much. 31 are the Clojure Civitas
articles listed above, which land as pull requests to the site. Another 106 are the jolt-lang
work, spread across 13 of its repos, and that part has more than tripled since September. That
leaves 60 across 38 other projects, and those are the ones I would actually call upstream:
nearly always a bug I hit while building something else, filed against the tool that hit it.
[cisco/ChezScheme](https://github.com/cisco/ChezScheme),
[atgreen/openldk](https://github.com/atgreen/openldk),
[weavejester/cljfmt](https://github.com/weavejester/cljfmt),
[clj-commons/antq](https://github.com/clj-commons/antq),
[seancorfield/deps-new](https://github.com/seancorfield/deps-new),
[djblue/portal](https://github.com/djblue/portal),
[babashka/process](https://github.com/babashka/process),
[babashka/pod-babashka-aws](https://github.com/babashka/pod-babashka-aws),
[funcool/promesa](https://github.com/funcool/promesa),
[lambdaisland/classpath](https://github.com/lambdaisland/classpath),
[zero-one-group/geni](https://github.com/zero-one-group/geni),
[jank-lang/jank](https://github.com/jank-lang/jank) and
[raysan5/raylib](https://github.com/raysan5/raylib) are the names a Clojure reader is most
likely to know. Four in five of the 197 landed in 2025 and 2026.

Still open: [bhauman/clojure-mcp-light#33](https://github.com/bhauman/clojure-mcp-light/pull/33)
teaches its file-extension and nREPL-process detection to recognize `.jolt` files and jolt's own
REPL, alongside a timbre config fix. clojure-mcp-light is where `clj-nrepl-eval` comes from, so
once it lands, Jolt gets the same LLM-assisted REPL workflow Clojure already has.

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

</details>

> 📌 **Two handles, one person.** [@agilecreativity](https://github.com/agilecreativity)
> is my original account, opened in 2013 and mostly Ruby until I found Clojure in early 2016.
> Both eras live there, which is why the list above points at both handles.
> [@burinc](https://github.com/burinc) is where I work now.

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
