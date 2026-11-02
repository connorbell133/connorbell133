# Connor Bell

I’m a Senior AI Platform Engineer at Optura, where I co-lead the Knowledge Platform team. I led the first client deployment of Librarian and now build the context engine behind it. My part of the platform determines what an agent can retrieve, whose definition applies, and how to trace an answer back to its source.

One question I keep coming back to is what happens when someone loses access to a source after an agent has already used it. You can check permissions on the next query. What about a cached answer, or a procedure the agent learned last week?

## Writing

**[The Warehouse Has a Column. It Doesn’t Have the Argument.](https://connorbell.dev/writing/the-warehouse-has-a-column)**  
If operations says a claim takes ten minutes and the adjusters say twenty, which number should an agent use? I wrote about what a knowledge layer needs to preserve when the people who know the work disagree.

## Public projects

- **[AgentFlow](https://github.com/connorbell133/Agentflow)** lets teams put an existing AI endpoint behind a shared chat interface. Group permissions control which agents each user can reach, and Postgres row-level security keeps each organization’s data separate.
- **[Async agent example](https://github.com/connorbell133/async-agent-example)** shows how to keep a conversation going while a tool runs in the background. When the task finishes, its result goes back into the conversation. Built with TypeScript, Next.js, and the AI SDK.

[Personal site](https://connorbell.dev/) · [LinkedIn](https://www.linkedin.com/in/connorbell13/)
