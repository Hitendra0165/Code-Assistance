## Code-Assistance
This project provides an interactive interface for generating code assistance using the Aiguru model. Users can input prompts related to code queries, and the system will generate responses based on the provided prompt.

#Files
app.py: This Python script contains the main functionality of the project. It uses the Aiguru model to generate responses to code-related prompts provided by the user. The script utilizes the Gradio library to create a simple web interface for users to interact with.

Modelfile: This file contains configuration parameters for the Aiguru model. It sets the temperature parameter to 1 and provides a system prompt for generating responses.

Requirement.txt: This file lists the required dependencies for running the project. It includes the langchain library for language processing and the gradio library for creating the interface.

Usage

To use this project:
Ensure you have Python installed on your system.

Install the required dependencies listed in Requirement.txt using pip.
pip install -r Requirement.txt

Run the app.py script.
python app.py

Notes
I used OLLAMA for The Aiguru model used in this project is trained to provide assistance with code-related queries.
The provided system prompt sets the context for generating responses.
Users can adjust the temperature parameter in the Modelfile to control the randomness of the generated responses.
