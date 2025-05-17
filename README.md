# Exno.7-Prompt-Engineering
# Date:07-05-2025
# Register no: 212222040168
# Aim: 
To Develop a prompt-based application tailored to their personal needs, fostering creativity and practical problem-solving skills while leveraging the capabilities of large language models.

# Algorithm: 
Develop a prompt-based application using ChatGPT - To demonstrate how to create a prompt-based application to organize daily tasks, showing the progression from simple to more advanced prompt designs and their corresponding outputs.

Step 1: Basic Task Organizer (Zero-shot Prompting)
```
def basic_prompt(task_list):
    prompt = f"Here is my task list: {task_list}. Organize it for me."
    return chat_with_gpt(prompt)
```
Step 2: Improved Prompt with Instructions (Direct Prompting)
```
def direct_instruction_prompt(task_list):
    prompt = f"""I have these tasks today: {task_list}
Please:
1. Categorize them into 'Urgent', 'Important', and 'Optional'
2. Sort them by time or priority
3. Give a short motivational tip"""
    return chat_with_gpt(prompt)
```
 Step 3: Persona-Based Prompting (Friendly Coach)
 ```
def role_based_prompt(task_list):
    prompt = f"""You are my personal productivity coach.
Here are my tasks: {task_list}
Please help me plan the day with priorities and encouragement."""
    return chat_with_gpt(prompt)
```
Step 4: Chain-of-Thought Prompting
```
def chain_of_thought_prompt(task_list):
    prompt = f"""Let's break this down step by step.
I have these tasks: {task_list}
First, identify the most time-sensitive tasks. Then, group similar tasks together.
Finally, suggest a schedule with breaks and tips to stay focused."""
    return chat_with_gpt(prompt)
```
 Step 5: Prompt with User Preferences (Advanced Customization)
 ```
def personalized_prompt(task_list, wake_time, energy_levels):
    prompt = f"""I wake up at {wake_time}, and I feel more energetic in the {energy_levels}.
Here's my task list: {task_list}
Please generate a detailed, energy-aware day plan with task priorities and relaxation slots."""
    return chat_with_gpt(prompt)
```
# Result: 

This application demonstrates a clear progression in prompt complexity and output quality, enabling users to:

Organize daily tasks better

Learn prompt engineering by example

Develop creative and practical problem-solving strategies using LLMs

**The Prompt is executed successfully**


