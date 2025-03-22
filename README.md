# ForwardSentry
An Agentic AI application designed to trace the flow of forwarded messages and transactions, enabling  tracking and analysis for use cases like Fake news detecting and monitoring and financial fraud detection.

ForwardSentry was inspired by the growing need to understand and track the spread of information/mis-information in our connected world. We recognized that the same principles used to trace message forwarding could be applied to track financial transactions, potentially uncovering complex networks of communication or money laundering schemes.

# What it does
ForwardSentry is a sophisticated application that traces the path of forwarded messages across networks. It uses Arango graph database technology and semantic analysis to:

- Map the journey of messages as they're forwarded between users
- Identify similar messages using vector embedding similarity
- Using web, verifies if the sent message was a fact or fake.

# Built ForwardSentry using:

- ArangoDB for graph database to store and query relationships between users and messages
- Python for backend logic and data processing
- Sentence transformers for semantic analysis of message content
- SerpAPI for web search to verify authenticity of message.
- AQL (ArangoDB Query Language) for efficient graph traversal and similarity searches

## How to naviagte
- ForwardSentry.pdf contains overview of developed application
- ArangoDB_Hackathon_ForwardSentry.ipynb Jupyter notebook executed on Google colab contains detailed steps to execute.

[Devpost](https://devpost.com/software/forwardsentry) [YouTube](https://www.youtube.com/watch?v=jptUIBSPxuw)
