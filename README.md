---
title: Yourname Simulatesearch
emoji: 🦀
colorFrom: indigo
colorTo: indigo
sdk: gradio
sdk_version: 6.0.2
app_file: app.py
pinned: false
short_description: project
thumbnail: >-
  https://cdn-uploads.huggingface.co/production/uploads/693534ba07c9e7f7eabe92b2/0Dbb7Ip9n0A8Bo97R75cB.jpeg
---
Linear Search Visualizer

Demo Screenshot

![image](https://cdn-uploads.huggingface.co/production/uploads/693534ba07c9e7f7eabe92b2/bEsEK0r0HRPVsvJJaKMQs.png)

![image](https://cdn-uploads.huggingface.co/production/uploads/693534ba07c9e7f7eabe92b2/gdA4mZKfQYcwvDLelYktK.png)

Problem Breakdown and Computational Thinking

Decomposition
Generate a random list of integers.
Ask the user for a target number.
Check each element in the list one-by-one.
Stop when the number is found, or after the last element.
Report the result and show the steps.

Pattern Recognition
Each step repeats the same action:
Compare `target` with `arr[i]`.
Move to the next index if not equal.
This repeating pattern is implemented with a `for` loop over the list.

Abstraction
The user only sees:
The list
The number they typed
A step-by-step explanation
Internal details like indices and loop counters are hidden inside the function.

Algorithm Design (Input → Process → Output)
Input:
A randomly generated list of integers.
A target integer entered by the user.
Process:
Linear search checks each element from left to right.
Output:
A trace of each comparison.
A final message saying whether the number was found (and where).

steps to run

run locally

1.Create and activate a virtual environment
2. Install dependencies:
   pip install -r requirements.txt
Check out the configuration reference at https://huggingface.co/docs/hub/spaces-config-reference
