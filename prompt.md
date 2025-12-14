# Multi-Step Prompt: Beach Vacation Planner

## Overview
This file contains a multi-step prompt designed as part of a prompt engineering exercise using OpenAI.

## Prompt Code

```python
from openai import OpenAI

client = OpenAI(api_key="<OPENAI_API_TOKEN>")

prompt = """
Help me plan a beach vacation.

Step 1 - Specify four potential locations for beach vacations.
Step 2 - State some accommodation options in each.
Step 3 - State activities that could be done in each.
Step 4 - Evaluate the pros and cons for each destination.
"""

response = get_response(prompt)
print(response)
