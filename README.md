# EX-02-Cross-Platform-Prompting-Evaluating-Diverse-Techniques-in-AI-Powered-Text-Summarization

## AIM
To evaluate and compare the effectiveness of prompting techniques (zero-shot, few-shot, chain-of-thought, role-based) across different AI platforms (e.g., ChatGPT, Gemini, Claude, Copilot) in a specific task: text summarization.

## SCENARIO
You are part of a content curation team for an educational platform that delivers quick summaries of research papers to undergraduate students. Your task is to summarize a 500-word technical article on "The Basics of Blockchain Technology" using multiple AI platforms and prompting strategies.

## ALGORITHM
### 1. Article Selection: 
Use a 500-word article explaining blockchain basics in a technical tone.

### 2. Prompt Design:

* Zero-shot: A direct instruction like “Summarize the following text in simple terms for undergraduate students.”

* Few-shot: Provide two or three example summaries of similar articles before asking the model to generate a new one.

* Chain-of-thought: Instruct the AI to reason through key ideas step-by-step before composing a summary.

* Role-based: Ask the AI to take on a persona (e.g., a professor) and explain the article to beginners.

### 3. Execution:
Input each prompt variant into ChatGPT, Gemini, Claude, and Copilot. Measure:

* Accuracy of content

* Coherence and flow

* Simplicity of language

* Speed of response

* User experience with the interface

### 4. Evaluation: 
Manually assess each output using a 1–5 scale for each of the five criteria. Averages help identify the best-performing combinations.

### 5. Comparison and Ranking:
Review overall performance across all combinations to determine the most effective platform + prompt strategy.

## RESULT
* The results showed that Claude combined with Chain-of-Thought prompting delivered the most effective summaries. This combination excelled in accuracy, logical flow, and maintaining clarity, especially when simplifying technical terms. While slightly slower than zero-shot methods, the quality trade-off was worth it.

* ChatGPT with zero-shot prompting was the fastest, producing quick summaries that were generally accurate and simple, though sometimes lacked depth.

* Gemini with few-shot prompting provided solid results, especially when the examples were well-chosen. However, performance depended heavily on the quality and relevance of the examples provided.

* Copilot using role-based prompting was easy to work with and produced relatable summaries, but occasionally lost technical accuracy due to over-simplification.
# EX-2 Comparative Analysis of different types of Prompting patterns and explain with Various Test scenerios
# AIM: 

Test and compare how different pattern models respond to various prompts (broad or unstructured) versus basic prompts (clearer and more refined) across multiple scenarios. Analyze the quality, accuracy, and depth of the generated responses.

# Aim of the Study:

To test and compare how different models respond to various prompts — from open-ended or vague queries to well-structured and specific instructions — and to analyze how these variations impact: 
- Response quality
- Depth of understanding
- Accuracy and relevance
# Methodology:

1. Select three categories of prompts:
   - Broad/unstructured
   - Basic/clear
   - Creative/advanced

2. Use three major AI tools for response generation:
   - ChatGPT (OpenAI)
   - Claude (Anthropic)
   - DeepSeek (DeepSeekAI)

3. For each prompt type, responses will be:
   - Evaluated qualitatively (coherence, depth, relevance)
   - Rated quantitatively (scale of 1–5)

4. Additionally, prompt inputs are given to:
   - Runway: to evaluate prompt interpretation for video generation
   - Midjourney: to visualize response accuracy in image generation
# Prompt Types Explained:
1.Broad/Unstructured Prompt:
A Broad/Unstructured Prompt is a general or vague instruction given to an AI model, such as “Tell me about AI.” It lacks specific details or direction, leading to wide-ranging, often superficial responses. These prompts offer creative freedom but may result in less focused or less relevant outputs.
 e.g., "Tell me about AI."

2. Basic/Refined Prompt: 
A Basic/Refined Prompt is a clearly structured and specific instruction given to an AI model. It includes details like context, desired output, and format, guiding the model toward accurate, relevant, and high-quality responses. These prompts reduce ambiguity and enhance the depth and usefulness of the generated content.
e.g., "Explain how AI is used in the healthcare sector with examples."

3. Creative/Advanced Prompt: 
A creative/advanced prompt is a highly specific and imaginative instruction designed to unlock an AI's full potential. It encourages originality, emotional depth, and contextual richness. These prompts often involve storytelling, hypothetical scenarios, or complex tasks, resulting in more nuanced, engaging, and insightful responses compared to basic or broad prompts.
e.g., "Generate a short sci-fi story where AI is used to terraform Mars, with emotional conflict."
Scenario 1 – General Information Retrieval
Prompt Type 1: "Talk about space"
- ChatGPT: Gives a broad overview
- Claude: Focuses on key areas
- DeepSeek: Detailed facts and organized output

Prompt Type 2: "List five recent space missions by NASA and their purpose"
- ChatGPT: Highly accurate
- Claude: Deeper technical insight
- DeepSeek: Systematic list

Observation: Refined prompts yield more relevant and focused responses.
Scenario 2 – Creative Content Generation
Prompt Type 1: "Write a story about robots"
- ChatGPT: Engaging, generic plot
- Claude: Philosophical themes
- DeepSeek: Balanced creativity and logic

Prompt Type 2: "Write a short story where a robot discovers human art in a post-apocalyptic world"
- All models delivered richer, more compelling narratives with strong emotional arcs

Observation: Advanced prompts unleash more creativity and coherence.
Scenario 3 – Instructional/Procedural Response
Prompt Type 1: "How to bake a cake?"
- All models: Provided basic steps

Prompt Type 2: "Provide a step-by-step chocolate cake recipe with measurements and baking time"
- Responses: Detailed, instructional, and more actionable

Observation: Clarity in prompt enhances instructional usefulness.
Scenario 4 – Visual Media Creation
Tool Used: Midjourney (Image) and Runway (Video)

Prompt Type 1: "Create an image of a city"
- Midjourney: Generic skyline
- Runway: Vague visuals

Prompt Type 2: "Generate a futuristic city at night with flying cars and neon lights"
- Midjourney: Stunning, detailed visuals
- Runway: High-concept sci-fi aesthetic

Observation: Specific descriptors vastly improve visual content.
# Evaluation Metrics:

Responses were rated based on:
- Relevance
- Depth
- Creativity
- Accuracy
- Clarity

Scores ranged from 1 (low) to 5 (high). Refined prompts consistently scored higher.
# Key Findings:

1. Broad Prompts often lead to surface-level, generic responses.
2. Refined Prompts improve depth, clarity, and focus.
3. Creative Prompts unlock the AI's potential for nuanced and original outputs.
4. Models differ slightly in style:
   - ChatGPT: Balanced and versatile
   - Claude: Contextually deep and philosophical
   - DeepSeek: Structured and informative
# Best Practices for Prompting:

Tips:
- Be clear about your intent
- Use specifics (what, who, how, when)
- Combine creative and structured phrasing
- Use follow-up prompts for deeper insights

Example:
Bad: "Talk about climate."
Good: "Explain three ways climate change affects coastal cities, with real-world examples."
# Conclusion:

This comparative study highlights the critical role that prompt engineering plays in AI interaction. More refined and detailed prompts consistently produce better, richer, and more useful outputs. As generative AI tools become more prevalent, users must learn how to communicate effectively with these systems to harness their full capabilities.
