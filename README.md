# PM Resources

A curated list of resources, AI skills, books, and frameworks for product managers.

## Table of Contents

- [Claude AI Skills and Utilities](#claude-ai-skills-and-utilities)
  - [Skills](#skills)
  - [Command-Line Utilities](#command-line-utilities)
- [Reading List](#reading-list)
  - [Working Products Conference #11, Hamburg 2026](#working-products-conference-11-hamburg-2026)
  - [Product Management Library](#product-management-library)

---

## Claude AI Skills and Utilities

A collection of agentic workflows, templates, and command-line tools for product managers using Claude Code or another AI coding assistant.

Open a skill directory to read its `SKILL.md` instructions. You can also use the templates in its `assets/`, `references/`, and `examples/` folders without running an AI assistant.

### Skills

- **[Agile Product Owner](skills/agile-product-owner/)**: Workflow for backlog management, sprint planning, and user story creation. Includes a story generator, planning guidance, and templates.
- **[Organic Growth Advisor](skills/organic-growth-advisor/)**: Workflow for designing organic acquisition and retention loops. Includes growth-loop templates and sample teardowns.
- **[PM Skill Creator](skills/pm-skill-creator/)**: Interactive guide for designing, scoping, and structuring a new PM skill. Includes authoring guidance and templates.
- **[PRD Development](skills/prd-development/)**: Workflow for creating a PRD from problem framing through user research, solution specifications, and success criteria. Includes a template and sample PRD.
- **[Prioritization Advisor](skills/prioritization-advisor/)**: Interactive guide for choosing among RICE, ICE, Value vs. Effort, MoSCoW, and Kano based on product stage.
- **[Product Manager Toolkit](skills/product-manager-toolkit/)**: Toolkit for feature prioritization, customer interview analysis, and PRD creation. Includes two Python utilities and PRD templates.
- **[Product Strategist](skills/product-strategist/)**: Strategic workflow for creating company-to-team OKRs and competitive analyses. Includes an OKR generator, templates, and five strategy models.
- **[User Story Mapping](skills/user-story-mapping/)**: Workflow based on Jeff Patton's two-dimensional story-mapping framework. Includes a template and sample story map.

### Command-Line Utilities

Run these examples from the repository root with Python 3. The commands show how to start each tool, but the utility documentation should also state its required packages, accepted inputs, output format, and available options.

- **[OKR Cascade Generator](skills/product-strategist/scripts/okr_cascade_generator.py)**: Command-line utility from [Product Strategist](skills/product-strategist/) for generating team-level OKRs from a strategic theme and list of teams. Example: `python3 skills/product-strategist/scripts/okr_cascade_generator.py growth --teams "Growth,Platform,Mobile,Data"`
- **[RICE Feature Prioritizer](skills/product-manager-toolkit/scripts/rice_prioritizer.py)**: Command-line utility from [Product Manager Toolkit](skills/product-manager-toolkit/) for scoring a sample backlog and selecting work within a capacity limit. Example: `python3 skills/product-manager-toolkit/scripts/rice_prioritizer.py sample --capacity 10 --output text`
- **[User Story Generator](skills/agile-product-owner/scripts/user_story_generator.py)**: Command-line utility from [Agile Product Owner](skills/agile-product-owner/) for creating structured user stories. Example: `python3 skills/agile-product-owner/scripts/user_story_generator.py`
- **[Customer Interview Analyzer](skills/product-manager-toolkit/scripts/customer_interview_analyzer.py)**: Command-line utility from [Product Manager Toolkit](skills/product-manager-toolkit/) for extracting themes and insights from customer interviews. Example: `python3 skills/product-manager-toolkit/scripts/customer_interview_analyzer.py`

---

## Reading List

### Working Products Conference #11, Hamburg 2026

These are the books and articles referenced in my talk on cognitive endurance, the pitfalls of frictionless design, and the importance of human judgment, empathy, and product taste in resisting algorithmic mediocrity.

#### The Death of Deep Reading and the Cognitive Shift

- **[The New Dark Ages: The Death of Reading and the Dawn of the Post-Literate Society](https://www.goodreads.com/book/show/244717250-the-new-dark-ages)**: Book by James Marriott. The collapse of print culture is dismantling the cognitive architecture required for linear focus, long-term historical continuity, and democratic deliberation.
- **[The Disappearance of Insight: When Technology Undermines How and Why](https://www.goodreads.com/book/show/214304859-the-disappearance-of-insight)**: Book by Frank C. Keil. Examines how the transition from mechanically transparent devices to opaque black-box systems atrophies our innate drive for causal understanding and fosters uncritical epistemic outsourcing.
- **[Reader, Come Home: The Reading Brain in a Digital World](https://www.goodreads.com/book/show/35887237-reader-come-home)**: Book by Maryanne Wolf. Documents how the brain's acquired reading circuits adapt to digital triage, including skimming and keyword spotting, at the expense of slower, deep-reading processes such as critical analysis and empathy.
- **[The Disappearance of Childhood](https://www.goodreads.com/book/show/79679.The_Disappearance_of_Childhood)**: Book by Neil Postman. Shows how print created an ordered, developmental hierarchy of learning, whereas electronic media delivers all information simultaneously, erasing pedagogical sequence and the master-novice boundary.
- **[The Shallows: What the Internet Is Doing to Our Brains](https://www.goodreads.com/book/show/9778945-the-shallows)**: Book by Nicholas Carr. Analyzes how continuous cognitive switching and hyperlinked environments overload working memory, inhibiting the consolidation of deep knowledge into durable mental models.

#### The Trap of Frictionless Experience and Lost Curiosity

- **[Shop Class as Soulcraft: An Inquiry into the Value of Work](https://www.goodreads.com/book/show/6261334-shop-class-as-soulcraft)**: Book by Matthew B. Crawford. Exposes how frictionless, sealed, and tamper-proof industrial designs deliberately infantilize users, severing direct physical understanding and transforming problem-solvers into passive consumers.
- **[The Glass Cage: Automation and Us](https://www.goodreads.com/book/show/20708814-the-glass-cage)**: Book by Nicholas Carr. Argues that friction is the fundamental mechanism through which the mind develops intuition and mastery; zero-friction interfaces inevitably induce cognitive deskilling and automation complacency.
- **[The Whale and the Reactor: A Search for Limits in an Age of High Technology](https://www.goodreads.com/book/show/195995.The_Whale_and_the_Reactor)**: Book by Langdon Winner. Introduces "technological somnambulism," showing how seamless user experiences lull society into adopting technological systems without questioning their embedded power structures or ethical consequences.
- **[User Friendly: How the Hidden Rules of Design Are Changing the Way We Live, Work, and Play](https://www.goodreads.com/book/show/41940285-user-friendly)**: Book by Cliff Kuang and Robert Fabricant. Traces the evolution of user experience design from empowering human comprehension to optimizing behavioral compliance and cognitive passivity.
- **[Atlas of AI: Power, Politics, and the Planetary Costs of Artificial Intelligence](https://www.goodreads.com/book/show/54304121-atlas-of-ai)**: Book by Kate Crawford. Demonstrates how the minimalist, frictionless interface of generative AI tools systematically obscures massive resource extraction, data scraping, and invisible human labor.
- **[Technopoly: The Surrender of Culture to Technology](https://www.goodreads.com/book/show/79678.Technopoly)**: Book by Neil Postman. Examines how culture surrenders to technological imperatives; when efficiency and convenience become primary ends, users stop inquiring about data provenance and intellectual validity.

#### The Collapse of Sequential Learning and Information Deluge

- **[Is Google Making Us Stupid?](https://www.theatlantic.com/magazine/archive/2008/07/is-google-making-us-stupid/306868/)**: Article by Nicholas Carr. The seminal *Atlantic* essay examining how algorithmic search and online skimming erode the sustained, linear concentration required for complex contemplation.
- **[The Reading Brain in the Digital Age: The Science of Paper versus Screens](https://www.scientificamerican.com/article/reading-paper-screens/)**: Article by Ferris Jabr. Synthesizes experimental research on how physical pages provide spatial and tactile scaffolding that flat, scrolling feeds dissolve.
- **[The Post-Literate Condition](https://www.greaterkashmir.com)**: Article by Greater Kashmir. Contrasts the quiet, patient unfolding of written arguments with algorithmic media, showing how informational flooding robs learners of the intellectual solitude required to synthesize ambiguity.
- **[The Shallows of the Academy: The Death of the Syllabus and the Rise of the Feed](https://academic.oup.com)**: Article. Analyzes the risks of fragmenting education into modular, instant content, bypassing the cognitive heavy lifting necessary to build internal frameworks of knowledge.
- **[From Literate to Entertained: The Shift to a Post-Literate Culture](https://periloustech.wordpress.com)**: Article by Perilous Tech. Critiques the emergence of "Pancake People": individuals spread wide and thin across vast oceans of surface data without the depth required for independent judgment.

#### Human Judgment, Taste, and Sensemaking vs. Machine Prediction

- **[Prediction Machines: The Simple Economics of Artificial Intelligence](https://www.goodreads.com/book/show/36373468-prediction-machines)**: Book by Ajay Agrawal, Joshua Gans, and Avi Goldfarb. Demonstrates that as the economic cost of prediction drops to near zero, its complement, human judgment under uncertainty, becomes exponentially more valuable.
- **[Sensemaking: What Makes Human Intelligence Essential in the Age of the Algorithm](https://www.goodreads.com/book/show/31848386-sensemaking)**: Book by Christian Madsbjerg. Argues that algorithmic analysis only maps quantifiable metrics, whereas true strategic insight requires understanding the cultural, emotional, and phenomenological context of human experience.
- **[The Master and His Emissary: The Divided Brain and the Making of the Western World](https://www.goodreads.com/book/show/6968772-the-master-and-his-emissary)**: Book by Iain McGilchrist. Contrasts left-hemisphere mechanical optimization with right-hemisphere contextual understanding; AI operates like a left hemisphere, needing human right-hemisphere synthesis to achieve relational coherence.
- **[Seeing Like a State: How Certain Schemes to Improve the Human Condition Have Failed](https://www.goodreads.com/book/show/20186.Seeing_Like_a_State)**: Book by James C. Scott. Contrasts abstract, codified schemes (*techne*) with localized, practical intuition (*metis*); centralized predictive systems collapse when they ignore tacit, lived reality.
- **[Skin in the Game: Hidden Asymmetries in Daily Life](https://www.goodreads.com/book/show/36064445-skin-in-the-game)**: Book by Nassim Nicholas Taleb. Argues that sound judgment cannot exist without real exposure to downside risk; because machines bear no consequence for erroneous outputs, accountability remains solely with the human decision-maker.

#### Strategic Discernment and the Product Management Edge

- **[The Alignment Problem: Machine Learning and Human Values](https://www.goodreads.com/book/show/50489349-the-alignment-problem)**: Book by Brian Christian. Explores the core paradox of machine learning: models optimize precisely for what they are mathematically told to maximize, inevitably creating unintended harm without human ethical steering.
- **[Weapons of Math Destruction: How Big Data Increases Inequality and Threatens Democracy](https://www.goodreads.com/book/show/28186015-weapons-of-math-destruction)**: Book by Cathy O'Neil. Shows how automated models encode past biases and scale them under an aura of mathematical objectivity; PMs must provide the moral agency to audit the system.
- **[The Design of Everyday Things](https://www.goodreads.com/book/show/840.The_Design_of_Everyday_Things)**: Book by Don Norman. The foundational text demonstrating that human error is nearly always a design failure; human PMs design affordances that safeguard user agency rather than merely maximizing conversion loops.
- **[What Humans Lose When We Let AI Decide](https://sloanreview.mit.edu/article/what-humans-lose-when-we-let-ai-decide/)**: Article by Thomas H. Davenport and Steven M. Miller, *MIT Sloan Management Review*. Warns against automation complacency in executive workflows, showing that offloading discernment atrophies the capacity to navigate ambiguous strategic landscapes.
- **[The Most Valuable Skill in AI Product Management Is Taste](https://www.mindtheproduct.com)**: Article by Product Leadership Group. Argues that when generative tools commoditize execution and synthesis, the primary competitive advantage shifts to product taste: the editorial restraint to build only what is meaningful.
- **[4 Important Human Skills AI Can't Replace](https://online.hbs.edu/blog/post/human-skills-ai-cant-replace)**: Article by Harvard Business School Online. Breaks down the durable boundaries of artificial systems: pattern recognition cannot replicate meaning-making, emotional intelligence, or non-linear creative breakthroughs.
- **[Why Empathy Is Your Most Valuable Product Management Metric](https://www.mindtheproduct.com/empathy-is-your-most-valuable-metric/)**: Article by Mind the Product. Frames empathy as a strategic safeguard that prevents teams from building exploitative, engagement-maximizing loops that degrade long-term brand equity.

### Product Management Library

#### New to Product? Start Here

- **[Product Management in Practice](https://www.goodreads.com/book/show/36563477)**: Book by Matt LeMay.
- **[Outcomes Over Output](https://www.goodreads.com/book/show/45273233)**: Book by Joshua Seiden.
- **[Escaping the Build Trap](https://www.goodreads.com/book/show/33369253-escaping-the-build-trap)**: Book by Melissa Perri.
- **[Continuous Discovery Habits](https://www.goodreads.com/book/show/58046715-continuous-discovery-habits)**: Book by Teresa Torres.
- **[Inspired](https://www.goodreads.com/book/show/48745535-inspired)**: Book by Marty Cagan.

#### More Product Management Basics

- **[The Team That Managed Itself](https://www.goodreads.com/book/show/48560062-the-team-that-managed-itself)**: Book by Christina Wodtke.
- **[User Story Mapping](https://www.goodreads.com/book/show/27109661-user-story-mapping)**: Book by Jeff Patton.
- **[Aligned: Stakeholder Management](https://www.goodreads.com/book/show/171661144-aligned)**: Book by Bruce McCarthy and Melissa Appel.
- **[The Art of Product Management, Second Edition](https://www.goodreads.com/book/show/208293497-the-art-of-product-management-second-edition)**: Book by Rich Mironov.
- **[Testing Business Ideas](https://www.goodreads.com/book/show/9781119551447)**: Book by David J. Bland and Alexander Osterwalder.
- **[Don't Make Me Think, Revisited](https://www.goodreads.com/book/show/30213252-don-t-make-me-think)**: Book by Steve Krug.
- **[Obviously Awesome: How to Nail Product Positioning](https://www.goodreads.com/book/show/59323708-obviously-awesome)**: Book by April Dunford.
- **[Sprint](https://www.goodreads.com/book/show/28244571-sprint)**: Book by Jake Knapp, John Zeratsky, and Braden Kowitz.
- **[Business Model Generation](https://www.goodreads.com/book/show/9780470876411)**: Book by Alexander Osterwalder et al.
- **[The Lean Startup](https://www.goodreads.com/book/show/24464406-the-lean-startup)**: Book by Eric Ries.
- **[Product Direction](https://www.goodreads.com/book/show/57578987-product-direction)**: Book by Nacho Bassino.
- **[Selling the Dream](https://www.goodreads.com/book/show/237837.Selling_the_Dream)**: Book by Guy Kawasaki.
- **[Evidence-Guided](https://www.goodreads.com/book/show/200096725-evidence-guided)**: Book by Itamar Gilad.
- **[The Product Momentum Gap](https://www.goodreads.com/book/show/9783982684918)**: Book by Andrea Saez and Dave Martin.
- **[Rocket Surgery Made Easy](https://www.goodreads.com/book/show/6658783-rocket-surgery-made-easy)**: Book by Steve Krug.
- **[Running Lean](https://www.goodreads.com/book/show/13078769-running-lean)**: Book by Ash Maurya.
- **[Kanban](https://www.goodreads.com/book/show/9780984521401)**: Book by David J. Anderson.
- **[The Back of the Napkin](https://www.goodreads.com/book/show/2420301)**: Book by Dan Roam.
- **[Managing Product = Managing Tension](https://www.goodreads.com/book/show/9781839521966)**: Book by Marc Abraham.
- **[What Do We Do Now? A Product Manager's Guide to Strategy in the Time of Crisis](https://www.goodreads.com/book/show/9781800684010)**: Book by Randy Silver.
- **[Digitales Produktmanagement: Methoden, Instrumente, Praxisbeispiele](https://www.goodreads.com/book/show/9783658306281)**: German-language book by Sascha Hoffmann et al.
- **[Scrum in der Praxis](https://www.goodreads.com/book/show/9783864908804)**: German-language book by Sven Röpstorff and Robert Wiechmann.
- **[Entwickle deine Stärken](https://www.goodreads.com/book/show/39712298-entwickle-deine-st-rken-mit-dem-strengthsfinder-2-0)**: German-language book by Tom Rath.
- **[Bikablo 2.0](https://www.goodreads.com/book/show/9783940315359)**: German-language book by Kommunikationslotsen.

#### Leading Product People and Product Organizations

- **[STRONG Product People: A Complete Guide to Developing Great Product Managers](https://www.goodreads.com/book/show/56794688-product-people)**: Book by Petra Wille.
- **[The Decision Stack](https://www.goodreads.com/book/show/9781067613211)**: Book by Martin Eriksson.
- **[Product Operations](https://www.goodreads.com/book/show/199368360-product-operations)**: Book by Melissa Perri and Denise Tilles.
- **[The Making of a Manager](https://www.goodreads.com/book/show/38821039-the-making-of-a-manager)**: Book by Julie Zhuo.
- **[EMPOWERED: Ordinary People, Extraordinary Products](https://www.goodreads.com/book/show/56259430-empowered)**: Book by Marty Cagan.
- **[TRANSFORMED](https://www.goodreads.com/book/show/56447603-transformed)**: Book by Marty Cagan et al.
- **[Future Ethics](https://www.goodreads.com/book/show/9781999601911)**: Book by Cennydd Bowles.
- **[Radical Focus](https://www.goodreads.com/book/show/57802947-radical-focus-second-edition)**: Book by Christina Wodtke.
- **[Who Does What by How Much? A Practical Guide to Customer-Centric OKRs](https://www.goodreads.com/book/show/210407220-who-does-what-by-how-much)**: Book by Jeff Gothelf and Josh Seiden.
- **[Hiring Product Managers](https://www.goodreads.com/book/show/55204734-hiring-product-managers)**: Book by Kate Leto.
- **[The Leader's Journey: Transforming Your Leadership to Achieve the Extraordinary](https://www.goodreads.com/book/show/9781959029137)**: Book by Donna Lichaw.
- **[Farther, Faster, and Far Less Drama](https://www.goodreads.com/book/show/61494019-farther-faster-and-far-less-drama)**: Book by Janice Fraser and Jason Fraser.
- **[Product Leadership](https://www.goodreads.com/book/show/30014114-product-leadership)**: Book by Richard Banfield, Martin Eriksson, and Nate Walkingshaw.
- **[Radical Alignment](https://www.goodreads.com/book/show/52079355-radical-alignment)**: Book by Alexandra Jamieson and Bob Gower.
- **[Time to Think: Listening to Ignite the Human Mind](https://www.goodreads.com/book/show/18937446-time-to-think)**: Book by Nancy Kline.
- **[Connect: Building Exceptional Relationships with Family, Friends and Colleagues](https://www.goodreads.com/book/show/140193873)**: Book by David L. Bradford and Carole Robin.
- **[What You Do Is Who You Are](https://www.goodreads.com/book/show/45885801-what-you-do-is-who-you-are)**: Book by Ben Horowitz.
- **[Trillion Dollar Coach](https://www.goodreads.com/book/show/45016469-trillion-dollar-coach)**: Book by Eric Schmidt, Jonathan Rosenberg, and Alan Eagle.
- **[Measure What Matters](https://www.goodreads.com/book/show/39286958)**: Book by John Doerr.
- **[Redesigning Leadership](https://www.goodreads.com/book/show/10281070)**: Book by John Maeda and Becky Bermont.
- **[Traction: Get a Grip on Your Business](https://www.goodreads.com/book/show/13236324-traction)**: Book by Gino Wickman.
- **[The Hard Thing About Hard Things](https://www.goodreads.com/book/show/20359768-the-hard-thing-about-hard-things)**: Book by Ben Horowitz.
- **[Good Talk](https://www.goodreads.com/book/show/53511223-good-talk)**: Book by Daniel Stillman.
- **[Magical Meetings](https://www.goodreads.com/book/show/57862542-the-non-obvious-guide-to-magical-meetings)**: Book by Douglas Ferguson and John Fitch.
- **[Monkey Management](https://www.goodreads.com/book/show/9783869910383)**: German-language book by J.R. Edlund.
- **[Das anständige Unternehmen: Was richtige Führung ausmacht und was sie weglässt](https://www.goodreads.com/book/show/26830429-das-anst-ndige-unternehmen)**: German-language book by Reinhard K. Sprenger.

#### Communities of Practice

- **[STRONG Product Communities: The Essential Guide to Product Communities of Practice](https://www.goodreads.com/book/show/9783982235189)**: Book by Petra Wille and Melissa Suzuno.
- **[Building Successful Communities of Practice](https://www.goodreads.com/book/show/29155800-building-successful-communities-of-practice)**: Book by Emily Webber.

#### Artificial Intelligence

- **[Artificial Organizations](https://www.goodreads.com/book/show/250017055-artificial-organizations)**: Book by Barry O'Reilly.
- **[All the Ghosts in the Machine: The Digital Afterlife of Your Personal Data](https://www.goodreads.com/book/show/45995273)**: Book by Elaine Kasket.
- **[Empire of AI](https://www.goodreads.com/book/show/230842820-empire-of-ai)**: Book by Karen Hao.

#### Broadening Your Product Horizon

- **[Reboot: Reclaiming Your Life in a Tech-Obsessed World](https://www.goodreads.com/book/show/9781783967568)**: Book by Elaine Kasket.
- **[Architecture for Flow](https://www.goodreads.com/book/show/239941967-architecture-for-flow)**: Book by Susanne Kaiser.
- **[Sales Pitch](https://www.goodreads.com/book/show/196811879)**: Book by April Dunford.
- **[Present Yourself: Proven Strategies for Authentic and Impactful Public Speaking](https://www.goodreads.com/book/show/9798989523405)**: Book by Danielle Barnes and Christina Wodtke.
- **[The Growth Equation: How Early Stage Startups Can Build a Powerful Engine for Growth](https://www.goodreads.com/book/show/217830934-the-growth-equation)**: Book by Andy Budd.
- **[Calm Technology](https://www.goodreads.com/book/show/28359833-calm-technology)**: Book by Amber Case.
- **[Draw Your Big Idea](https://www.goodreads.com/book/show/26031175-draw-your-big-idea)**: Book by Heather Willems and Nora Herting.
- **[The Advice Trap](https://www.goodreads.com/book/show/50550775-the-advice-trap)**: Book by Michael Bungay Stanier.
- **[The Inner Game of Tennis: The Classic Guide to the Mental Side of Peak Performance](https://www.goodreads.com/book/show/1471595.The_Inner_Game_Of_Tennis)**: Book by W. Timothy Gallwey.
- **[Mapping Experiences](https://www.goodreads.com/book/show/30206219)**: Book by Jim Kalbach.
- **[Anything You Want](https://www.goodreads.com/book/show/27436585)**: Book by Derek Sivers.
- **[Illuminate](https://www.goodreads.com/book/show/28582290-illuminate)**: Book by Nancy Duarte and Patti Sanchez.
- **[Dear Data](https://www.goodreads.com/book/show/28465052-dear-data)**: Book by Giorgia Lupi and Stefanie Posavec.
- **[The Laws of Simplicity](https://www.goodreads.com/book/show/54456008-the-laws-of-simplicity)**: Book by John Maeda.
- **[Predictable Revenue](https://www.goodreads.com/book/show/18899679-predictable-revenue)**: Book by Aaron Ross and Marylou Tyler.
- **[The Art of the Start](https://www.goodreads.com/book/show/17774027-the-art-of-the-start)**: Book by Guy Kawasaki.
- **[Turn the Ship Around!](https://www.goodreads.com/book/show/26917955-turn-the-ship-around)**: Book by David Marquet.
- **[The Tipping Point](https://www.goodreads.com/book/show/17167952)**: Book by Malcolm Gladwell.
- **[Getting Real](https://www.goodreads.com/book/show/11553059-getting-real)**: Book by 37signals.
- **[Who Owns the Future?](https://www.goodreads.com/book/show/18804368-who-owns-the-future)**: Book by Jaron Lanier.
- **[Rework](https://www.goodreads.com/book/show/7861053-rework)**: Book by Jason Fried and David Heinemeier Hansson.
- **[Designing the Search Experience](https://www.goodreads.com/book/show/9780123969811)**: Book by Tony Russell-Rose and Tyler Tate.
- **[Good to Great](https://www.goodreads.com/book/show/4113)**: Book by Jim Collins.
- **[Remote: Office Not Required](https://www.goodreads.com/book/show/18802899-remote)**: Book by Jason Fried and David Heinemeier Hansson.
- **[Lean In](https://www.goodreads.com/book/show/19546126-lean-in)**: Book by Sheryl Sandberg.
- **[Built to Last](https://www.goodreads.com/book/show/2361505.Built_to_Last_)**: Book by Jim Collins and Jerry I. Porras.
- **[Hooked](https://www.goodreads.com/book/show/23586542)**: Book by Nir Eyal.
- **[The Five Dysfunctions of a Team: A Leadership Fable](https://www.goodreads.com/book/show/21343)**: Book by Patrick M. Lencioni.
- **[Tribal Leadership](https://www.goodreads.com/book/show/25818373-tribal-leadership)**: Book by Dave Logan, John King, and Halee Fischer-Wright.
- **[Antifragile: Things That Gain from Disorder](https://www.goodreads.com/book/show/19723223-antifragile)**: Book by Nassim Nicholas Taleb.
- **[Value Proposition Design](https://www.goodreads.com/book/show/23232900-value-proposition-design)**: Book by Alexander Osterwalder, Yves Pigneur, Greg Bernarda, and Alan Smith.
- **[Winner Take All](https://www.goodreads.com/book/show/15956433-winner-take-all)**: Book by Dambisa Moyo.
- **[The 4-Hour Workweek](https://www.goodreads.com/book/show/3134376-the-4-hour-workweek)**: Book by Timothy Ferriss.
- **[Die Kunst der kleinen Lösung](https://www.goodreads.com/book/show/23927334-die-kunst-der-kleinen-l-sung)**: German-language book by Klaus Henning.
- **[Die Feigheit der Frauen](https://www.goodreads.com/book/show/9783570100707)**: German-language book by Bascha Mika.
- **[Jeder Mensch](https://www.goodreads.com/book/show/57616302-jeder-mensch)**: German-language book by Ferdinand von Schirach.
- **[Exit Racism](https://www.goodreads.com/book/show/35213270)**: German-language book by Tupoka Ogette.

#### Coaching and Psychology

- **[Coaching From Essence](https://www.goodreads.com/book/show/9780971752221)**: Book by Robert Ellis.
- **[Evidence Based Coaching Handbook](https://www.goodreads.com/book/show/9780471720867)**: Book by Dianne R. Stober and Anthony M. Grant.
- **[The Creative Act: A Way of Being](https://www.goodreads.com/book/show/60965426-the-creative-act)**: Book by Rick Rubin.
- **[Small Teaching: Everyday Lessons from the Science of Learning](https://www.goodreads.com/book/show/58664292)**: Book by James M. Lang.
- **[Team Coaching Toolkit](https://www.goodreads.com/book/show/9781910056653)**: Book by Tony Llewellyn.
- **[The Coaching Habit](https://www.goodreads.com/book/show/36684893-the-coaching-habit)**: Book by Michael Bungay Stanier.
- **[Help Them Grow or Watch Them Go](https://www.goodreads.com/book/show/42866295-help-them-grow-or-watch-them-go)**: Book by Beverly Kaye and Julie Winkle Giulioni.
- **[Emotional Intelligence](https://www.goodreads.com/book/show/26329.Emotional_Intelligence)**: Book by Daniel Goleman.
- **[FYI: For Your Improvement](https://www.goodreads.com/book/show/55824028-fyi-for-your-improvement)**: Book by Michael M. Lombardo.
- **[The Myth of Normal: Trauma, Illness, and Healing in a Toxic Culture](https://www.goodreads.com/book/show/58764796-the-myth-of-normal)**: Book by Gabor Maté.
- **[Thinking, Fast and Slow](https://www.goodreads.com/book/show/12385458-thinking-fast-and-slow)**: Book by Daniel Kahneman.
- **[The Prosperous Coach](https://www.goodreads.com/book/show/20110915-the-prosperous-coach)**: Book by Rich Litvin and Steve Chandler.
- **[Schnelles Denken, langsames Denken](https://www.goodreads.com/book/show/34853084-schnelles-denken-langsames-denken)**: German-language book by Daniel Kahneman.
- **[Coaching mit NLP-Werkzeugen](https://www.goodreads.com/book/show/9783527503513)**: German-language book by Thomas Rückerl.
- **[Ich-Entwicklung für effektives Beraten](https://www.goodreads.com/book/show/28049376-ich-entwicklung-fur-effektives-beraten-interdisziplinare-beratungsforsc)**: German-language book by Thomas Binder.
- **[Fragen können wie Küsse schmecken](https://www.goodreads.com/book/show/7966837-fragen-k-nnen-wie-k-sse-schmecken-hauptbd)**: German-language book by Carmen Kindl-Beilfuß.
- **[Spiele der Erwachsenen: Psychologie der menschlichen Beziehungen](https://www.goodreads.com/book/show/13509277-spiele-der-erwachsenen)**: German-language book by Eric Berne.
- **[Das neue 1×1 der Persönlichkeit](https://www.goodreads.com/book/show/3048352-das-neue-1x1-einmaleins-der-pers-nlichkeit)**: German-language book by Lothar Seiwert and Friedbert Gay.
- **[Typisch Mensch](https://www.goodreads.com/book/show/12427916-typisch-mensch)**: German-language book by Richard Bents and Reiner Blank.
- **[Emotionale Führung](https://www.goodreads.com/book/show/9783548364667)**: German-language book by Daniel Goleman.
- **[Die Kunst des klaren Denkens](https://www.goodreads.com/book/show/72332138)**: German-language book by Rolf Dobelli.
- **[HASS. Von der Macht eines widerständigen Gefühls](https://www.goodreads.com/book/show/75328576-hass)**: German-language book by Seyda Kurt.

---

*Last updated: August 2026*
