# The agentic workflow loop

1. **precaption** - Here the agent gather a lot of informations from the user prompts, from external resources like google, etc
2. **Reasoning** - The AI agent see it's now state, And the goals that are provided for it and it's start to compare the diffrence and use the knowledge he have finish the tasks
3. **Action** - This is the output of the agent and in this stage it's achive the tasks that have been providen for it

*And the loop dose not end at the action no the agent update it's knowledge to the new things he have done*

## Perception

**Is where the the user talk to the agent by the prompt it's say his tasks and his goals and what tools to use? and everything the user want is written in the prompt, and also it's updated it's memory and the tools output, Like the agent see the world not just the prompt**

## Reasoning

**Here the AI get the user prompt and start working on it it's see if that tools that the user have gived him will help him or no or if there is better tools, and how can i achive the tasks, etc**

### Example:

**User** - `Please fix to me every code error in this task i want the fixes come only from stack overflow, and then publish the new true code on my twitter and give me a context to say it in my youtube video that explain the fix of the code, and also publish on reddit the youtube video link when i say to you`

**Agent reasoning** - `Ok i should get to the user file and see it's errors and then i should search on stack over flow for fixing those errors i should get the most up-to-date solve and that is the same as the version that user use, and after i finish it i should publsih the old code and the new code and the fixes on twitter with a good explanation and then i should give the user the captions that he will say in his youtube video that how he solved the problem, and then after the user tell me that he finished preparing for his youtubwe video i should publish it on youtube and then provide the link to the uder reddit with good explanation for the video`

***Yeah this is how we use AI agents LOL, well can a chatbot do this?***

## Action

**Where the agent finally finish it's reasoning and the tools and everything and he achived the task that the user want**

## Summary
The agentic loop transforms a static LLM into an active participant in your workflow. By explicitly separating the perception of inputs, the reasoning of intent, and the execution of actions, you turn your Python scripts into entities capable of autonomous decision-making. In our upcoming sessions, we will implement this exact structure, starting with the project folder setup and moving into connecting your local models.
