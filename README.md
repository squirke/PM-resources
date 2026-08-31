# PM Resources

A curated list of resources, AI skills, books, and frameworks for Product Managers.

## Table of Contents

- [AI Skills for Product Managers](#ai-skills-for-product-managers)
  - [Skills Overview](#skills-overview)
  - [Using the Skills](#using-the-skills)
  - [Python Utilities](#python-utilities)
- [Books](#books)
  - [New to Product? Start Here](#new-to-product-start-here)
  - [More Product Management Basics](#more-product-management-basics)
  - [Leading Product People & Product Organizations](#leading-product-people--product-organizations)
  - [Communities of Practice](#communities-of-practice)
  - [Artificial Intelligence](#artificial-intelligence)
  - [Broadening your Product Horizon](#broadening-your-product-horizon)
  - [Coaching & Psychology](#coaching--psychology)
- [Articles & Blogs](#articles--blogs)
- [Tools & Frameworks](#tools--frameworks)
- [Communities](#communities)

---

## AI Skills for Product Managers

A collection of agentic skills, interactive workflows, templates, and scripts designed for Product Managers using AI coding assistants (Claude Code, Antigravity, Cursor, etc.) or standalone CLI workflows.

### Skills Overview

| Skill | Description | Type | Key Assets / Tools |
|---|---|---|---|
| **[Agile Product Owner](skills/agile-product-owner/)** | Backlog management, sprint planning, user story templates, and automated story generation. | Workflow | `user_story_generator.py`, sprint planning guide, user story templates |
| **[Organic Growth Advisor](skills/organic-growth-advisor/)** | Organic growth loops, acquisition & retention models, and growth strategy templates. | Workflow | Growth loop templates, sample teardowns |
| **[PM Skill Creator](skills/pm-skill-creator/)** | Meta-skill to design, scope, and structure new PM skills through guided conversation. | Interactive | Skill authoring guidelines & templates |
| **[PRD Development](skills/prd-development/)** | End-to-end PRD creation connecting problem framing, user research, solution specs, and success criteria. | Workflow | `template.md`, sample PRD |
| **[Prioritization Advisor](skills/prioritization-advisor/)** | Interactive advisor to select the right prioritization framework (RICE, ICE, Value vs Effort, MoSCoW, Kano) based on product stage. | Interactive | Framework comparison & decision engine |
| **[Product Manager Toolkit](skills/product-manager-toolkit/)** | Comprehensive toolkit covering feature prioritization, customer interview analysis, and PRD templates. | Toolkit | `rice_prioritizer.py`, `customer_interview_analyzer.py`, PRD templates |
| **[Product Strategist](skills/product-strategist/)** | Strategic leadership toolkit for Head of Product to generate company-to-team cascaded OKRs and competitive analyses. | Strategic | `okr_cascade_generator.py`, OKR templates, 5 strategy models |
| **[User Story Mapping](skills/user-story-mapping/)** | Jeff Patton 2D user story mapping framework to visualize activities, steps, tasks, and release slices. | Component | `template.md`, sample story map |

### Using the Skills

- **With Claude Code / Antigravity / Agentic AI**: Point your AI assistant to the relevant `SKILL.md` in any skill directory, or load them into your AI skills configuration directory.
- **Standalone Templates**: Browse the `assets/`, `references/`, and `examples/` folders in each skill directory for ready-to-use Markdown templates.

### Python Utilities

Several skills include executable CLI tools in their `scripts/` directories:

- **OKR Cascade Generator**:
  ```bash
  python3 skills/product-strategist/scripts/okr_cascade_generator.py growth --teams "Growth,Platform,Mobile,Data"
  ```
- **RICE Feature Prioritizer**:
  ```bash
  python3 skills/product-manager-toolkit/scripts/rice_prioritizer.py sample --capacity 10 --output text
  ```
- **User Story Generator**:
  ```bash
  python3 skills/agile-product-owner/scripts/user_story_generator.py
  ```
- **Customer Interview Analyzer**:
  ```bash
  python3 skills/product-manager-toolkit/scripts/customer_interview_analyzer.py
  ```

---

## Books

### New to Product? Start here

- **Matt LeMay** - *Product Management in Practice* - [Goodreads](https://www.goodreads.com/book/show/36563477)
- **Joshua Seiden** - *Outcomes Over Output* - [Goodreads](https://www.goodreads.com/book/show/45273233)
- **Melissa Perri** - *Escaping the Build Trap* - [Goodreads](https://www.goodreads.com/book/show/33369253-escaping-the-build-trap)
- **Teresa Torres** - *Continuous Discovery Habits* - [Goodreads](https://www.goodreads.com/book/show/58046715-continuous-discovery-habits)
- **Marty Cagan** – *Inspired* - [Goodreads](https://www.goodreads.com/book/show/48745535-inspired)

### More Product Management Basics

- **Christina Wodtke** – *The team that managed itself* - [Goodreads](https://www.goodreads.com/book/show/48560062-the-team-that-managed-itself)
- **Jeff Patton** – *User Story Mapping* - [Goodreads](https://www.goodreads.com/book/show/27109661-user-story-mapping)
- **Bruce McCarthy, Melissa Appel** – *Aligned: Stakeholder Management* - [Goodreads](https://www.goodreads.com/book/show/171661144-aligned)
- **Rich Mironov** - *The Art of Product Management, Second Edition* - [Goodreads](https://www.goodreads.com/book/show/208293497-the-art-of-product-management-second-edition)
- **Bland, Osterwalder** – *Testing Business Ideas* - [Goodreads](https://www.goodreads.com/book/show/9781119551447)
- **Steve Krug** – *Don't make me think (revisited)* - [Goodreads](https://www.goodreads.com/book/show/30213252-don-t-make-me-think)
- **April Dunford** - *Obviously Awesome: How to Nail Product Positioning* - [Goodreads](https://www.goodreads.com/book/show/59323708-obviously-awesome)
- **Jake Knapp, John Zeratsky, Braden Kowitz** – *Sprint* - [Goodreads](https://www.goodreads.com/book/show/28244571-sprint)
- **Osterwalder and others** – *Business Model Generation* - [Goodreads](https://www.goodreads.com/book/show/9780470876411)
- **Eric Ries** – *The lean startup* - [Goodreads](https://www.goodreads.com/book/show/24464406-the-lean-startup)
- **Nacho Bassino** - *Product Direction* - [Goodreads](https://www.goodreads.com/book/show/57578987-product-direction)
- **Guy Kawasaki** – *Selling the dream* - [Goodreads](https://www.goodreads.com/book/show/237837.Selling_the_Dream)
- **Itamar Gilad** - *Evidence-Guided* - [Goodreads](https://www.goodreads.com/book/show/200096725-evidence-guided)
- **Andrea Saez & Dave Martin** - *The Product Momentum Gap* - [Goodreads](https://www.goodreads.com/book/show/9783982684918)
- **Steve Krug** – *Rocket surgery made easy* - [Goodreads](https://www.goodreads.com/book/show/6658783-rocket-surgery-made-easy)
- **Ash Maurya** – *Running Lean* - [Goodreads](https://www.goodreads.com/book/show/13078769-running-lean)
- **David J. Anderson** – *Kanban* - [Goodreads](https://www.goodreads.com/book/show/9780984521401)
- **Dan Roam** – *The back of the napkin* - [Goodreads](https://www.goodreads.com/book/show/2420301)
- **Marc Abraham** - *Managing Product = Managing Tension* - [Goodreads](https://www.goodreads.com/book/show/9781839521966)
- **Randy Silver** - *What Do We Do Now? A product manager's guide to strategy in the time of crisis* - [Goodreads](https://www.goodreads.com/book/show/9781800684010)
- **(DE) Sascha Hoffmann et al.** – *Digitales Produktmanagement: Methoden–Instrumente–Praxisbeispiele* - [Goodreads](https://www.goodreads.com/book/show/9783658306281)
- **(DE) Sven Röpstorff & Robert Wiechmann** – *Scrum in der Praxis* - [Goodreads](https://www.goodreads.com/book/show/9783864908804)
- **(DE) Tom Rath** – *Entwickle deine Stärken* - [Goodreads](https://www.goodreads.com/book/show/39712298-entwickle-deine-st-rken-mit-dem-strengthsfinder-2-0)
- **(DE) Kommunikationslotsen** – *Bikablo 2.0* - [Goodreads](https://www.goodreads.com/book/show/9783940315359)

### Leading Product People & Product Organizations

- **Petra Wille** - *STRONG Product People: A Complete Guide to Developing Great Product Managers* - [Goodreads](https://www.goodreads.com/book/show/56794688-product-people)
- **Martin Eriksson** – *The Decision Stack* - [Goodreads](https://www.goodreads.com/book/show/9781067613211)
- **Melissa Perri and Denise Tilles** - *Product Operations* - [Goodreads](https://www.goodreads.com/book/show/199368360-product-operations)
- **Julie Zou** – *The Making of a Manager* - [Goodreads](https://www.goodreads.com/book/show/38821039-the-making-of-a-manager)
- **Marty Cagan** - *EMPOWERED: Ordinary People, Extraordinary Products* - [Goodreads](https://www.goodreads.com/book/show/56259430-empowered)
- **Marty Cagan et. al.** - *TRANSFORMED* - [Goodreads](https://www.goodreads.com/book/show/56447603-transformed)
- **Cennydd Bowles** - *Future Ethics* - [Goodreads](https://www.goodreads.com/book/show/9781999601911)
- **Christina Wodtke** – *Radical Focus* - [Goodreads](https://www.goodreads.com/book/show/57802947-radical-focus-second-edition)
- **Jeff Gothelf, Josh Seiden** – *Who Does What By How Much?: A Practical Guide to Customer-Centric OKRs* - [Goodreads](https://www.goodreads.com/book/show/210407220-who-does-what-by-how-much)
- **Kate Leto** - *Hiring Product Managers* - [Goodreads](https://www.goodreads.com/book/show/55204734-hiring-product-managers)
- **Donna Lichaw** - *The Leader's Journey: Transforming Your Leadership to Achieve the Extraordinary* - [Goodreads](https://www.goodreads.com/book/show/9781959029137)
- **Janice & Jason Fraser** - *Farther Faster and Far Less Drama* - [Goodreads](https://www.goodreads.com/book/show/61494019-farther-faster-and-far-less-drama)
- **Richard Banfield, Martin Eriksson, Nate Walkingshaw** – *Product Leadership* - [Goodreads](https://www.goodreads.com/book/show/30014114-product-leadership)
- **Alexandra Jamieson, Bob Gower** - *Radical Alignment* - [Goodreads](https://www.goodreads.com/book/show/52079355-radical-alignment)
- **Nancy Kline** - *Time to Think: Listening to Ignite the Human Mind* - [Goodreads](https://www.goodreads.com/book/show/18937446-time-to-think)
- **David L. Bradford, Carole Robin** - *Connect: Building Exceptional Relationships with Family, Friends and Colleagues* - [Goodreads](https://www.goodreads.com/book/show/140193873)
- **Ben Horowitz** – *What you do is who you are* - [Goodreads](https://www.goodreads.com/book/show/45885801-what-you-do-is-who-you-are)
- **Schmidt, Rosenberg, Eagle** – *Trillion Dollar Coach* - [Goodreads](https://www.goodreads.com/book/show/45016469-trillion-dollar-coach)
- **John Doerr** – *Measure what matters* - [Goodreads](https://www.goodreads.com/book/show/39286958)
- **John Maeda & Becky Bermont** – *Redesigning Leadership* - [Goodreads](https://www.goodreads.com/book/show/10281070)
- **Gino Wickman** – *Traction (get a grip on your business)* - [Goodreads](https://www.goodreads.com/book/show/13236324-traction)
- **Ben Horowitz** – *The hard thing about hard things* - [Goodreads](https://www.goodreads.com/book/show/20359768-the-hard-thing-about-hard-things)
- **Daniel Stillman** - *Good Talk* - [Goodreads](https://www.goodreads.com/book/show/53511223-good-talk)
- **Douglas Ferguson & John Fitch** - *Magical Meetings* - [Goodreads](https://www.goodreads.com/book/show/57862542-the-non-obvious-guide-to-magical-meetings)
- **(DE) J.R. Edlund** – *Monkey Management* - [Goodreads](https://www.goodreads.com/book/show/9783869910383)
- **(DE) Reinhard K. Sprenger** – *Das anständige Unternehmen: Was richtige Führung ausmacht – und was sie weglässt* - [Goodreads](https://www.goodreads.com/book/show/26830429-das-anst-ndige-unternehmen)

### Communities of Practice

- **Petra Wille & Melissa Suzuno** - *STRONG Product Communities: The Essential Guide to Product Communities of Practice* - [Goodreads](https://www.goodreads.com/book/show/9783982235189)
- **Emily Webber** - *Building Successful Communities of Practice* - [Goodreads](https://www.goodreads.com/book/show/29155800-building-successful-communities-of-practice)

### Artificial Intelligence

- **Barry O'Reilly** – *Artificial Organizations* - [Goodreads](https://www.goodreads.com/book/show/250017055-artificial-organizations)
- **Elaine Kasket** – *All the Ghosts in the Machine: The Digital Afterlife of Your Personal Data* - [Goodreads](https://www.goodreads.com/book/show/45995273)
- **Karen Hao** – *Empire of AI* - [Goodreads](https://www.goodreads.com/book/show/230842820-empire-of-ai)

### Broadening your Product Horizon

- **Elaine Kasket** – *Reboot: Reclaiming Your Life in a Tech-Obsessed World* - [Goodreads](https://www.goodreads.com/book/show/9781783967568)
- **Susanne Kaiser** – *Architecture for Flow* - [Goodreads](https://www.goodreads.com/book/show/239941967-architecture-for-flow)
- **April Dunford** - *Sales Pitch* - [Goodreads](https://www.goodreads.com/book/show/196811879)
- **Danielle Barnes, Christina Wodtke** – *Present Yourself: Proven Strategies for Authentic and Impactful Public Speaking* - [Goodreads](https://www.goodreads.com/book/show/9798989523405)
- **Andy Budd** - *The Growth Equation: How Early Stage Startups Can Build a Powerful Engine for Growth* - [Goodreads](https://www.goodreads.com/book/show/217830934-the-growth-equation)
- **Amber Case** – *Calm Technology* - [Goodreads](https://www.goodreads.com/book/show/28359833-calm-technology)
- **Heather Willems, Nora Herting** – *Draw Your Big Idea* - [Goodreads](https://www.goodreads.com/book/show/26031175-draw-your-big-idea)
- **Alexandra Jamieson, Bob Gower** - *Radical Alignment* - [Goodreads](https://www.goodreads.com/book/show/52079355-radical-alignment)
- **Michael Bungay Stanier** - *Advice Trap* - [Goodreads](https://www.goodreads.com/book/show/50550775-the-advice-trap)
- **W. Timothy Gallwey** - *The Inner Game of Tennis: The Classic Guide to the Mental Side of Peak Performance* - [Goodreads](https://www.goodreads.com/book/show/1471595.The_Inner_Game_Of_Tennis)
- **Jim Kalbach** – *Mapping Experiences* - [Goodreads](https://www.goodreads.com/book/show/30206219)
- **Derek Sivers** – *Anything you want* - [Goodreads](https://www.goodreads.com/book/show/27436585)
- **Nancy Duarte & Patti Sanchez** – *Illuminate* - [Goodreads](https://www.goodreads.com/book/show/28582290-illuminate)
- **Giorgia Lupi und Stefanie Posavec** – *Dear Data* - [Goodreads](https://www.goodreads.com/book/show/28465052-dear-data)
- **John Maeda** – *The laws of simplicity* - [Goodreads](https://www.goodreads.com/book/show/54456008-the-laws-of-simplicity)
- **Aaron Ross & Marylou Tyler** – *Predictable Revenue* - [Goodreads](https://www.goodreads.com/book/show/18899679-predictable-revenue)
- **Guy Kawasaki** – *The art of the start* - [Goodreads](https://www.goodreads.com/book/show/17774027-the-art-of-the-start)
- **David Marquet** – *Turn the ship around* - [Goodreads](https://www.goodreads.com/book/show/26917955-turn-the-ship-around)
- **Malcolm Gladwell** – *The tipping point* - [Goodreads](https://www.goodreads.com/book/show/17167952)
- **37signals** – *Getting Real* - [Goodreads](https://www.goodreads.com/book/show/11553059-getting-real)
- **Jaron Lanier** – *Who owns the future* - [Goodreads](https://www.goodreads.com/book/show/18804368-who-owns-the-future)
- **Jason Fried & David Heinemeier Hansson** – *Rework* - [Goodreads](https://www.goodreads.com/book/show/7861053-rework)
- **Tony Russel-Rose & Tyler Tate** – *Designing the search experience* - [Goodreads](https://www.goodreads.com/book/show/9780123969811)
- **Jim Collins** – *Good to Great* - [Goodreads](https://www.goodreads.com/book/show/4113)
- **Jason Fried & David Heinemeier Hansson** – *Remote (office not required)* - [Goodreads](https://www.goodreads.com/book/show/18802899-remote)
- **Sheryl Sandberg** – *Lean in* - [Goodreads](https://www.goodreads.com/book/show/19546126-lean-in)
- **Jim Collins & Jerry I. Porras** – *Built to last* - [Goodreads](https://www.goodreads.com/book/show/2361505.Built_to_Last_)
- **Nir Eyal** – *Hooked* - [Goodreads](https://www.goodreads.com/book/show/23586542)
- **Patrick M. Lencioni** – *The Five Dysfunctions of a Team: A Leadership Fable* - [Goodreads](https://www.goodreads.com/book/show/21343)
- **Logan, King** – *Tribal Leadership* - [Goodreads](https://www.goodreads.com/book/show/25818373-tribal-leadership)
- **Nassim Nicholas Taleb** – *Antifragile: Things That Gain from Disorder* - [Goodreads](https://www.goodreads.com/book/show/19723223-antifragile)
- **Osterwalder, Pigneur, Bernarda, Smith** – *Value Proposition Design* - [Goodreads](https://www.goodreads.com/book/show/23232900-value-proposition-design)
- **Dambisa Moyo** – *Winner take all* - [Goodreads](https://www.goodreads.com/book/show/15956433-winner-take-all)
- **Timothy Ferriss** – *The 4-Hour Workweek* - [Goodreads](https://www.goodreads.com/book/show/3134376-the-4-hour-workweek)
- **(DE) Klaus Henning** – *Die Kunst der kleinen Lösung* - [Goodreads](https://www.goodreads.com/book/show/23927334-die-kunst-der-kleinen-l-sung)
- **(DE) Bascha Mika** – *Die Feigheit der Frauen* - [Goodreads](https://www.goodreads.com/book/show/9783570100707)
- **(DE) Ferdinand von Schirach** - *Jeder Mensch* - [Goodreads](https://www.goodreads.com/book/show/57616302-jeder-mensch)
- **(DE) Tupoka Ogette** - *Exit Racism* - [Goodreads](https://www.goodreads.com/book/show/35213270)

### Coaching & Psychology

- **Robert Ellis** – *Coaching From Essence* - [Goodreads](https://www.goodreads.com/book/show/9780971752221)
- **Dianne R. Stober und Anthony M. Grant** - *Evidence Based Coaching Handbook* - [Goodreads](https://www.goodreads.com/book/show/9780471720867)
- **Rick Rubin** - *The Creative Act: A Way of Being* - [Goodreads](https://www.goodreads.com/book/show/60965426-the-creative-act)
- **James M. Lang** - *Small Teaching: Everyday Lessons from the Science of Learning* - [Goodreads](https://www.goodreads.com/book/show/58664292)
- **Tony Llewellyn** – *Team Coaching Toolkit* - [Goodreads](https://www.goodreads.com/book/show/9781910056653)
- **Michael Bungay Stanier** – *The Coaching Habit* - [Goodreads](https://www.goodreads.com/book/show/36684893-the-coaching-habit)
- **Kaye, Giulioni** – *Help them grow or watch them go* - [Goodreads](https://www.goodreads.com/book/show/42866295-help-them-grow-or-watch-them-go)
- **Daniel Goleman** – *Emotional Intelligence* - [Goodreads](https://www.goodreads.com/book/show/26329.Emotional_Intelligence)
- **Michael M. Lombardo** – *FYI: For Your Improvement* - [Goodreads](https://www.goodreads.com/book/show/55824028-fyi-for-your-improvement)
- **Gabor Maté** - *The Myth of Normal: Trauma, Illness, and Healing in a Toxic Culture* - [Goodreads](https://www.goodreads.com/book/show/58764796-the-myth-of-normal)
- **Daniel Kahneman** – *Thinking, Fast and Slow* - [Goodreads](https://www.goodreads.com/book/show/12385458-thinking-fast-and-slow)
- **Rich Litvin & Steve Chandler** - *The Prosperous Coach* - [Goodreads](https://www.goodreads.com/book/show/20110915-the-prosperous-coach)
- **(DE) Daniel Kahneman** – *Schnelles Denken, langsames Denken* - [Goodreads](https://www.goodreads.com/book/show/34853084-schnelles-denken-langsames-denken)
- **(DE) Thomas Rückerl** – *Coaching mit NLP-Werkzeugen* - [Goodreads](https://www.goodreads.com/book/show/9783527503513)
- **(DE) Thomas Binder** – *Ich-Entwicklung für effektives Beraten* - [Goodreads](https://www.goodreads.com/book/show/28049376-ich-entwicklung-fur-effektives-beraten-interdisziplinare-beratungsforsc)
- **(DE) Carmen Kindl-Beilfuß** – *Fragen können wie Küsse schmecken* - [Goodreads](https://www.goodreads.com/book/show/7966837-fragen-k-nnen-wie-k-sse-schmecken-hauptbd)
- **(DE) Eric Berne** – *Spiele der Erwachsenen: Psychologie der menschlichen Beziehungen* - [Goodreads](https://www.goodreads.com/book/show/13509277-spiele-der-erwachsenen)
- **(DE) Lothar Seiwert & Friedbert Gay** – *Das neue 1×1 der Persönlichkeit* - [Goodreads](https://www.goodreads.com/book/show/3048352-das-neue-1x1-einmaleins-der-pers-nlichkeit)
- **(DE) Richard Bents & Reiner Blank** – *Typisch Mensch* - [Goodreads](https://www.goodreads.com/book/show/12427916-typisch-mensch)
- **(DE) Daniel Goleman** – *Emotionale Führung* - [Goodreads](https://www.goodreads.com/book/show/9783548364667)
- **(DE) Rolf Dobelli** – *Die Kunst des klaren Denkens* - [Goodreads](https://www.goodreads.com/book/show/72332138)
- **(DE) Seyda Kurt** - *HASS. Von der Macht eines widerständigen Gefühls* - [Goodreads](https://www.goodreads.com/book/show/75328576-hass)

---

## Articles & Blogs

*Coming soon...*

---

## Tools & Frameworks

*See [AI Skills for Product Managers](#ai-skills-for-product-managers) above for interactive tools and templates.*

---

## Communities

*Coming soon...*

---

*Last updated: August 2026*
