

# EXP 5: COMPARATIVE ANALYSIS OF DIFFERENT TYPES OF PROMPTING PATTERNS AND EXPLAIN WITH VARIOUS TEST SCENARIOS

# Aim: 
To test and compare how different pattern models respond to various prompts (broad or unstructured) versus basic prompts (clearer and more refined) across multiple scenarios.  Analyze the quality, accuracy, and depth of the generated responses 

# Explanation: 
Define the Two Prompt Types:

Write a basic Prompt: Clear, detailed, and structured prompts that give specific instructions or context to guide the model.
Based on that pattern type refined the prompt and submit that with AI tool.
Get the ouput and write the report.

Prepare Multiple Test Scenarios:
Select various scenarios such as:
Generating a creative story.
Answering a factual question.
Summarizing an article or concept.
Providing advice or recommendations.
Or Any other test scenario
For each scenario, create both a naïve and a basic prompt. Ensure each pair of prompts targets the same task but with different levels of structure.
Run Experiments with ChatGPT:
Input the naïve prompt for each scenario and record the generated response.
Then input the corresponding basic prompt and capture that response.
Repeat this process for all selected scenarios to gather a full set of results.
Evaluate Responses : 
	Compare how ChatGPT performs when given naïve versus basic prompts and analyze the output based on Quality,Accuracy and Depth. Also analyse does ChatGPT consistently provide better results with basic prompts? Are there scenarios where naïve prompts work equally well?
Deliverables:
A table comparing ChatGPT's responses to naïve and basic prompts across all scenarios.
Analysis of how prompt clarity impacts the quality, accuracy, and depth of ChatGPT’s outputs.
Summary of findings with insights on how to structure prompts for optimal results when using ChatGPT.


# OUTPUT:
Prompting Patterns <br> 
Common patterns include zero-shot (direct task without examples), few-shot (with input-output examples), and chain-of-thought (CoT, step-by-step reasoning). Structured prompts like few-shot CoT outperform zero-shot by 5-15% in accuracy on reasoning tasks, as they provide context and guide logical paths. Negative prompting avoids unwanted outputs, while instruction-based patterns break tasks into clear steps for precision. <br>
​

Test Scenario 1: Classification <br> 
Unstructured (broad): Classify this: The excretory system removes waste. <br>​
Structured (few-shot CoT): Examples: Q: Does kidney filter blood? A: Yes, step 1: Identify organ function, step 2: Match to passage. Now classify: The excretory system removes waste. <br>​
Structured yields higher F1 scores by leveraging examples for context, reducing errors in ambiguous cases. <br>​

Test Scenario 2: Reasoning <br> 
Unstructured: Solve: If A > B and B > C, is A > C?​ <br>
Structured (zero-shot CoT): Solve step by step: If A > B and B > C, is A > C? <br>​
CoT boosts accuracy without examples, as models generate internal logic better than broad queries. <br>

| Pattern           | Quality (Depth) | Accuracy | Best For         | Limitation arxiv+1​                                     |
| ----------------- | --------------- | -------- | ---------------- | -------------------------------------------------------|
| Zero-shot         | Low             | 60-70%   | Simple facts     | Lacks context, poor on complex tasks                   |
| Few-shot          | Medium-High     | 75-85%   | Classification   | Needs good examples, can confuse with poor ones vellum​ |
| CoT               | High            | 80-90%   | Reasoning        | Verbose outputs pmc.ncbi.nlm.nih​                       |
| Instruction-based | High            | 85%+     | Structured tasks | Requires precise wording linkedin​                      |



# RESULT: 
The prompt for the above said problem executed successfully
