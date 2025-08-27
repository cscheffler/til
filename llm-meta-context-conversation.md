# LLM Context Documents and Meta-Conversations

If you're starting a big project where you intend to use LLMs a lot, one of the most useful things you can do is have a meta-conversation with it first. The point of this meta-conversation is to create a _context document_ which you then use in all your other conversations.

## The Context Document

The idea here is that you start each conversation in your project with the contents of this document. It primes the LLM with

* project goals
* constraints
* priorities
* strategy/methodology
* background information
* tools to use or avoid
* the role and/or personality of the LLM

Once it's ready, add it as a file to your project and refer to it at the start of each conversation, or simply paste the contents of the context document at the start of each conversation.

The context document is a _living_ document. You should review and update it regularly as your project evolves or as you update your understanding of the bullet points above.

## The Meta-Conversation

The best part is that you can use an LLM to help you create and refine the context document. My meta-conversation started like this. I'll use finding/applying for a job as an example here. All phrases specific to this example are **highlighted in bold**.

> This is a bit meta but I want to develop a context document for an AI assistant to help it help me **better apply for a job**. I would like you to help me develop that context document. I can provide any information required to put together a document but I'm not sure what the right questions are so that's where I can use your help. What should be in the context document so that I can provide that to another assistant and ask it to help me perform other tasks like **improve my CV or a cover letter, or determine which jobs I might be a good fit for**?
> 
> Product: The output we're aiming for here is a 1-pager context document that I'll provide to an assistant.
> 
> Process: Help me determine the right questions to ask. I can provide the answers. We can iterate this for a while and then we use those questions and answers to put together the context document.
> 
> Role: I want you to act as the question-asker and an export on what current LLM-based AI assistants with thinking enabled need in a context document.

The LLM responded with a great list of questions. I spent the next 30–60 minutes providing detailed answers to these questions and ended up with a great context document. Don't rush through this part! The time you invest here will pay for itself many times over during the rest of the project.
