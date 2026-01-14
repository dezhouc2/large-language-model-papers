# Prompt-Engineering Paper

## How prompt format affects model output accuracy: 
  https://arxiv.org/pdf/2310.11324

## Chain-of-Thought Prompting Elicits Reasoning in Large Language Models
  https://arxiv.org/abs/2201.11903

## Tree of Thoughts: Deliberate Problem Solving with Large Language Models
  https://arxiv.org/abs/2305.10601

## Self-Consistency Improves Chain of Thought Reasoning in Language Models
  https://arxiv.org/abs/2203.11171

## Chain-of-Verification Reduces Hallucination in Large Language Models
   https://arxiv.org/pdf/2309.11495
   
  Step 1: Initial Response Generation  
  The model directly answers the user’s question (which may contain hallucinations).
  
  Step 2: Generate Verification Questions  
  Based on the initial answer, automatically design a set of verification questions (for example:  
  Initial answer: “Albert Einstein won the 1921 Nobel Prize in Physics.”  
  Verification questions: “For what work did Einstein receive the award? Was the award year between 1900 and 1950?”).
  
  Step 3: Isolated Verification Execution  
  Answer each verification question in an independent context (to avoid contamination from initial errors), forcing the model to retrieve factual evidence.
  
  Step 4: Compare and Revise the Answer  
  Compare the verification results with the initial answer and automatically correct any inconsistencies (e.g., fixing an incorrect year).


## Scaling Instruction-Finetuned Language Models
  https://arxiv.org/abs/2210.11416
