# Personalize-Emails-using-Crew-AI

# What is Crew AI?

CrewAI is a framework designed to build and manage teams of AI agents and facilitate collaboration between different AI agents. 
It allows you to create individual agents with specific roles and functionalities. These agents can then work together to achieve complex tasks.

## Here's a breakdown of what CrewAI offers 

- Multi-agent Collaboration: CrewAI allows you to create teams of AI agents, each with its own strengths and functionalities.
- These agents can then work together to achieve complex tasks 
- Role-playing Agents: Each agent within CrewAI can be assigned a specific role, with its own goals and area of expertise, similar to members of a human tea.
- Seamless Communication: CrewAI is designed to ensure that the different agents can communicate effectively with each other, fostering smooth collaboration.

# How Crew AI is Used in This Project

This project leverages Crew AI to automate email personalization at scale. It utilizes the Mixtral-8x7B model, a large language model (LLM), for content analysis and generation.

## Individual Agents:

 Email Personalizer Agent: Analyzes recipient information (name, bio, last conversation) and suggests modifications to the email template. It incorporates recipient details while maintaining the core message and structure.

Ghostwriter Agent: Utilizes the Mixtral-8x7B LLM to revise draft emails in a specific writing style. This style is typically informal, engaging, and slightly sales-oriented, with clear, direct communication and a friendly tone.

## Output 

Personalized emails are saved in the output directory with filenames containing the recipient's name and a .txt extension.

## Example Workflow:

- You provide recipient data (name, bio, last conversation) and an email template.
- The Email Personalizer Agent analyzes the data and modifies the template to incorporate relevant details.
- The Ghostwriter Agent revises the personalized draft to match the desired writing style.
- The final, personalized email is saved in the output directory.

By leveraging Crew AI and this project's framework, you can automate email personalization, saving time and effort while achieving better communication outcomes.





  
