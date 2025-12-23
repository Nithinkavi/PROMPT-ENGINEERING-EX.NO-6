# Ex.No.6 Development of Python Code Compatible with Multiple AI Tools

# Date:23.12.2025
# Register no:25016374
# Aim: 
Write and implement Python code that integrates with multiple AI tools to automate the task of interacting with APIs, comparing outputs, and generating actionable insights with Multiple AI Tools

# AI Tools Required:
Chatgpt,copilot,gemini

# Explanation:
Experiment the persona pattern as a programmer for any specific applications related with your interesting area. 
Generate the outoput using more than one AI tool and based on the code generation analyse and discussing that. 

# Code:
```
# Python program to compare responses from multiple AI tools
# Domain: Smart Education Systems

# Persona-based prompt
persona_prompt = """
Act as an educational data analyst.

Explain how artificial intelligence can be used in
online learning platforms to personalize student learning
and give one simple example.
"""

# Function to simulate responses from different AI tools
def get_ai_output(tool_name):
    print(f"\n--- Response from {tool_name} ---")

    simulated_outputs = {
        "ChatGPT": "AI analyzes student performance and learning patterns to recommend personalized lessons and practice materials.",
        "Gemini": "Online learning platforms use AI to study student behavior and adapt course content based on individual progress.",
        "Copilot": "AI helps educators by tracking student activity and suggesting learning resources suited to each learner."
    }

    return simulated_outputs.get(tool_name, "AI tool not available.")

# List of AI tools
ai_tools = ["ChatGPT", "Gemini", "Copilot"]

# Dictionary to store responses
responses = {}

# Collect responses
for tool in ai_tools:
    output = get_ai_output(tool)
    responses[tool] = output
    print(output)

# Simple comparison based on word count
print("\n--- Comparative Analysis ---")
for tool, text in responses.items():
    print(f"{tool}: {len(text.split())} words")

```

# Conclusion:
[EX 06.docx](https://github.com/user-attachments/files/24310053/EX.06.docx)


# Result: The corresponding Prompt is executed successfully.
