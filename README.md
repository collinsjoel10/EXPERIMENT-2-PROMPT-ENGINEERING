# EXP-2-PROMPT-ENGINEERING-

## Aim: 
Comparative Analysis of different types of Prompting patterns and explain with Various Test Scenarios

Experiment:
Test and compare how different pattern models respond to various prompts (broad or unstructured) versus basic prompts (clearer and more refined) across multiple scenarios. 
Analyze the quality, accuracy, and depth of the generated responses.


## Algorithm:
1.Identify different prompt styles – Broad, Basic, Refined.

2.Select test scenarios – Automated Test Script Generation, Bug Identification, Performance Test Planning.

3.Apply each prompt type to all scenarios.

4.Record and document AI responses.

5.Evaluate based on clarity, accuracy, depth, and relevance.

6.Compare and analyze which prompting style performs best.

7.Analyze Findings – Identify which prompting style is most effective for each task.

## Output
Comparative Analysis of Prompting Patterns

# Objective:

To evaluate and compare the effectiveness of different prompting techniques — Zero-Shot, Few-Shot, Chain-of-Thought, and Role-Based Prompting — by testing them on varied scenarios. The goal is to analyze quality, accuracy, and depth of responses across broad/unstructured prompts and refined/structured prompts.

# Prompting Techniques Considered

# Zero-Shot Prompting

*Direct question without examples.

*Tests how the model leverages prior knowledge.

# Few-Shot Prompting

*Provides 2–3 examples before asking the main question.

*Tests model learning through context.

# Chain-of-Thought Prompting (CoT)

*Encourages step-by-step reasoning before answering.

*Tests logical depth and correctness.

# Role-Based Prompting

Assigns a persona or role (e.g., “Act as a teacher”).

*Tests contextual adaptability and tailored explanations.

# Scenarios Tested:

*Summarization – Summarizing a technical passage.

*Math Problem Solving – Solving a word problem.

*Creative Writing – Generating a short story.

*Decision Making – Recommending the best option in a real-world case.

# Prompt Types:

*Broad / Unstructured Prompt: vague or loosely framed.

*Refined / Structured Prompt: specific and clear instruction.

# Evaluation Metrics:

*Quality (clarity, fluency)

*Accuracy (fact correctness, reasoning validity)

*Depth (detail, comprehensiveness)

# Scenario 1: Summarization of a Research Passage

Unstructured Prompt: “Summarize this article on Generative AI.”

Refined Prompt: “Summarize the following 500-word article on Generative AI into 3 bullet points focusing on architecture, applications, and challenges.”

Prompting Pattern	Broad/Unstructured	Refined/Structured	Analysis
Zero-Shot	Generic summary, sometimes missing technical depth.	Clear, concise summary but less nuanced.	Works well when instructions are explicit.
Few-Shot	More aligned with intended format (bullets) due to examples.	Excellent structure, covers key aspects.	Performs best with examples.
CoT	Produced overly long reasoning in broad prompt.	Stepwise breakdown gave detailed yet clear summary.	Useful for deeper insights.
Role-Based	Summary framed in teacher-friendly language.	Simplified explanation with context for students.	Best for audience-focused responses.

# Scenario 2: Math Problem Solving

Problem: “A train travels 120 km in 2 hours. What is its average speed?”

Prompting Pattern	Broad Prompt (“Solve this problem”)	Refined Prompt (“Show step-by-step calculation for speed = distance/time”)	Analysis
Zero-Shot	Correct but brief (“60 km/h”).	Still short but accurate.	Limited reasoning.
Few-Shot	Correct, mimicked example style.	Neatly aligned with example structure.	Good for formatting answers.
CoT	Broke problem into distance/time reasoning.	Very detailed, accurate, transparent.	Best for math/logical problems.
Role-Based	Explained as if to a student.	Detailed explanation in teaching tone.	Best when clarity for learners is required.

# Scenario 3: Creative Writing

Prompt: “Write a short story about a robot.”

Prompting Pattern	Broad Prompt	Refined Prompt (“Write a 150-word story about a robot learning human emotions, in a hopeful tone”)	Analysis
Zero-Shot	Generic robot story, sometimes bland.	Better alignment with theme and word limit.	Performs decently if instructions are explicit.
Few-Shot	Learned narrative style from examples.	Very creative, aligned with examples.	Boosts originality.
CoT	Sometimes over-explains, story feels mechanical.	Good for planning story structure but may lack flair.	Not ideal for creativity.
Role-Based	Story framed as if told by a storyteller/teacher.	Captivating, audience-tailored narrative.	Best for storytelling.

# Scenario 4: Decision Making (Recommendation Task)

Prompt: “Which laptop should I buy?”

Refined: “Recommend a laptop under ₹60,000 for machine learning tasks, with reasoning on CPU, GPU, and RAM.”

Prompting Pattern	Broad Prompt	Refined Prompt	Analysis
Zero-Shot	Gave generic laptop brands.	Suggested specific models, but shallow reasoning.	Needs clarity in prompt.
Few-Shot	Followed example recommendation style.	Provided structured recommendation with pros/cons.	Strong when examples exist.
CoT	Broke down requirements (budget → CPU → GPU).	Transparent reasoning, best trade-off explanation.	Excellent for decisions.
Role-Based	Framed recommendation as a consultant/expert.	Detailed with buyer-oriented explanation.	Best for real-world advisory tasks.

## Result
Thus, a comparative analysis of prompting styles was successfully conducted, and it was observed that refined and well-structured prompts significantly enhance the clarity, accuracy, and depth of AI outputs.
