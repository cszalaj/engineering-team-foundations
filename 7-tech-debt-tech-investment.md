# Technical Investment Over Technical Debt
Our software engineering team adheres to the strategic approach of making technical, architectural and infrastructure investments rather than deferring necessary improvements to future development cycles, sometimes called accruing technical debt. We consciously allocate time and resources to enhance our product, architecture, codebase, infrastructure and processes. These investments pay dividends over time, fostering maintainability, scalability and robustness. By prioritizing the quality of what we ship we ensure that our software thrives, avoiding the pitfalls of technical debt that can hinder progress and innovation. 

We recognize that making trade-offs is a fundamental part of software development. We approach our choices intentionally, in good faith, and with an awareness of the inherent trade-offs involved.

We have permission and power to rethink decisions and invest in improving circumstances without judgement against past decisions. Most technology decisions are two way doors, where we can revisit decisions at a future time with learning and data in hand, choosing to invest in making something better if the returns are clear. 

With that in mind, we take the perspective of making technical investments rather than accruing technical debt, which is achieved by the following principles.

* **Ship finished work.** We don't ship on the promise of future work. If we find ourselves saying, "Lets ship it 'as is' today, and circle back in a month", we evaluate if the additional work is truly necessary. If it is, the work is done before shipping; if not, there is no promise to circle back. What has shipped is what we live with until there is a clear reason - with data to validate the benefits - to make an investment. 
* **Build only what is necessary.** When we use data to make decisions about our architecture, the risk of over or under building is mitigated. 
* **Build with what we have.** Introducing a new library, language, code pattern or AWS service should be viewed as an investment like any other technical or architecture decision. New technology is introduced to our stack with consideration **<sup>1</sup>** and with the involvement of the appropriate stakeholders **<sup>2</sup>**.
* **Make data-backed decisions.** We make technical decisions based on data and learning rather than assumptions and hypotheticals. 
* **Undertake work that has a payoff.** All of the work we undertake should yield dividends by improving efficiency, lowering costs, improving performance, and/or aligning with core cloud-first values in the [AWS Well-Architected Framework](https://docs.aws.amazon.com/wellarchitected/latest/framework/welcome.html).
* **Accept that the platform and its components can and will evolve when necessary.** We evaluate, rethink and learn as we ship, therefore evolving our understanding of where our time and financial investments are best applied. Platform evolution will happen as a product of following the principles in this foundation.

**<sup>1</sup>** _Consideration in this case includes the following items._

* Learn enough about the technology to be proficient and conversant in the tradeoffs of adding it to our stack. 
    * This might include building a proof of concept.
    * This could be giving a presentation and interrogating the decision with peers and stakeholders.
* Look at a roadmap of the current software to see if the technology fits.
* Look at the roadmap for our products to see if the technology fits.

**<sup>2</sup>** _A stakeholder is defined as any team member impacted by a particular decision (potentially including Engineers, Product, Quality Assurance, Hosting, Support, Consulting or other departments and teams)._

_Examples_

* If you are introducing a new coding pattern like dependency injection, then the only stake holder is other engineers on your immediate team. However, if you are introducing a new DI library, like using Unity instead of Windsor, the stakeholders are the broader Engineering team.
* If you are introducing a new language like Rust, then the stakeholders would be the Engineering team as a whole, and the hosting team.
* If you are introducing structured logging, then the stakeholders would be engineers on your immediate team and the Support team.


# Contributors
This proposal was created by Chris Szalaj, Jeff Oliver, John Jakovich, and Engineering Leadership. 

