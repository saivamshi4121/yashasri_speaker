# AI: Mastering Prompt Engineering, Ethics, and Automation 

## Date Time: 14-June-2025 at 10:00 AM IST

## Event URL: https://www.meetup.com/dot-net-learners-house-hyderabad/events/308109558/?eventOrigin=group_upcoming_events

![YASHASRI |150x150](./Documentation/Images/ViswanathaSwamyPK.PNG)

---

### Software/Tools

> 1. OS: Windows 10/11 x64
> 1. Python / .NET 8
> 1. Visual Studio 2022
> 1. Visual Studio Code

### Prior Knowledge

> 1. Programming knowledge in C# / Python

## Technology Stack

> 1. .NET 8, AI, Open AI

## Information

![Information | 100x100](Information.png)

## What are we doing today?
Best Practices for Prompt Engineering

1. Be clear & specific: Avoid vague instructions.
2. Add context/examples: Improve quality with relevant samples.
3. Guide reasoning: Use "Let's think step-by-step" to boost logical output.
4. Assign roles: Help models match tone/expertise.
5. Test multiple prompts: Find what works best.
6. Break down tasks: Use chaining for complex processes.

Types of Prompting

Prompting is the art of crafting clear instructions for AI models using natural language. It helps guide the model’s reasoning, improve accuracy, and ensure structured and relevant responses.

Below are the most effective types of prompting techniques with practical use cases and examples.

1. Zero-Shot Prompting
Ask the model to perform a task without giving any examples.
It is best for simple, common tasks.

Use Cases:
a. Summarization
b. Translation
c. Direct question answering

Example Prompt:
Summarize the sentence : "Artificial intelligence is a rapidly growing field that focuses on building systems capable of performing tasks that typically require human intelligence."

2. Few-Shot Prompting
Provide 2–3 examples to show the model what kind of response is expected.
Ideal for tasks needing consistency or format adherence.

Use Cases:
a. Text formatting
b. Pattern matching
c. Style transfer

Example Prompt:
Q: Convert 'data science' to PascalCase  

A: DataScience
Q: Convert 'student login' to PascalCase  
A: StudentLogin
Q: Convert 'account settings' to PascalCase  
A:

3. Chain-of-Thought Prompting
Guide the model to explain its reasoning step-by-step before giving the answer. It boosts logical and math-based tasks.

Use Cases:
a. Math problems
b. Code analysis
c. Logical reasoning

Example Prompt:
Q: There are 10 cookies. Alice eats 3, and Bob eats 2. How many are left?  
Let's think step-by-step.

4. Prompt Chaining
Break down complex tasks into multiple connected prompts and output of one prompt becomes input for the next.

Use Cases:
a. Task automation
b. Multi-step workflows
c. LangChain, N8N integrations

Example Workflow:

Step 1 Prompt:  
Summarize the following GitHub issue:  
"The login button doesn't work on mobile devices running Safari."

Step 2 Prompt:  
Write a professional email to the mobile dev team with the summary:
"The login button is broken on Safari mobile. Needs urgent fix."

5. Role Prompting
Assign a persona or role to the model to influence the tone or expertise level.

Use Cases:

a. Professional reviews
b. Teaching or explaining concepts
c. Simulated interviews

Example Prompt:
You are a senior software architect.  
Please review the following microservices design for performance and scalability issues.

6. Self-Consistency Prompting
Run the same prompt multiple times and compare the outputs. It is useful for creative or open-ended responses.

Use Cases:
a. Brainstorming
b. Storytelling
c. Metaphor generation

Example Prompt:

Question: Calculate 15% of 240

Path 1:
- 10% of 240 = 24
- 5% is half of 10% = 12
- Total: 24 + 12 = 36

Path 2:
- Convert 15% to decimal: 0.15
- Multiply: 240 × 0.15 = 36

Path 3:
- Break down into: (240 × 10/100) + (240 × 5/100)
- = 24 + 12
- = 36

All paths converge on 36, indicating high confidence in the answer.
> 1. SUMMARY / RECAP / Q&A
>    - Recap of key topics covered.
>    - Open Q&A session for participants.
>    - Follow-up queries will be addressed via meetup chat or Twitter.


---

![Information | 100x100](SeatBelt.png)

---

## Developer's Guide to AI Evolution & Prompt Engineering
## 1. Our Progress Over Time
From Basic Tools to AI-Powered Development

Historical Context:

1980s: Monochrome IDEs with limited functionality

2020s: AI-assisted coding with real-time suggestions and error detection

## Example:

python
 Old: Manual code completion
 New: AI suggests complete functions based on comments
## 2. GitHub Copilot in Action
Real-World Prompt Engineering for Developers

## Effective Prompt Patterns:
text
# As a senior Python developer, write a Flask endpoint that:
# - Accepts JSON input
# - Validates email format
# - Returns 400 if invalid

Debugging with CoT:
text
Explain why this React component fails. Analyze step-by-step:
[Problem Code]


## 3. Expanding AI Use Cases

Prompt Engineering Across Domains
Domain	Prompt Technique	
## Example
DevOps	Few-Shot Prompting	"Convert these YAML to Terraform: [examples]"
Customer Support	Role Prompting	"As a support agent, respond to: 'My order is late'"
Technical Writing	Zero-Shot + Constraints	"Explain Kubernetes pods (1 paragraph, non-technical)"

## 4. Accelerating Work with RAG Systems
Advanced Prompt Chaining for Knowledge Retrieval

Workflow Example:

## Retrieval Prompt:
"Extract key points from our API documentation about authentication"

## Generation Prompt:
"Using these points, create a troubleshooting guide for auth errors (markdown)"

> 1. Demonstrating how Retrieval-Augmented Generation (RAG) can speed up workflows.

### Streamlining Our Jobs with AI

> 1. Using AI to simplify tasks while keeping security in focus.

### Automating Repetitive Tasks

> 1. Utilizing batch files, PowerShell scripts, etc., to reduce manual work.

### Getting Started with AI

> 1. Key resources and starting points: [Microsoft AI Developer Resources](https://developer.microsoft.com/en-us/ai).

### Data-Driven Learning in AI

> 1. How AI learns from our data to continuously improve and adapt.

### The Future of AI-Driven Development

> 1. Exploring emerging trends, innovations, and ethical considerations that will shape the next generation of developer tools and practices.
> 1. A look at how the evolving AI landscape will further empower developers, and how we can prepare for these changes.

---
### Key Guidelines

- **Be Explicit**: Clearly define the task and expected output.
- **Test and Iterate**: Continuously refine prompts based on results.
- **Leverage Context**: Provide relevant background information.
- **Monitor and Adjust**: Regularly evaluate and tweak prompts.

---

##  Sample Prompts

> 1. A collection of sample prompts for demonstration purposes.

### Example Prompts

```text
# Example 1: Summarization Prompt
Summarize the following text in 50 words or less:
"Artificial Intelligence (AI) is a branch of computer science that aims to create machines that can perform tasks that would typically require human intelligence. Examples include learning, reasoning, problem-solving, and language understanding. AI is increasingly being used in various industries to improve efficiency and decision-making."
```

```text
# Example 2: Sentiment Analysis Prompt
Analyze the sentiment of the following text and classify it as Positive, Negative, or Neutral:
"The product quality is excellent, and the customer service was outstanding."
```

```text
# Example 3: Role Play Prompt
You are a customer support agent. Respond to the following customer query:
"I received a damaged product. Can I get a replacement?"
```

```text
# Example 4: Code Generation Prompt
Generate a Python function to calculate the factorial of a number using recursion.
```

```text
# Example 5: Translation Prompt
Translate the following sentence into French:
"The weather is beautiful today."
```

```text
# Example 6: Zero Shot Prompt
What is the capital of France?
```

```text
# Example 7: Single Shot Prompt
Q: What is the capital of France?
A: The capital of France is Paris.

Q: What is the capital of Germany?
```

```text
# Example 8: Few Shots Prompt
Q: What is the capital of France?
A: The capital of France is Paris.

Q: What is the capital of Germany?
A: The capital of Germany is Berlin.

Q: What is the capital of Italy?
```

```text
# Example 9: Chain of Thought (CoT) Prompt
Please solve the following problem using a Chain of Thought (CoT) approach, which involves breaking the problem down into smaller, logical steps to ensure a clear and systematic progression to the solution. Show each intermediate step and explain your reasoning.

Example Problem: "A bakery had 50 cupcakes. They sold 15 in the morning and then baked 20 more in the afternoon. How many cupcakes do they have now?"

**Expected CoT Response:**

1. Start with the initial number of cupcakes: 50.
2. Subtract the number of cupcakes sold in the morning: \( 50 - 15 = 35 \).
3. Add the number of cupcakes baked in the afternoon: \( 35 + 20 = 55 \).
4. The bakery now has 55 cupcakes.

Q: Roger has 5 tennis balls. He buys 2 more cans of tennis balls. Each can has 3 tennis balls. How many tennis balls does he have now?
A: Roger started with 5 balls. 2 cans of 3 tennis balls each is 6 tennis balls. 5 + 6 = 11. The answer is 11.

Q: The cafeteria had 23 apples. If they used 20 to make lunch and bought 6 more, how many apples do they have?
```

```text
# Example 10: Sample Prompt for Social Media Post
Create a Twitter post for "101 Dosa Center". Highlight the following:
- Home-made spices
- Generous use of butter
- Dosas made with love
- Keep the tone warm and inviting.

Example:
"Craving something delicious? 🍽️ At 101 Dosa Center, we bring you dosas made with love, home-made spices, and lots of butter! 🧈✨ Taste the tradition in every bite. ❤️ #DosaLovers #FoodieHeaven"
```

````texts
#Example:  Blog Post Generation Prompt

Generate a detailed blog post about '{topic}'.
Include an introduction, multiple main sections, optional code snippets, and a conclusion.
Use proper **Markdown syntax** to format each section.

The blog post must include the following Markdown elements:

Headings
# Heading Level 1
## Heading Level 2
### Heading Level 3

Paragraphs
Just write regular text separated by line breaks for paragraphs.

Unordered List
- Item 1
- Item 2
- Item 3

Ordered List
1. First item
2. Second item
3. Third item

Blockquote
> “Experience is simply the name we give our mistakes.”
> — Oscar Wilde

Code Block (JavaScript example)
```js
function helloWorld() {
  console.log(""Hello, world!"");
}
````

---

##  Chat Playground

> 1. Hands-on demonstration of interacting with OpenAI models using the chat playground.

## ![Chat using Playground](./Documentation/Images/Chat_Using_PlayGround.PNG)


## SUMMARY / RECAP / Q&A

> 1. Recap of key topics covered.
> 2. Open Q&A session for participants.
> 3. Follow-up queries will be addressed via meetup chat or Twitter.

---
