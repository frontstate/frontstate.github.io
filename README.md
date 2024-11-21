# frontstate.github.io

The Front State is a new civics-oriented nonprofit started after the 2024 US elections, with final acceptance that no matter who wins in reality most of us lose. This is not particularly newsworthy, as for decades government has increasingly worsened, even before the more *dramatic* modern times.

Its objective is a generational project to rethink how governance can work better, from the smallest neighborhood groups through to national governments and international organizations.

One on-going mystery (to varying degrees) is why politicians can't seem to publish coherent plans, only seemingly having *concepts* of plans before the voters are meant to put them into power. Why are so many bills worked on behind closed doors, then get presented to a larger group to vote on before they even have time to read it? And why must we do that repeatedly at every level of government, in every state, municipality, and so on. There must be a way to develop better process and reuse it where able. 

The Front State is built on and develops the open source Demicracy.org platform - from "[Deme](https://en.wikipedia.org/wiki/Deme)" a term from Classical Greece for a local administrative division - an emphasis on people organized in groups for action, rather than people alone or as a whole.

The cornerstone features for the platform include:

* A voter-oriented user system, with verified registered voters ("demites") and optional social network features/ Verification itself can be optional for other instances of the platform, and different instances can be federated or standalone as desired.
* A "Process in Git" (PiG) system for developing and tracking process (like legislation), with a focus on transparency and collaboration. This is a key part of the platform, and is designed to be used by anyone, not just politicians. Much like code in Git you can branch different variants of a process, collaborate with pull requests, release specific versions, and share process between different needs for similar objectives.
* An *implementation* layer for process, including Behavior-driven development ([BDD](https://en.wikipedia.org/wiki/Behavior-driven_development)) to essentially write requirements for process in a computer-readable and testable way. Laws should compile, syntax check correctly, and run tests on themselves! This then could also be the foundation for actual websites offering users a view into how a regulation works (imagine asking AI to generate architectural plans for a modification to your house then get plans back that show exactly how they validate correctly against local code).
* A front-end to gain better visibility into your process, involved users, if tests are passing in pending changes, a ledger of changes made and by who, and so on. This is a classic platform engineering project and starts based on https://backstage.io - which when viewed from the right angle seems eerily like government should work as well (available variants of process presented objectively you can then choose to follow, or not, then benefit, or not). 

Back in 1976 a Schoolhouse Rock! segment introduced a "bill" as a piece of paper that could become a law. Many things have changed lately (expect an expansion here of how Chevron Doctrine relates), let alone from back when representatives travelled to their jobs on horseback. We should be able to finally update the technology involved here. Meet Bill the PiG, as brought to you by Gemini:

![GeminiGeneratedProcessPiG.png](GeminiGeneratedProcessPiG.png)
