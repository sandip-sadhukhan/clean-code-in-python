# Chapter 1: Introduction, Code Formatting, and Tools

- When code is structured randomly, without following any logic, or adhering to any standard, then it would be as difficult for us to mistakes as a novice developer. On the other hand if we are used to reading code in a structured fashion, and we have learned to get ideas quickly from the code by following patterns, then we are at a considerable advantage.

- When looking at the code by a peer, you should ask such questions as:

  - Is this code easy to understand and follow to a fellow programmer?
  - Does it speak in terms of the domain of the problem?
  - Would a new person joining the team be able to understand it, and work with it effectively?

- It's good to leverage the `Makefile` as much as possible, and that means configuring your CI tool to also call the commands in the `Makefile`. This way there is a standardized way of running the main tasks in your project, and we place as little configuration as possible in the CI tool(which again, might change in the future,a nd doesn't have to be major burden).
