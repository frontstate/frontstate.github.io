[The Front State](https://frontstate.org) is a new civics-oriented organization started after the 2024 US elections, with final acceptance that no matter who wins in reality most of us lose. This is not particularly newsworthy, as for decades government has increasingly worsened, even before the more *dramatic* modern times.

Its objective is a generational project to rethink how governance can work better, from the smallest neighborhood groups through to national governments and international organizations. Potentially this could be achieved by building a transparent state-like construct _in front_ of any current bureaucracy.

One ongoing "mystery" is why politicians can't seem to publish coherent plans, even sometimes only having *concepts* of plans before voters are meant to put them into power. Why are so many bills worked on behind closed doors, then get presented to a larger group to vote on before they even have time to read it or make changes? And why must we do that repeatedly at every level of government, in every state, municipality, and so on. There is a better way to develop process. 

The Front State is built on and develops the open source [Demicracy.org](https://demicracy.org) platform - from "[Deme](https://en.wikipedia.org/wiki/Deme)" a term from Classical Greece for a local administrative division - an emphasis on people organized in groups for action, rather than people alone or as a whole.

The cornerstone features for the platform include:

* A voter-oriented user system with verification levels including registered voter and optional social network features perhaps oddly focused *against* global reach at the individual (but not policy) level. Verification itself can be optional for other instances of the platform, and different instances can be federated or standalone as desired.
  * Consider this like a non-profit (to the point of disallowing ads & tracking) NextDoor or service seeking site that puts the users first and in touch with each other, while focusing on truly bettering your local community. 
* A "Process in Git" (PiG) system for developing and tracking process (like legislation), with a focus on transparency and collaboration. This is a crucial part of the platform, and is designed to be used by anyone, not just politicians. Much like code in Git you can branch different variants of a process, collaborate with pull requests, release specific versions, and share process between different needs for similar objectives.
  * This system is available for more than just legislation, and should be useful for even organizing small groups like [PTAs](https://en.wikipedia.org/wiki/Parent%E2%80%93teacher_association).
* An *implementation* layer for process, including Behavior-driven development ([BDD](https://en.wikipedia.org/wiki/Behavior-driven_development)) to essentially write requirements for process in a computer-readable and testable way. Laws should compile, syntax check correctly, and run tests on themselves. This then could also be the foundation for actual websites offering users a view into how given regulations work.
  * Imagine asking an AI agent on a municipal website to generate architectural plans for a modification to your home then get blueprints back that show exactly how they validate correctly against local code - although you should probably still verify with a human architect lest you get a room without doors.
* A front-end to gain better visibility into various process, involved users, if tests are passing in pending changes, a ledger of changes made by whom, and so on. This is a classic [platform engineering](https://en.wikipedia.org/wiki/Platform_engineering) challenge and starts based on https://backstage.io - which when viewed from the right angle seems eerily like government should work as well.
  * Essentially it indexes various available variants of process presented objectively you can then choose to follow, or not, then benefit from, or not. 

Back in [1976 a Schoolhouse Rock! segment introduced an anthropomorphic "bill"](https://en.wikipedia.org/wiki/I%27m_Just_a_Bill) as a piece of paper that could become a law. Many things have changed lately (expect an eventual expansion here of how [Chevron deference](https://en.wikipedia.org/wiki/Chevron_U.S.A.,_Inc._v._Natural_Resources_Defense_Council,_Inc.) relates!), let alone from back when representatives travelled to their jobs on horseback. We should be able to finally update the technology involved here - at times it feels like this is still the tech level parts of our government are at.

Meet Bill the PiG, as brought to you by [Gemini](https://en.wikipedia.org/wiki/Gemini_(chatbot)) - no more hiding the pork!

![GeminiGeneratedProcessPiG.png](GeminiGeneratedProcessPiG.png)
