# EX-02-Cross-Platform-Prompting-Evaluating-Diverse-Techniques-in-AI-Powered-Text-Summarization

## AIM
To evaluate and compare the effectiveness of prompting techniques (zero-shot, few-shot, chain-of-thought, role-based) across different AI platforms (e.g., ChatGPT, Gemini, Claude, Copilot) in a specific task: text summarization.

## Scenario:
You are part of a content curation team for an educational platform that delivers quick summaries of research papers to undergraduate students. Your task is to summarize a 500-word technical article on "The Basics of Blockchain Technology" using multiple AI platforms and prompting strategies.

Your goal is to determine which combination of prompting technique + platform provides the best summary in terms of:

Accuracy

Coherence

Simplicity

Speed

User experience

## Algorithm
## chatgpt : Algorithm-driven structured prompting.
# summary
The prompting strategy used was mainly structured instruction prompting, where the task was divided into clear steps and sections. The prompt also used chain-of-thought style reasoning by giving an algorithmic sequence to follow. Output-constrained prompting was applied by specifying the exact format, diagrams, and result section needed. Contextual prompting helped the AI understand that the response should match an engineering lab report style. Overall, the prompt was detailed, organized, and goal-oriented, which improved the quality of the generated output.
# Evaluation
Accuracy:Correctly identifies the prompting strategies used, Coherence:Ideas flow logically from one point to another,
Simplicity: Uses simple and understandable language suitable for students., Speed:Information is concise and quickly understandable in 4–5 lines., User experience: Easy and understandable 9.5/10.

## Gemini : Iterative Prompting (Feedback Loop)
# Summary
Blockchain functions as a decentralized, peer-to-peer digital ledger that records data in secure, linked blocks to make information immutable. Key components like cryptographic hashes, consensus mechanisms, and smart contracts eliminate intermediaries, reducing transaction costs and removing single points of failure. Despite challenges like scalability, high energy consumption, and evolving regulations, its inherent transparency and efficiency continue to drive widespread adoption. Today, major global industries—including finance, healthcare, and supply chain management—actively leverage blockchain to prevent fraud and automate complex agreements.
# Evaluation
Accuracy:successfully extracted the core concepts, Coherence:The explanation of your prompting technique was also structured clearly. Simplicity: understandable Speed: fast User experience: had to ask multiple times for expected output

## copilot : contextual prompt
# Summary 
Blockchain is a decentralized, immutable digital ledger that records transactions securely across a distributed network of computers. It eliminates the need for intermediaries, enhances transparency, and ensures trust through cryptography and consensus mechanisms.
# Evaluation
Accuracy: Gave the informations correctly but can be iproved Coherence: good Simplicity: school students can also understand Speed: Fast User experience: good

## Result
Thus, different prompting strategies were tested across multiple AI platforms for summarizing a technical article on blockchain technology.
