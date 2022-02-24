# Code Reviews

Most important questions

* Does it work?
* Is it easy to maintain?
* Will we be able to understand it 2 years from now?

Have a deep knowledge of programming principles - but treat them as guidelines, not rules - know the importance of data structures, accurate abstractions, naming and control flow.

Review a PR slowly, you need a deep understanding of the change, don't glaze of a line of code that you don't understand.

Start with scanning through the PR to find the critical piece of implementation. Possibly write comments as you go and fix/update them later.

Follow function calls and jump around, read existing code too see how a change fits. Don't forget to read the task or ticket for context of the problem.

Afterwards read class by class, think of edge cases in the implementation. Ensure they are covered by tests.

Don't leave ambiguous comments. Explain:

1. The problem with the code.
2. The reason why I perceive it to be a problem.
3. My recommendation for how the author can resolve it.

Leave style decisions up to the automated formatting tools.

Approve the PR when it is good, not perfect.

## Links:

* [https://curtiseinsmann.hashnode.dev/ive-code-reviewed-over-750-pull-requests-at-amazon-heres-my-exact-thought-process](https://curtiseinsmann.hashnode.dev/ive-code-reviewed-over-750-pull-requests-at-amazon-heres-my-exact-thought-process)
