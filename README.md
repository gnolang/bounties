# gno.land Bounty Program 

We’ve provided a detailed guide on how to navigate the gno.land bounty ecosystem, and recommendations on how to participate and increase your chances of receiving the bounty.

We have four different categories of bounties, and different bounty sizes linked to a monetary reward. Please take the time to read this information before starting to work on a bounty.

### Meta Bounties

**Description:**

Meta bounties focus on creating several impactful and reusable examples, dApps, and packages for Gno. You can find an example of this bounty type [here](https://github.com/gnolang/gno/issues/3084).

These contributions should be:

- Creative: Demonstrating unique and innovative use cases.
- Straightforward: Easy to understand for developers of all skill levels.
- Concise and Well-Documented: Clear source code with thorough documentation, serving as onboarding material and primary references for developers exploring Gno’s features and applications.
- Specific: instead of tackling a wide array of functionality, the code should be focused on the objective and attempt to re-use as much as possible existing packages.

Meta bounties range in value from $500 to $2,000, depending on the quality, complexity, and potential impact of the contribution. While the issue for the bounty is open, all submissions are entitled to compensation up to the bounty value, with approval from the core team.

### Scoped Bounties

**Description:**

Scoped bounties are well-defined tasks with a detailed scope and clear expected outcomes. These bounties typically involve solving specific problems or implementing predefined features. An example from this bounty category is the [`gno test -cover` bounty](https://github.com/gnolang/gno/issues/2908) bounties.

**Key Points:**

- Each bounty has an exact monetary value, but can be shared between multiple participants. In the review process, a best effort will be made to distribute rewards fairly.
- The deliverables and success criteria are clearly outlined in the bounty description.

This category is straightforward and ideal for developers who prefer structured tasks with minimal ambiguity.

### Bounties for Competing Implementations

**Description:**

This category aims to explore different approaches at solving a problem, in the form of multiple competing implementations. These are often core re-usable packages within gno.land, which can serve as a useful tool for the larger ecosystem. An example from this bounty category is the [Markdown Library/Framework bounty](https://github.com/gnolang/gno/issues/2753).

**Key Points:**

- The first implementations to be merged will receive an initial payout of 50% of the total bounty.
- The remaining 50% is awarded based on adoption and usage over the course of the 6 months (or less) from the first implementations, incentivizing quality and user engagement.
- Strong documentation and usability increase the chances of adoption and being recognized as the “winning” solution.
- Implementations should have distinctive names.

Monetary values for these bounties vary and are determined by the scope and potential impact of the feature.

### Bounties for Architectural Solutions

**Description:**

These bounties focus on solving architectural challenges through creative proposals. The aim is to gather multiple innovative ideas and combine the best aspects into a single comprehensive specification - and after it’s approved, the implementation into code. An example from this bounty category is the [anti-squatting system](https://github.com/gnolang/gno/issues/2727) bounty.

**Key Points:**

- Proposals are reviewed collectively, with the final solution potentially being a synthesis of multiple contributions.
- Rewards are higher than other bounty categories, reflecting the complexity, collaboration, and level of effort required.
- The core team will ultimately confirm which specification should be considered final, and give a go-ahead for the implementation.

Due to the nature of these bounties, payouts are flexible and distributed based on contribution quality and input of each proposal in the final solution


## Bounty sizes

Each bounty is associated with a size, to which corresponds the maximum compensation for the work involved on the bounty. A bounty size may under rare occasion be revisited to a bigger or smaller size; hence why it's important to talk about your proposed solution with the core team ahead of time.

In some cases, the work associated with a bounty may be outstanding. When that happens, the core team can decide to award up to 25% of the bounty's value to the recipient.

The value of the bounty, aside from the material completion of the task, considers the involved time in managing the created pull request and iterating on feedback.

| t-shirt size | expected compensation |
|--------------|-----------------------|
| XS           | $500                  |
| S            | $1000                 |
| M            | $2000                 |
| L            | $4000                 |
| XL           | $8000                 |
| XXL          | $16000                |
| 3XL          | $32000                |


##  A Guide to Participating

- Identify the bounty you want to work on, and join in the discussion on the issue for anything that is unclear; or where you want to more clearly define the work to be done. At this stage, you can also start working on an initial implementation in your local environment.
- Once you have spent time on the code related to the bounty, we recommend submitting a 'draft' PR as soon as possible.
    - The draft PR doesn't indicate that the bounty has been assigned to you, others are free to work on other draft PRs for the bounty.
    - Make sure to reference the bounty issue on the PR description you're writing.
    - After submitting the 'draft' PR, continue working until you are ready to mark the PR as "ready for review".
    - The core team will review the bounty PR submission after the work on the bounty has been completed, and determine if it qualifies for the bounty reward.
- Ask for clarification early if an element on the requirements or implementation design is unclear.
    - Aside from publishing the PR early, keeping regular updates with the core team on the bounty issue is key to being on the right track.
    - As part of the requirements, you must adhere to the contributing guidelines; additionally, it is expected that any newly added code or functionality is properly documented, tested and covered, at least in 80% of added code.
    - You're welcome to propose additional features and work on an issue should you envision a plausible expansion or change in scope. The core team may assign a bounty to the additional work, or change the bounty with respect to the changed scope.

You may make your submission at any time; however we invite you to publish your draft PR very early in the development process. This will make your work public, so you can easily get help by the core team and other community members. Additionally, your work can be continued by other people should you get stuck or no longer be willing to work on the bounty. Likewise, you can continue the abandoned or stuck work that someone else worked on.

Don't fear your work being "stolen": if a submission is the result of multiple people's efforts, we will look to split the bounty in a way that is fair and recognises each participant in creating the final outcome. Here are some examples of how that can happen:

- If Alice does most of the work and abandons it; then Bob comes around and finishes the job, then Bob's PR will be merged. But the core team will propose a split like 70% for Alice and 30% for Bob (depending, of course, on the relative effort undertaken by both).
- If Alice makes a PR that does only 50% of the work outlined in the requirements for the original issue, she will get 50%. Someone can still come up and finish the job; and claim the remaining part.
    - If you, for instance, cannot complete the entirety of the task or, as a non-developer, can only contribute a part of the specification/implementation, you may still be awarded a bounty for your input in the contribution.
- If Alice makes a PR that, aside from implementing what's required, also undertakes creating useful tools along the way, she may qualify for an "outstanding contribution"; and may be awarded up to 25% more of the original bounty's value. Or she may also ask if the team would be willing to offer a different bounty for the implementation of the tools.

Participants in the gno.land Bounty Program must meet the legal Terms and Conditions referenced [here](https://docs.google.com/document/d/e/2PACX-1vSUF-JwIXGscrNsc5QBD7Pa6i83mXUGogAEIf1wkeb_w42UgL3Lj6jFKMlNTdwEMUnhsLkjRlhe25K4/pub).
