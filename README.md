# sflean.group

Hello! We're a friendly group of Lean enthusiasts who meet weekly for a talk or presentation, followed by discussion, hands-on learning, and group projects.

Our members include researchers, industry professionals, students, startup founders, consultants, curious community members — and hopefully YOU!

One of the great things about Lean is that it attracts people from many disciplines: math, CS theory, AI, software engineering, cryptography, physics, and economics, to name a few. Our members come from all of these backgrounds, and we welcome others with any level of experience, [including first timers](#im-totally-new-to-lean-how-do-i-get-started).

While Lean is our focus, don't be surprised if you get pulled into conversations about programming languages, formal methods, or AI-assisted coding.

**When:** Monday evenings at 7pm. Sessions run 1–2 hours, with the "official" portion lasting about an hour.

**Where:** [Mox SF](https://moxsf.com/) (1680 Mission St, San Francisco)

[Luma](https://luma.com/user/usr-IIea6zgV4whGCMX) has more information about upcoming talks and events.

Join the Discord to stay up to date on events and discussions — concatenate `https://discord.gg/` and `bXNPh` and `Qyjfe` and paste into your browser. All our communication happens on Discord.


## Past Session Conversation Topics

- **06 Jul 2026:**
  - Gerhard presented on aristotle
- **29 Jun 2026:**
  - ClocksSugars presented on Type Theory [slides][6] [video][7] [agda+lean code][8]
- **22 Jun 2026:**
  - Will presented "Zero to Type Theory in 1 Hour" [slides][4] [video][5]
- **15 Jun 2026:**
  - Rado presented on Filters 2 in Mathlib and [jacobian-claude][3]
- **8 Jun 2026:**
  - Rado presented on Filters in Mathlib [gslides][2] 
- **1 Jun 2026:**
  - Elliott presented on the proof of the independence of the continuum
	hypothesis
- **30 Mar 2026:**
  - Rado: [Zorn's lemma formalization][1] - took a Lean statement from
	Tao's Analysis and prodded models until they got it to proofcheck
  - Sudoku solvers and verso (lean docs tool)
  - Pablo: von neumann game theory & nash equilib - constructively prove
	that a nash equilib always exists
  - Will: Property-based testing library
- **23 Mar 2026:**
  - New format: let's demo / present!
  - MathInc did an autonomous lean formalization of dimension-24
	(following-up 2022 Fields Medal Maryna Viazovska), which raises
	interesting questions about the future of mathlib
  - New tools: Gauss, Aristotle, Leanstral
  - LLM chatter: Gemini seems smartest but has a confidence issue, codex is
	the practically smartest at the moment
  - lean-libclang - goal of creating a lean bindgen
  - [Equational Theories distillation
	challenge](https://terrytao.wordpress.com/2026/03/13/mathematics-distillation-challenge-equational-theories/)
	from Terry Tao
  - [Interview of Tao on Lean](https://www.youtube.com/watch?v=Q8Fkpi18QXU)
  - [Gowers'
	Puzzles](https://gowers.wordpress.com/2026/03/20/group-and-semigroup-puzzles-and-a-possible-polymath-project/)
	are some turing machine word games from a mathematician
- **9 Feb 2026:**
  - Lean metaprogramming from Perry
  - Number theory part 3 from Gerhard
- **2 Feb 2026:**
  - Number theory part 2 from Gerhard
- **26 Jan 2026:**
  - Number theory part 1 from Gerhard

## I'm totally new to Lean! How do I get started?

If you have time before you arrive, try installing the [Natural Number Game](https://github.com/leanprover-community/NNG4) locally. You'll want to open the repo in a VSCode devcontainer and open http://localhost:3000 in your browser.

If you'd like to skip straight to the math, clone Terence Tao's repo:
1. `git clone https://github.com/teorth/analysis`
2. `cd analysis/analysis`
3. `lake exe cache get`
4. Start poking around `Section_2_2.lean` and filling out the `sorry`s.

Good luck! You can ask for help in the Discord server.


[1]: https://en.wikipedia.org/wiki/Zorn%27s_lemma
[2]: https://docs.google.com/presentation/d/1w6o-3BBk3Sn52XLOwiuIGfwvaw3x6VZj2Ya5fjX2Id8/edit
[3]: http://github.com/rkirov/jacobian-claude
[4]: https://docs.google.com/presentation/d/1KliDGPNfI49_dib6Nbn1Gri8qx09_GlhunjuC_7ieS4/edit
[5]: https://www.youtube.com/watch?v=x6GALs_x9Do
[6]: TypeTheoryForAgdaNoPause.pdf
[7]: https://youtu.be/k2MOU7Q8N4w
[8]: https://github.com/rkirov/agda-lean
