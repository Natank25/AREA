# Distance travelled

## What “distance” means

Here, distance travelled means **progress from a fresh start towards a small, working web result that the developer can explain and reproduce**. It is a qualitative measure, not elapsed time or a score: the result reached matters, but so do avoidable setup/documentation detours and whether the implementation was understood rather than copied. The spikes did not finish with exactly the same result, so the comparison below is indicative, not a strict ranking.

| Run | Result when time ran out | Documentation and main friction | Distance travelled |
| --- | --- | --- | --- |
| Laravel | The server had been launched. Finding the right `.env` variable took time. | The relevant documentation was not immediately obvious, but was useful once found; more tutorials linked directly from the docs would help. | **Short to medium.** A running server is a concrete milestone, but time spent finding the right guidance left less room to go further. |
| Spring Boot | A `ping` endpoint was quick to create; at the bell, the Java file still needed a dependency import/package. Setup in IntelliJ IDEA was easy. | Documentation was easy to find, plentiful and comprehensive. Its breadth made it less straightforward to identify a getting-started path; choosing the framework was the longest task. | **Short to medium.** The spike got closest to the intended endpoint, with only a small dependency gap. |
| Go | The server was running and serving a page at `localhost:8080`, using an HTML template copied from Stack Overflow; a `ping` endpoint was not recorded. | Documentation is accessible and abundant, and Go by Example offers code examples for many features. Installing Go and resolving a VS Code issue that deleted code. | **Short to medium.** A visible page was reached, but environment/editor friction consumed much of the spike and the copied template is weaker evidence of an understood, reproducible implementation. |

The labels are deliberately broad: they summarize both the concrete outcome and how much uncertainty remained before a developer could continue independently. They should not be read as a claim that one framework is faster overall; the notes capture different outputs and setup conditions.